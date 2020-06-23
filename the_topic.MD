

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




~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
     
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~



~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
     
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

