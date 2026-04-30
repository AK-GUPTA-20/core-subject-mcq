# Top 150 Operating System (OS) Interview MCQs (With Answers)

> Format: Each question is multiple-choice (A–D). The correct option is marked as **Answer: X**.

---

## 1) OS Basics

### 1. What is the primary purpose of an operating system?
A. Compile programs  
B. Manage hardware and provide services to applications  
C. Design hardware circuits  
D. Encrypt all user data  
**Answer: B**

### 2. Which of the following is NOT a function of an OS?
A. Memory management  
B. Process scheduling  
C. Compiler optimization  
D. File management  
**Answer: C**

### 3. The OS component that directly interacts with hardware is:
A. Shell  
B. Kernel  
C. Application layer  
D. Editor  
**Answer: B**

### 4. A system call is:
A. A function call within a user program only  
B. A request to the OS kernel for a service  
C. A hardware interrupt only  
D. A BIOS routine  
**Answer: B**

### 5. The interface that allows users to communicate with the OS is called:
A. Loader  
B. Shell  
C. Cache  
D. Scheduler  
**Answer: B**

### 6. Which is a common OS design approach?
A. Monolithic kernel  
B. Microkernel  
C. Hybrid kernel  
D. All of the above  
**Answer: D**

### 7. In a monolithic kernel:
A. Most services run in user space  
B. Most OS services run in kernel space  
C. Kernel contains only IPC  
D. Kernel cannot load drivers  
**Answer: B**

### 8. In a microkernel architecture:
A. Device drivers typically run in kernel mode  
B. Most services run in user mode  
C. No IPC is used  
D. Scheduling is impossible  
**Answer: B**

### 9. The term "booting" refers to:
A. Formatting disk  
B. Starting the computer and loading the OS  
C. Installing applications  
D. Shutting down the system  
**Answer: B**

### 10. Which is an example of a real-time operating system (RTOS)?
A. MS-DOS  
B. VxWorks  
C. Windows XP  
D. Ubuntu Desktop  
**Answer: B**

### 11. Which OS is considered a time-sharing OS?
A. Batch OS  
B. Time-sharing OS  
C. Embedded OS only  
D. BIOS  
**Answer: B**

### 12. Multiprogramming improves:
A. CPU utilization  
B. Disk size  
C. Monitor resolution  
D. Network bandwidth  
**Answer: A**

### 13. A batch operating system primarily:
A. Interacts with users continuously  
B. Executes jobs in batches with minimal interaction  
C. Runs only one job at a time always  
D. Cannot use disks  
**Answer: B**

### 14. The OS module responsible for managing files is:
A. File system  
B. Scheduler  
C. Swapper  
D. IPC module  
**Answer: A**

### 15. Which of these is NOT an OS type?
A. Distributed OS  
B. Real-time OS  
C. Compiler OS  
D. Network OS  
**Answer: C**

---

## 2) Processes & Threads

### 16. A process is:
A. A program in secondary storage  
B. A program in execution  
C. A CPU register  
D. A device driver  
**Answer: B**

### 17. The Process Control Block (PCB) contains:
A. Only program code  
B. Process state, registers, scheduling info, etc.  
C. Only cache data  
D. Only file descriptors of other processes  
**Answer: B**

### 18. Which is NOT a valid process state?
A. New  
B. Ready  
C. Running  
D. Compiled  
**Answer: D**

### 19. Context switching is:
A. Running two processes simultaneously on one core without overhead  
B. Saving and restoring CPU state between processes/threads  
C. Only a disk operation  
D. Only a network operation  
**Answer: B**

### 20. A thread is:
A. A lightweight process unit of execution within a process  
B. A file system object  
C. A memory page  
D. A kernel module only  
**Answer: A**

### 21. Compared to processes, threads share:
A. Program counter  
B. Stack  
C. Address space and resources  
D. CPU registers  
**Answer: C**

### 22. Which is true about user-level threads?
A. Scheduled directly by the OS kernel always  
B. Managed by a user-space library  
C. Cannot be created  
D. Always faster than kernel threads in all cases  
**Answer: B**

### 23. Kernel-level threads are:
A. Invisible to the OS  
B. Managed and scheduled by the OS kernel  
C. Not preemptable  
D. Not runnable on multiprocessors  
**Answer: B**

### 24. The advantage of multithreading is:
A. Reduced concurrency  
B. Better responsiveness and resource sharing  
C. More disk fragmentation  
D. Larger binaries only  
**Answer: B**

### 25. A parent process creates a child process typically using:
A. fork()  
B. open()  
C. read()  
D. chmod()  
**Answer: A**

### 26. exec() does:
A. Creates a new process always  
B. Replaces current process image with a new program  
C. Terminates the kernel  
D. Flushes cache  
**Answer: B**

### 27. Zombie process is:
A. A process that never ran  
B. A terminated process whose exit status is not collected  
C. A process in ready queue  
D. A process blocked on I/O  
**Answer: B**

### 28. Orphan process is:
A. A process with no memory  
B. A process whose parent has terminated  
C. A process that cannot be killed  
D. A process in kernel mode forever  
**Answer: B**

### 29. Which is NOT a typical reason for process termination?
A. Normal exit  
B. Fatal error  
C. Killed by another process  
D. Increasing clock frequency  
**Answer: D**

### 30. In Linux, PID 1 is typically:
A. swapper  
B. init/systemd  
C. kthreadd always only  
D. bash  
**Answer: B**

---

## 3) CPU Scheduling

### 31. CPU scheduling decides:
A. Which page to evict  
B. Which process/thread runs next on CPU  
C. Which disk to format  
D. Which compiler to use  
**Answer: B**

### 32. Non-preemptive scheduling means:
A. A running process can be interrupted anytime by scheduler  
B. CPU is allocated until it terminates or blocks  
C. Only interrupts are disabled  
D. It never uses ready queue  
**Answer: B**

### 33. Preemptive scheduling means:
A. Running process can be interrupted and moved back to ready state  
B. No context switches occur  
C. CPU runs only one job in whole system lifetime  
D. It is same as FCFS always  
**Answer: A**

### 34. FCFS scheduling can suffer from:
A. Starvation of short jobs never  
B. Convoy effect  
C. Deadlock always  
D. No waiting time  
**Answer: B**

### 35. SJF scheduling minimizes:
A. Average waiting time (under certain assumptions)  
B. Context switching always  
C. Disk usage  
D. Network latency always  
**Answer: A**

### 36. The major issue with SJF is:
A. It needs prediction of burst time  
B. It never runs  
C. It causes deadlock  
D. It requires paging  
**Answer: A**

### 37. Round Robin scheduling is best suited for:
A. Batch systems only  
B. Time-sharing systems  
C. Disk scheduling  
D. Deadlock handling  
**Answer: B**

### 38. In Round Robin, the time quantum too small leads to:
A. Very low context switching  
B. High context switching overhead  
C. No fairness  
D. Deadlock  
**Answer: B**

### 39. Priority scheduling can cause:
A. No overhead  
B. Starvation of low-priority processes  
C. No waiting time  
D. Only CPU-bound jobs  
**Answer: B**

### 40. Aging is used to:
A. Increase disk rotation speed  
B. Prevent starvation by gradually increasing priority  
C. Increase fragmentation  
D. Disable interrupts  
**Answer: B**

### 41. Multilevel queue scheduling:
A. Uses one queue only  
B. Has multiple queues with different priorities/policies  
C. Is same as paging  
D. Works only for RTOS  
**Answer: B**

### 42. Turnaround time is:
A. Time in ready queue only  
B. Completion time - arrival time  
C. Burst time only  
D. Waiting time - burst time  
**Answer: B**

### 43. Waiting time is:
A. Total time spent in ready queue  
B. Time spent executing on CPU  
C. Time spent in I/O only  
D. Arrival time - completion time  
**Answer: A**

### 44. Response time is:
A. Time from submission to completion  
B. Time from submission to first response/first CPU allocation  
C. Total CPU time used  
D. Total I/O time  
**Answer: B**

### 45. Throughput refers to:
A. Number of processes completed per unit time  
B. CPU temperature  
C. RAM size  
D. Network packets only  
**Answer: A**

---

## 4) Synchronization & Concurrency

### 46. Critical section problem arises due to:
A. Multiple processes accessing shared resources concurrently  
B. Only disk fragmentation  
C. Only paging  
D. Only device driver issues  
**Answer: A**

### 47. Mutual exclusion ensures:
A. Multiple threads can enter critical section at same time  
B. Only one thread enters critical section at a time  
C. CPU never idles  
D. No deadlocks ever  
**Answer: B**

### 48. Race condition occurs when:
A. Result depends on timing/interleaving of threads  
B. Only one thread runs  
C. CPU frequency changes  
D. Disk becomes full  
**Answer: A**

### 49. Semaphore is:
A. A scheduling algorithm  
B. A synchronization primitive (counter + wait/signal)  
C. A file system  
D. A page replacement policy  
**Answer: B**

### 50. Binary semaphore is also known as:
A. Mutex  
B. Monitor  
C. Swap space  
D. Page table  
**Answer: A**

### 51. Spinlock is:
A. A lock where thread sleeps immediately  
B. A lock where thread busy-waits  
C. A disk scheduling method  
D. A memory allocation strategy  
**Answer: B**

### 52. Busy waiting wastes:
A. CPU cycles  
B. Disk space  
C. File descriptors  
D. Network ports  
**Answer: A**

### 53. A monitor provides:
A. Only hardware protection  
B. High-level synchronization with mutual exclusion + condition variables  
C. Only paging  
D. Only process creation  
**Answer: B**

### 54. Condition variables are used for:
A. File encryption  
B. Thread communication (wait/signal on conditions)  
C. Disk formatting  
D. Cache eviction  
**Answer: B**

### 55. Deadlock requires:
A. Only mutual exclusion  
B. All four Coffman conditions simultaneously  
C. Only preemption  
D. Only paging  
**Answer: B**

### 56. Which is NOT a Coffman condition?
A. Mutual exclusion  
B. Hold and wait  
C. Circular wait  
D. Cache locality  
**Answer: D**

### 57. Livelock is:
A. Processes are blocked forever  
B. Processes keep changing state but no progress happens  
C. A memory leak  
D. Disk failure  
**Answer: B**

### 58. Starvation means:
A. Process gets CPU too often  
B. Process never gets required resources for a long time  
C. RAM always full  
D. Files are corrupted  
**Answer: B**

### 59. Reentrant code is:
A. Code that cannot be interrupted  
B. Code that can be safely executed concurrently by multiple threads  
C. Code that requires global variables always  
D. Code that runs only in kernel  
**Answer: B**

### 60. Atomic operation means:
A. Operation that can be interrupted halfway  
B. Indivisible operation  
C. Disk-only operation  
D. Network-only operation  
**Answer: B**

---

## 5) Deadlocks

### 61. Deadlock is:
A. CPU overheating  
B. A set of processes waiting indefinitely for resources held by each other  
C. A file permission issue  
D. A cache miss  
**Answer: B**

### 62. Deadlock prevention works by:
A. Ignoring deadlocks  
B. Violating at least one Coffman condition  
C. Increasing CPU quantum  
D. Increasing disk size  
**Answer: B**

### 63. Deadlock avoidance is commonly implemented using:
A. Banker’s algorithm  
B. FCFS scheduling  
C. LRU paging  
D. RAID  
**Answer: A**

### 64. Safe state means:
A. No process can run  
B. There exists a safe sequence to finish all processes  
C. Memory is full  
D. Disk is idle  
**Answer: B**

### 65. Deadlock detection typically uses:
A. Resource allocation graph / wait-for graph  
B. DNS cache  
C. Page table  
D. Heap  
**Answer: A**

### 66. Recovery from deadlock can be done by:
A. Terminating processes or preempting resources  
B. Increasing monitor size  
C. Increasing CPU speed only  
D. Increasing font size  
**Answer: A**

### 67. Circular wait implies:
A. Deadlock always in single instance of resources? (not always)  
B. A necessary condition for deadlock  
C. Deadlock can never happen  
D. Starvation can’t happen  
**Answer: B**

### 68. If resources have multiple instances, deadlock detection uses:
A. Simple cycle detection only  
B. Detection algorithm similar to Banker’s (matrix-based)  
C. Only FCFS  
D. Only Round Robin  
**Answer: B**

### 69. Hold and wait means:
A. Process holds no resources  
B. Process holds at least one resource and waits for others  
C. Process releases all before requesting  
D. Process never requests resources  
**Answer: B**

### 70. Preemption in deadlock context means:
A. CPU preemption only  
B. Forcibly taking a resource from a process  
C. Killing the kernel  
D. Disk defragmentation  
**Answer: B**

---

## 6) Memory Management

### 71. Logical address is generated by:
A. Disk controller  
B. CPU  
C. Printer  
D. BIOS only  
**Answer: B**

### 72. Physical address refers to:
A. Address in CPU registers  
B. Actual address in main memory  
C. Address in source code  
D. Address in cache line tag only  
**Answer: B**

### 73. The hardware that maps logical to physical addresses is:
A. ALU  
B. MMU (Memory Management Unit)  
C. DMA controller  
D. Clock  
**Answer: B**

### 74. Swapping refers to:
A. Switching CPU cores  
B. Moving processes between main memory and disk  
C. Changing file names  
D. Replacing cache only  
**Answer: B**

### 75. Fragmentation can be:
A. Only internal  
B. Only external  
C. Both internal and external  
D. Neither  
**Answer: C**

### 76. Internal fragmentation occurs when:
A. Free memory is split into many small pieces  
B. Allocated memory block has unused space inside it  
C. Disk is fragmented  
D. Page table is missing  
**Answer: B**

### 77. External fragmentation occurs when:
A. Unused memory exists but not contiguous enough to allocate  
B. Page size is too small  
C. TLB is too large  
D. Cache is too small  
**Answer: A**

### 78. Compaction is used to reduce:
A. Internal fragmentation  
B. External fragmentation  
C. Page faults  
D. Deadlocks  
**Answer: B**

### 79. Paging eliminates:
A. Internal fragmentation completely  
B. External fragmentation  
C. Need for page tables  
D. Need for protection  
**Answer: B**

### 80. Paging may cause:
A. External fragmentation  
B. Internal fragmentation  
C. No overhead  
D. No address translation  
**Answer: B**

### 81. A page table stores:
A. Mapping from logical pages to physical frames  
B. Only file permissions  
C. Only CPU scheduling order  
D. Only disk blocks always  
**Answer: A**

### 82. TLB is:
A. Translation Lookaside Buffer (cache of page table entries)  
B. Time limit buffer  
C. Thread local block  
D. Transfer link bridge  
**Answer: A**

### 83. If TLB hit ratio increases, effective memory access time:
A. Increases  
B. Decreases  
C. Unchanged always  
D. Becomes infinite  
**Answer: B**

### 84. Segmentation divides memory into:
A. Fixed-size blocks  
B. Variable-size logical segments  
C. Only disk sectors  
D. Only cache lines  
**Answer: B**

### 85. In segmentation, a logical address consists of:
A. (page, offset)  
B. (segment number, offset)  
C. (frame, offset)  
D. (block, inode)  
**Answer: B**

### 86. Virtual memory allows:
A. Running programs larger than physical RAM  
B. Eliminating CPU  
C. Eliminating disks  
D. Eliminating scheduling  
**Answer: A**

### 87. Demand paging loads pages:
A. All at program start  
B. Only when referenced  
C. Never  
D. Only on timer interrupt  
**Answer: B**

### 88. A page fault occurs when:
A. TLB hit happens  
B. Required page is not in physical memory  
C. CPU overheats  
D. File permission denied  
**Answer: B**

### 89. Working set model is used to:
A. Replace CPU scheduling  
B. Control degree of multiprogramming and reduce thrashing  
C. Increase fragmentation  
D. Disable paging  
**Answer: B**

### 90. Thrashing is:
A. Excessive paging leading to low CPU utilization  
B. CPU running at 100% always efficiently  
C. Disk formatting  
D. File copying  
**Answer: A**

---

## 7) Page Replacement

### 91. Page replacement is needed when:
A. CPU is idle  
B. A page fault occurs and no free frame is available  
C. Disk is full  
D. Network is down  
**Answer: B**

### 92. FIFO page replacement may suffer from:
A. Belady’s anomaly  
B. No page faults  
C. No overhead  
D. Deadlock  
**Answer: A**

### 93. Optimal page replacement:
A. Is implementable easily in real systems  
B. Replaces page that will not be used for longest time in future  
C. Is same as FIFO  
D. Always worst  
**Answer: B**

### 94. LRU replaces:
A. Most recently used page  
B. Least recently used page  
C. Random page always  
D. Largest page  
**Answer: B**

### 95. LRU approximation can be done using:
A. Reference bits / clock algorithm  
B. Banker’s algorithm  
C. FCFS scheduling  
D. RAID 0  
**Answer: A**

### 96. The Clock algorithm is an approximation of:
A. FIFO  
B. LRU  
C. Optimal  
D. SJF  
**Answer: B**

### 97. Page replacement algorithm selection impacts:
A. Page fault rate  
B. CPU instruction set  
C. Ethernet speed  
D. Keyboard layout  
**Answer: A**

### 98. Belady’s anomaly means:
A. More frames always reduce page faults  
B. Increasing frames can increase page faults (in FIFO)  
C. LRU has anomaly  
D. Optimal has anomaly  
**Answer: B**

### 99. Stack algorithms have the property that:
A. More frames can increase faults  
B. More frames cannot increase faults  
C. They ignore locality  
D. They require segmentation only  
**Answer: B**

### 100. Which is a stack algorithm?
A. FIFO  
B. LRU  
C. Random  
D. Second chance only  
**Answer: B**

---

## 8) File Systems

### 101. A file is:
A. A named collection of related information on secondary storage  
B. A CPU register  
C. A semaphore  
D. A page frame  
**Answer: A**

### 102. File attributes include:
A. Name, type, size, permissions, timestamps  
B. CPU burst time  
C. TLB entries  
D. Scheduler quantum  
**Answer: A**

### 103. The structure that stores file metadata in Unix-like systems is:
A. inode  
B. PCB  
C. TCB  
D. TLB  
**Answer: A**

### 104. File access methods include:
A. Sequential, direct (random), indexed  
B. Only sequential  
C. Only direct  
D. Only indexed  
**Answer: A**

### 105. Directory structure provides:
A. CPU scheduling  
B. Organization of files and name-to-file mapping  
C. Memory protection  
D. Paging  
**Answer: B**

### 106. Hard link in Unix:
A. Points to inode (same file data)  
B. Is a copy of file content always  
C. Cannot exist  
D. Always crosses file systems  
**Answer: A**

### 107. Symbolic link:
A. Is another name for inode pointer only  
B. Stores path to target file  
C. Is same as hard link always  
D. Works only for directories  
**Answer: B**

### 108. Free space management can be done using:
A. Bitmaps  
B. Linked list of free blocks  
C. Grouping/counting  
D. All of the above  
**Answer: D**

### 109. Contiguous allocation suffers from:
A. External fragmentation  
B. No random access  
C. Huge overhead always  
D. No need for free space management  
**Answer: A**

### 110. Linked allocation primarily suffers from:
A. External fragmentation  
B. Poor random access (needs traversal)  
C. Internal fragmentation  
D. No overhead  
**Answer: B**

### 111. Indexed allocation uses:
A. File Allocation Table only always  
B. An index block to point to file blocks  
C. Only contiguous blocks  
D. Only linked lists  
**Answer: B**

### 112. Journaling file systems help with:
A. Faster CPU scheduling  
B. Crash consistency / recovery  
C. Increasing RAM  
D. Eliminating permissions  
**Answer: B**

### 113. Buffer cache is used to:
A. Store frequently used disk blocks in memory  
B. Store CPU registers  
C. Store page tables only  
D. Store network packets only  
**Answer: A**

### 114. File permission bits in Unix define:
A. Read/write/execute for owner/group/others  
B. CPU speed  
C. Disk rotation speed  
D. Network routing  
**Answer: A**

### 115. Mounting a file system means:
A. Encrypting it  
B. Making it accessible at a directory (mount point)  
C. Compressing it  
D. Defragmenting it  
**Answer: B**

---

## 9) I/O Systems & Disk Scheduling

### 116. Interrupt-driven I/O means:
A. CPU polls device continuously  
B. Device interrupts CPU when ready  
C. CPU never interacts with device  
D. Only DMA can be used  
**Answer: B**

### 117. DMA stands for:
A. Direct Memory Access  
B. Dynamic Memory Allocation  
C. Disk Mode Access  
D. Data Message API  
**Answer: A**

### 118. DMA helps by:
A. Increasing CPU workload  
B. Allowing device to transfer data to memory without CPU involvement for each byte  
C. Eliminating memory  
D. Eliminating disk  
**Answer: B**

### 119. Device driver is:
A. Hardware circuit  
B. Software that controls device and provides interface to OS  
C. A user app always  
D. A CPU instruction  
**Answer: B**

### 120. Disk scheduling is needed to:
A. Manage CPU registers  
B. Minimize disk head movement and access time  
C. Increase RAM  
D. Avoid deadlocks only  
**Answer: B**

### 121. FCFS disk scheduling:
A. Gives minimal seek time always  
B. Serves requests in arrival order  
C. Is same as SSTF  
D. Requires sorting  
**Answer: B**

### 122. SSTF disk scheduling selects:
A. Farthest request first  
B. Closest request (shortest seek time first)  
C. Requests in circular order only  
D. Random request  
**Answer: B**

### 123. SSTF may cause:
A. No starvation  
B. Starvation for far requests  
C. Guaranteed fairness  
D. Deadlock  
**Answer: B**

### 124. SCAN (elevator) algorithm:
A. Moves head in one direction servicing requests, then reverses  
B. Randomly jumps  
C. Always stays at middle  
D. Serves only nearest request  
**Answer: A**

### 125. C-SCAN differs from SCAN because:
A. It reverses direction every request  
B. It services in one direction only and jumps back to start without servicing on return  
C. It never services requests  
D. It is same as FCFS  
**Answer: B**

### 126. Disk access time includes:
A. Seek time + rotational latency + transfer time  
B. Only transfer time  
C. Only seek time  
D. Only latency  
**Answer: A**

### 127. Spooling is:
A. Storing I/O data temporarily on disk for later processing (e.g., printing)  
B. A CPU scheduling algorithm  
C. Memory allocation method  
D. Deadlock recovery method  
**Answer: A**

### 128. Caching in I/O improves:
A. CPU overheating  
B. Performance by reusing recently accessed data  
C. Disk wear always  
D. Deadlocks  
**Answer: B**

### 129. Polling is:
A. Device interrupts CPU  
B. CPU repeatedly checks device status  
C. DMA operation  
D. Page replacement  
**Answer: B**

### 130. Memory-mapped I/O means:
A. Device registers mapped into memory address space  
B. Only disk blocks mapped  
C. Only files mapped  
D. CPU cannot access devices  
**Answer: A**

---

## 10) Protection, Security & Misc

### 131. Kernel mode vs user mode distinction is for:
A. Better graphics  
B. Protection and controlled access to hardware  
C. Faster typing  
D. Larger disks  
**Answer: B**

### 132. A trap is:
A. A hardware fault only  
B. A software-generated interrupt (exception)  
C. A disk scheduling event  
D. A file operation only  
**Answer: B**

### 133. Privileged instructions can be executed in:
A. User mode only  
B. Kernel mode only  
C. Both equally  
D. Only BIOS mode  
**Answer: B**

### 134. Access control list (ACL) specifies:
A. CPU priorities  
B. Which users/groups have what permissions on an object  
C. Page replacement order  
D. Disk geometry  
**Answer: B**

### 135. Authentication is:
A. Determining what you can do  
B. Verifying who you are  
C. Encrypting files only  
D. Scheduling processes  
**Answer: B**

### 136. Authorization is:
A. Verifying identity  
B. Determining allowed actions/permissions  
C. Disk scheduling  
D. Page replacement  
**Answer: B**

### 137. Principle of least privilege means:
A. Give maximum access for convenience  
B. Give only minimum permissions needed  
C. Remove all permissions  
D. Run everything as admin  
**Answer: B**

### 138. A protection domain defines:
A. Set of access rights for a process/user  
B. Disk blocks  
C. CPU burst  
D. TLB size  
**Answer: A**

### 139. Capability list is:
A. List of files in directory  
B. Tokens/keys that grant rights to objects  
C. List of CPU instructions  
D. List of network routes  
**Answer: B**

### 140. System call executes typically via:
A. Direct jump to RAM only with no mode switch  
B. Trap instruction causing switch to kernel mode  
C. Reboot  
D. Disk interrupt only  
**Answer: B**

### 141. POSIX stands for:
A. Portable Operating System Interface  
B. Process OS Index  
C. Page-Oriented System Interface  
D. Protected OS Integration eXtension  
**Answer: A**

### 142. A daemon is:
A. A kernel panic  
B. A background service process (Unix-like)  
C. A page fault handler only  
D. A file system type  
**Answer: B**

### 143. System throughput can degrade due to:
A. Thrashing  
B. Larger TLB  
C. Better locality  
D. More CPU cores  
**Answer: A**

### 144. Copy-on-write (COW) is used to:
A. Copy files always  
B. Delay copying memory pages until modification  
C. Increase disk usage  
D. Prevent paging  
**Answer: B**

### 145. A pipe is:
A. Disk block  
B. IPC mechanism for unidirectional data flow  
C. Scheduler queue  
D. Memory page  
**Answer: B**

### 146. Message passing IPC can be:
A. Only shared memory  
B. Direct or indirect (mailboxes/ports)  
C. Only signals  
D. Only semaphores  
**Answer: B**

### 147. Shared memory IPC requires:
A. No synchronization  
B. Synchronization primitives (semaphores/mutex) to avoid races  
C. No mapping  
D. Disk scheduling  
**Answer: B**

### 148. In producer-consumer problem, the bounded buffer requires:
A. Only one semaphore  
B. Synchronization to ensure mutual exclusion and buffer state tracking  
C. No locks  
D. Only paging  
**Answer: B**

### 149. A system is scalable when:
A. Performance decreases as resources increase  
B. It can handle growth (users/CPU/nodes) with acceptable performance  
C. It cannot add new resources  
D. It requires reboot for every process  
**Answer: B**

### 150. SMP stands for:
A. Single Memory Processor  
B. Symmetric Multiprocessing  
C. System Memory Paging  
D. Sequential Multi-Processing  
**Answer: B**

---

## How to use this file
- Practice by hiding the answers first.
- Track weak areas by section (Scheduling, Deadlock, Memory, File Systems, I/O).
