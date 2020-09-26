https://linux-kernel-labs.github.io/refs/heads/master/labs/filesystems_part1.html



~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Locking                                           
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
# Professional Linux Kernel Architecture
> Ch 5 (start : 366)
# Mastering Linux Kernel Development
> Ch 8 (489:500) (500:  )
# Love
> Ch 9 & 10 (Done Semaphore 190:194)
# Operating Systems Three Easy Pieces
> part 2
# Understanding Linux Kernel
> Ch 5 (189: 199)

> Awesome source MUST to read https://www.kernel.org/doc/htmldocs/kernel-locking/index.html
## Make simple example

### read-modify-write (RMW) operations
https://www.youtube.com/watch?v=TDzQixSl73M&t=1547s
http://www.cs.uni.edu/~diesburg/courses/cs3430_sp14/recitations/r06/week6.pdf
https://www.ibm.com/developerworks/library/l-linux-synchronization/index.html
https://www.informit.com/articles/article.aspx?p=414983
https://sysplay.in/blog/tag/kernel-synchronization-mechanisms/
https://kerneltweaks.wordpress.com/2015/03/20/quick-guide-for-choosing-correct-synchronization-mechanism-inside-linux-kernel/

https://www.kernel.org/doc/html/latest/locking/lockdep-design.html

https://lwn.net/Kernel/Index/#Mutex
https://lwn.net/Kernel/Index/#Atomic_spinlocks
https://lwn.net/Kernel/Index/#atomic_t
https://lwn.net/Kernel/Index/#Atomic_operations
https://lwn.net/Kernel/Index/#Race_conditions
https://lwn.net/Kernel/Index/#Read-copy-update
https://lwn.net/Kernel/Index/#Reader-writer_spinlocks
https://lwn.net/Kernel/Index/#Spinlocks



https://en.wikipedia.org/wiki/Test-and-set


Concept: race condition
Concept: writer starvation problem
Concept: mutual exclusion
https://en.wikipedia.org/wiki/Preemption_%28computing%29
`
- spinlocks
	- spin_lock_irqsave
	- spin_lock_bh
	- spin_trylock
- queued spinlocks
- Semaphores
	- binary semaphore;
	- normal semaphore.
	- Reader/Writer semaphore
	- seqlock
- mutex (binary semaphore)
`

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
	PLA - first 7 chapters
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Ch 2 -> 4 -> 5 -> 6 -> 7 -> ... -> 1 -> 3 



~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Kernel internal: Process Management and Scheduling
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Google images > Virtual Process Memory







~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
     Memory Management
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
https://docs.google.com/document/d/1YzpOoMJ1P1awhApxRGXXcqc77a2E3a3ZDoRp_Qyoguw/edit?usp=sharing
https://www.tldp.org/LDP/tlk/mm/memory.html

https://github.com/0xAX/linux-insides/blob/master/MM/README.md



~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
	VFS     
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
http://ods.com.ua/win/eng/unix/usail/peripherals/toc.html
https://www.star.bnl.gov/~liuzx/lki/lki-3.html
https://unix.stackexchange.com/q/4402/265591
https://www.poftut.com/file-system-block-super-block/
https://www3.cs.stonybrook.edu/~dongyoon/cse506-f19/lecture/lec20-vfs.pdf
https://www.kernel.org/doc/Documentation/filesystems/vfs.txt
https://ic.unicamp.br/~islene/2s2013-mo806/vfs/andre-zhen.pdf

https://docstore.mik.ua/manuals/hp-ux/en/B2355-60130/vfsmount.2.html
https://www.google.com/search?q=vfsmount+what+is

https://www.win.tue.nl/~aeb/linux/lk/lk-8.html#:~:text=A%20struct%20vfsmount%20represents%20a,is%20needed%20for%20I%2FO.
http://www.fieldses.org/~bfields/kernel/vfs.txt

ioctl: https://github.com/pokitoz/ioctl_driver
https://github.com/ZhangShurong/simple-filesystem
https://github.com/psankar/simplefs
https://www.google.com/search?q=linux+kernel+simple+fs


Google: linux kernel file system example github
https://unix.stackexchange.com/questions/4402/what-is-a-superblock-inode-dentry-and-a-file
Google images> `VFS layer for filesystem abstraction`
https://www.google.com/search?q=Understanding+UNIX+%2F+Linux+filesystem+Superblock
https://tldp.org/LDP/intro-linux/html/sect_03_01.html
https://www.youtube.com/watch?v=sLR17lUjTpc&t=249s
http://www.tldp.org/LDP/khg/HyperNews/get/fs/fs.html
http://www.tldp.org/LDP/tlk/tlk.html
https://www.slashroot.in/understanding-file-system-superblock-linux
