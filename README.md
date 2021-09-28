#### rtos 

### What is this ?  
Complete solutions to the [Embedded and Real-Time Systems / Real-Time Operating Systems](http://users.ece.utexas.edu/~gerstl/ee445m_f20/)  

It is a fully operational RTOS kernel that contains a priority scheduler, blocking semaphores, memory management, a file system, and more.  

It ended up winning the end-of-semester contest for most efficient kernel calculated by total idle time when a set test framework (series of tasks (freeRTOS term)) was scheduled and ran.  
This is likely because of the nature of the scheduler that is both stateless and light-weight.  

If you take a look inside, you might notice seemingly randomly commented out code. This is because the labs are at times, not backwards compatible. Some of the commented out code are threads of thought left incomplete, though :)  

The bulk of the kernel is in `os.c`.  
There is no getting started guide for this repository because it was uploaded in hindsight, and very IDE-specific settings such as setting up the debugger have long been forgotten by me :( .  