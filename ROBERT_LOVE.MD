> Applying Patches To The Linux Kernel
https://www.kernel.org/doc/html/latest/process/applying-patches.html


`Sounds easy`
https://www.kernel.org/doc/html/latest/admin-guide/index.html
https://www.kernel.org/doc/html/latest/kbuild/index.html
https://www.kernel.org/doc/html/latest/userspace-api/index.html
https://www.kernel.org/doc/html/latest/process/index.html
https://www.kernel.org/doc/html/latest/dev-tools/index.html
https://www.kernel.org/doc/html/latest/doc-guide/index.html
https://www.kernel.org/doc/html/latest/kernel-hacking/index.html
https://www.kernel.org/doc/html/latest/trace/index.html
https://www.kernel.org/doc/html/latest/maintainer/index.html

`Use Git for Linux Kernel Dev`
https://landley.net/writing/git-bisect-howto.html
https://opensourceforu.com/2014/09/use-git-for-linux-kernel-development/
https://github.com/0xAX/linux-insides/blob/master/Misc/linux-misc-1.md
https://opensourceforu.com/2011/05/linux-kernel-development-using-git/
https://github.com/gregkh/kernel-development
https://kernelnewbies.org/KernelBuild
https://stackoverflow.com/q/1856241/5688267
**Google:use git for linux kernel development**


`Submitting patches`
https://www.kernel.org/doc/html/v4.10/process/submitting-patches.html


`Deep but i like it`
https://www.kernel.org/doc/html/latest/driver-api/index.html
https://www.kernel.org/doc/html/latest/core-api/index.html
https://www.kernel.org/doc/html/latest/hwmon/index.html
https://www.kernel.org/doc/html/latest/leds/index.html



`Subsystem`
ACPI subsystem
I2C/SMBus Subsystem

`String manipulation`
lib/string.c  <linux/string.h>


struct task_struct <linux/sched.h>
<linux/threads.h>
for_each_process <linux/sched/signal.h>



Page: 25 ``The task_struct structure is allocated via the slab allocator``




#Log
- reread carefolly from P: 32 to P: 40



--------------------------------------------------------------------------------
`Chapter 4`
Scheduling algorithms:
	priority-based scheduling
	Round-robin scheduling
	CFS scheduler

Process Priority
	- nice value (-20 : 19)
	- real-time priority (0 : 99)

kernel/sched.c
kernel/sched_fair.c
--------------------------------------------------------------------------------
`Chapter 6`
rbtree
	- self-balancing binary search tree
--------------------------------------------------------------------------------