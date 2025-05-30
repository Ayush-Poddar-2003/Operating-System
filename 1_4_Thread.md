# Thread

A thread is the smallest unit of CPU execution within a process. A process can have one or more threads.

---
**Types of Threads:**
1. User-level threads: Managed by user-level libraries, the OS kernel is unaware of them.
2. Kernel-level threads: Managed directly by the OS kernel.

---
Components shared by threads in the same process:  
Code section, Data section (variables), Open files, Heap memory

Components unique to each thread:  
Program counter (PC), Registers, Stack (for function calls and local variables)

---
Threads are called lightweight processes because they share the same memory space and resources of their parent process, reducing the overhead involved in switching between them.

Threads support parallel and concurrent execution through multithreading on multicore systems by allowing multiple threads to run simultaneously on different cores, achieving true parallelism, or by allowing multiple threads to share the same core, achieving concurrency.