# PROCESS MANAGEMENT

PROGRAM ?  
Set of instructions stored in secondary memory

PROCESS ?  
A Program when loads in Main memory and a PCB is created, An active entity

STORAGE IN MEMORY ?  
- Stack : Temporary data - Parameters, return value...
- Heap : Dynamic allocated memory
- Data : Global ,Static data/variables
- Text : Code 

![alt text](image-15.png)

---
## PCB ?  
Also called process descriptor, Data structure used to store all the information about a process.  
PCB is identified by an integer process ID (PID)

![alt text](image-19.png)

1. Process ID (PID): Unique identifier for the process
2. Process state: New, Ready, Running, Waiting, Terminated
3. Program counter: Address of the next instruction to execute
4. CPU registers: Contents of CPU registers during process execution
5. CPU scheduling information: Priority, scheduling queue pointers
6. Memory management info: Base and limit registers, page tables
7. Accounting info: CPU usage, clock time, etc.
8. I/O status information: List of I/O devices allocated, open files

When the OS switches CPU from one process to another, it saves the current process’s state in its PCB and loads the next process’s PCB to resume its execution.