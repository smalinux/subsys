
Write and Submit your first Linux kernel Patch - by Greg
https://www.youtube.com/watch?v=LLBrBBImJt4

Linux Kernel in a Nutshell
http://www.kroah.com/lkn/

https://bootlin.com/docs/


If you are doing for final year project, my suggestion is develop some
userspace tools which is not available and useful one. Probably getting
info from kernel and display some info etc. Right now I am not getting any
idea, but developing a tool is good idea. U can identify.
http://lists.kernelnewbies.org/pipermail/kernelnewbies/2015-January/013316.html

linux perf
http://www.brendangregg.com/linuxperf.html

Send e-mails
https://www.tecmint.com/send-mail-from-command-line-using-mutt-command/

FirstKernelPatch
https://kernelnewbies.org/FirstKernelPatch

`Study & kill by subject Not by book or any thing else`

Block Device Driver Tutorial
https://github.com/pranjas/block_driverhttps://github.com/pranjas/block_driver

Linux kernel and driver development training
https://bootlin.com/training/kernel/

pwclient
http://www.openembedded.org/wiki/Patchwork
https://blog.linuxplumbersconf.org/2011/ocw/system/presentations/255/original/patchwork.pdf



Mutex:
http://lists.kernelnewbies.org/pipermail/kernelnewbies/2015-March/013620.html



"An Introduction to Programming with Threads" by Birrell
--


=====================================================================
#quote

use a single mutex to protect all the global state of an entire module.

The rule that you must use a mutex to protect every access to global variables.






================================================================
#log
USING A MUTEX: ACCESSING SHARED DATA
Unprotected data 						done!

================================================================
#bref
USING A MUTEX: ACCESSING SHARED DATA
The basic rule for using mutual exclusion is straightforward: in a multi-threaded program
all shared mutable data must be protected by associating it with some mutex, and you
must access the data only from a thread that is holding the associated mutex (i.e., from a
thread executing within a LOCK clause that locked the mutex).

Unprotected data
The simplest bug related to mutexes occurs when you fail to protect some mutable data
and then you access it without the benefits of synchronization. 

Invariants
When the data protected by a mutex is at all complicated, many programmers find it
convenient to think of the mutex as protecting the invariant of the associated data. `An
invariant is a boolean function of the data that is true whenever the mutex is not held.` So
any thread that locks the mutex knows that it starts out with the invariant true. Each
thread has the responsibility to restore the invariant before releasing the mutex. This
includes restoring the invariant before calling “Wait”, since that unlocks the mutex.
#Google img("mutex Invariants")

Cheating

#What is the difference between mutex, condition variable, semaphore and monitor ?
https://www.quora.com/What-is-the-difference-between-mutex-condition-variable-semaphore-and-monitor
https://github.com/angrave/SystemProgramming/wiki/Synchronization,-Part-5:-Condition-Variables
https://stackoverflow.com/questions/4742196/advantages-of-using-condition-variables-over-mutex
https://web.stanford.edu/~ouster/cgi-bin/cs140-spring14/lecture.php?topic=locks








----






































