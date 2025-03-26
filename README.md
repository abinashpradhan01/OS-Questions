# OS-Questions
---

## **5 Long-Answer Questions (10 Marks Each)**  

### **1. Explain the functions and services of an operating system in detail.**  
#### **Answer:**  
An **Operating System (OS)** is system software that manages computer hardware and software resources and provides services for computer programs.  
#### **Functions of an OS:**  
1. **Process Management** – Schedules and manages multiple processes.  
2. **Memory Management** – Allocates and deallocates memory.  
3. **File System Management** – Manages files and directories.  
4. **Device Management** – Controls input/output devices.  
5. **Security & Protection** – Ensures user authentication and data protection.  
6. **User Interface** – Provides command-line or GUI interaction.  

#### **Operating System Services:**  
1. **Program Execution** – Loads and executes programs.  
2. **I/O Operations** – Manages input and output devices.  
3. **File System Manipulation** – Handles file creation, deletion, and access.  
4. **Communication** – Enables inter-process communication.  
5. **Error Handling** – Detects and handles system failures.  
6. **Resource Allocation** – Assigns CPU, memory, and devices to processes.  

---

### **2. What are system calls? Explain their types with examples.**  
#### **Answer:**  
**System Calls** provide an interface between a program and the OS. Programs use system calls to request OS services.  

#### **Types of System Calls:**  
1. **Process Control:**  
   - Example: `fork()`, `exec()`, `exit()`  
   - Used for creating and terminating processes.  
2. **File Management:**  
   - Example: `open()`, `read()`, `write()`, `close()`  
   - Handles file operations.  
3. **Device Management:**  
   - Example: `ioctl()`, `read()`, `write()`  
   - Interacts with hardware devices.  
4. **Information Maintenance:**  
   - Example: `getpid()`, `getuid()`  
   - Retrieves system information.  
5. **Communication:**  
   - Example: `send()`, `recv()`, `socket()`  
   - Used for inter-process communication.  

---

### **3. Explain the different types of Operating System structures.**  
#### **Answer:**  
OS structure defines how various components of the OS interact.  

1. **Monolithic Structure:**  
   - All OS functionalities exist in a single large kernel.  
   - Example: **MS-DOS, Linux Kernel**  
2. **Layered Structure:**  
   - OS is divided into layers, where each layer performs specific functions.  
   - Example: **THE OS (Technische Hogeschool Eindhoven OS)**  
3. **Microkernel Structure:**  
   - Only essential functions (like process and memory management) are in the kernel; other services run in user mode.  
   - Example: **Minix, QNX**  
4. **Modular Structure:**  
   - Uses dynamically loadable kernel modules.  
   - Example: **Modern Linux Kernels**  
5. **Hybrid Structure:**  
   - Combination of monolithic and microkernel structures.  
   - Example: **Windows, macOS**  

---

### **4. What are system programs? Explain different types with examples.**  
#### **Answer:**  
**System Programs** are software utilities that provide functionalities beyond an OS but support its operation.  

**Types of System Programs:**  
1. **File Management Programs** – Handle file creation, deletion, and access.  
   - Example: `cp`, `mv`, `rm` (Linux commands)  
2. **Status Information Programs** – Provide system information.  
   - Example: `top`, `ps`, `uptime`  
3. **Programming Language Support Programs** – Provide compilers and assemblers.  
   - Example: GCC Compiler  
4. **Communication Programs** – Facilitate communication between users.  
   - Example: `mail`, `chat`, `ssh`  
5. **Application Program Interface (API) Programs** – Help software interact with the OS.  
   - Example: Windows API, POSIX API  

---

### **5. Discuss Operating System Design and Implementation considerations.**  
#### **Answer:**  
**OS Design Goals:**  
1. **Efficiency** – Optimize CPU, memory, and I/O usage.  
2. **Security** – Protect data and prevent unauthorized access.  
3. **Flexibility** – Adapt to new hardware and software.  
4. **Scalability** – Support multiple users and large workloads.  
5. **Reliability** – Ensure system stability and crash recovery.  

**Implementation Considerations:**  
1. **Programming Language Choice:** C, C++, Rust  
2. **Kernel Mode vs. User Mode:** Separation of privilege levels.  
3. **Portability:** Ability to run on different hardware architectures.  
4. **Process Synchronization:** Using locks and semaphores.  

---

## **10 Medium-Answer Questions (3 Marks Each)**  

1. **What is an operating system?**  
   - An OS is system software that manages hardware and software resources and provides services to programs.  

2. **List different types of OS.**  
   - Batch OS, Time-Sharing OS, Distributed OS, Real-Time OS, Multi-User OS, Embedded OS.  

3. **Define system calls.**  
   - System calls are functions used by user programs to request services from the OS.  

4. **What is the purpose of an API in an OS?**  
   - API (Application Programming Interface) allows applications to interact with the OS.  

5. **List different types of system structures.**  
   - Monolithic, Layered, Microkernel, Modular, Hybrid.  

6. **What are system programs?**  
   - System programs provide basic functionalities for system maintenance and user interaction.  

7. **What is a kernel?**  
   - The kernel is the core of an OS that manages system resources and hardware.  

8. **What is a microkernel OS?**  
   - A microkernel OS has minimal core functions, with additional services running in user space.  

9. **Explain OS portability.**  
   - Portability allows an OS to run on different hardware architectures with minimal changes.  

10. **What are the main components of an OS?**  
   - Kernel, File System, Device Drivers, User Interface, Process Management, Memory Management.  

---

## **15 Short-Answer Questions (1 Mark Each)**  

1. **What is the main function of an OS?**  
   - Resource management and user interaction.  

2. **What is the difference between firmware and an OS?**  
   - Firmware is pre-installed low-level software; OS is general-purpose system software.  

3. **Give an example of a multi-user OS.**  
   - UNIX, Windows Server.  

4. **What is a batch operating system?**  
   - An OS that executes a batch of jobs without user interaction.  

5. **Define process.**  
   - A program in execution.  

6. **What is the function of system calls?**  
   - Provide an interface between user programs and the OS.  

7. **Give an example of a system call.**  
   - `fork()` – Creates a new process.  

8. **What is system software?**  
   - Software that manages hardware and provides a platform for applications.  

9. **Define user mode and kernel mode.**  
   - User mode: Limited access; Kernel mode: Full system control.  

10. **What is an interrupt?**  
   - A signal that pauses CPU execution for immediate attention.  

11. **Name one advantage of a microkernel.**  
   - Increased stability and security.  

12. **What is an API?**  
   - A set of functions enabling application-OS interaction.  

13. **What does the term "open-source OS" mean?**  
   - An OS whose source code is publicly available (e.g., Linux).  

14. **What is a shell in an OS?**  
   - A command-line interface for user interaction.  

15. **What is the purpose of a device driver?**  
   - Facilitates communication between hardware and the OS.  

---

## **5 Long-Answer Questions (10 Marks Each)**  

### **1. Explain the concept of a process and describe the different states of a process.**  
#### **Answer:**  
A **process** is a program in execution. It includes the program code, stack, heap, and data sections.  

#### **Process States:**  
1. **New:** The process is created.  
2. **Ready:** The process is waiting to be assigned to the CPU.  
3. **Running:** The process is currently executing.  
4. **Waiting (Blocked):** The process is waiting for I/O completion.  
5. **Terminated:** The process has finished execution.  

The **Process Control Block (PCB)** stores process details like process ID, program counter, registers, scheduling information, and memory limits.  

---

### **2. What are the different types of process scheduling? Explain various CPU scheduling algorithms.**  
#### **Answer:**  
**Process Scheduling Types:**  
1. **Long-Term Scheduling:** Decides which processes to admit to the system.  
2. **Short-Term Scheduling (CPU Scheduling):** Decides which process gets the CPU next.  
3. **Medium-Term Scheduling:** Temporarily removes processes from memory (swapping).  

#### **CPU Scheduling Algorithms:**  
1. **First-Come, First-Served (FCFS):**  
   - Non-preemptive, executes processes in order of arrival.  
   - Example: If P1 (5ms), P2 (3ms), P3 (8ms) arrive in this order, they execute sequentially.  
2. **Shortest Job Next (SJN):**  
   - Non-preemptive, executes shortest process first.  
   - Example: P1 (5ms), P2 (2ms), P3 (8ms) → Order: P2 → P1 → P3.  
3. **Round Robin (RR):**  
   - Preemptive, each process gets a fixed time quantum.  
   - Example: If quantum = 2ms and P1 (5ms), P2 (3ms), P3 (8ms), they execute in cyclic order.  
4. **Priority Scheduling:**  
   - Assigns priority values, highest priority executes first.  
   - Example: If P1 = priority 3, P2 = priority 1, P3 = priority 2 → Execution order: P1 → P3 → P2.  
5. **Shortest Remaining Time First (SRTF):**  
   - Preemptive version of SJN, runs shortest remaining process first.  
6. **Multilevel Queue Scheduling:**  
   - Different queues for different priority levels (foreground, background tasks).  

---

### **3. What is Inter-Process Communication (IPC)? Explain different IPC mechanisms.**  
#### **Answer:**  
IPC allows processes to communicate and synchronize their actions.  

#### **IPC Mechanisms:**  
1. **Shared Memory:**  
   - Processes share a memory space to exchange information.  
   - Fast but requires synchronization mechanisms like semaphores.  
2. **Message Passing:**  
   - Processes send and receive messages using OS services.  
   - Slower but more secure than shared memory.  
3. **Pipes:**  
   - Unidirectional communication channel between processes.  
4. **Sockets:**  
   - Used for network communication between processes on different machines.  
5. **Signals:**  
   - Used to notify processes about events like termination or errors.  

---

### **4. Explain the concepts of threads and processes. What are the advantages of multithreading?**  
#### **Answer:**  
A **process** is an independent execution unit with its own memory space, while a **thread** is a lightweight process that shares memory with other threads in the same process.  

#### **Types of Threads:**  
1. **User-Level Threads:** Managed by the application, not the OS.  
2. **Kernel-Level Threads:** Managed directly by the OS.  

#### **Advantages of Multithreading:**  
1. **Improved Responsiveness:** UI remains active while tasks execute in the background.  
2. **Resource Sharing:** Threads share memory and reduce overhead.  
3. **Parallel Execution:** Speeds up CPU-bound tasks.  
4. **Efficient Resource Utilization:** Reduces context-switching overhead.  

---

### **5. What is a deadlock? Explain deadlock detection, prevention, and avoidance techniques.**  
#### **Answer:**  
A **deadlock** occurs when two or more processes wait indefinitely for resources held by each other.  

#### **Deadlock Detection:**  
- The OS checks for cycles in the **resource allocation graph**.  

#### **Deadlock Prevention (Avoiding at the design stage):**  
1. **Mutual Exclusion:** Make resources sharable where possible.  
2. **Hold and Wait:** Require processes to request all resources at once.  
3. **No Preemption:** Allow resources to be forcibly taken from a process.  
4. **Circular Wait:** Impose an ordering on resource requests.  

#### **Deadlock Avoidance:**  
- Uses algorithms like **Banker’s Algorithm** to allocate resources dynamically.  

---

## **10 Medium-Answer Questions (3 Marks Each)**  

1. **What are the main differences between a process and a thread?**  
   - A process has separate memory, while threads share memory within a process.  

2. **Define process scheduling.**  
   - The OS decides which process gets the CPU next based on scheduling algorithms.  

3. **What is the difference between preemptive and non-preemptive scheduling?**  
   - Preemptive allows CPU switching before a task completes; non-preemptive does not.  

4. **What is the purpose of a Process Control Block (PCB)?**  
   - Stores process information like process ID, registers, program counter, and status.  

5. **What are the main IPC methods?**  
   - Shared memory, message passing, pipes, sockets, signals.  

6. **What are the four necessary conditions for deadlock?**  
   - Mutual Exclusion, Hold and Wait, No Preemption, Circular Wait.  

7. **What is the function of a scheduler?**  
   - Manages process execution order based on scheduling policies.  

8. **Explain the term ‘context switch’.**  
   - The CPU switches from one process to another, saving and restoring its state.  

9. **What is a safe state in deadlock avoidance?**  
   - A state where a system can allocate resources without leading to a deadlock.  

10. **Explain the role of semaphores in process synchronization.**  
   - Semaphores help prevent race conditions and ensure mutual exclusion in shared resources.  

---

## **15 Short-Answer Questions (1 Mark Each)**  

1. **What is a process?**  
   - A program in execution.  

2. **What is a thread?**  
   - A lightweight process that shares resources with other threads.  

3. **Give an example of a CPU scheduling algorithm.**  
   - Round Robin (RR).  

4. **What does IPC stand for?**  
   - Inter-Process Communication.  

5. **What is the purpose of a PCB?**  
   - To store process-related information.  

6. **Name a preemptive CPU scheduling algorithm.**  
   - Shortest Remaining Time First (SRTF).  

7. **What is the time quantum in Round Robin scheduling?**  
   - The fixed time slice for each process.  

8. **What is the major drawback of FCFS scheduling?**  
   - It causes the **convoy effect**, where long processes delay short ones.  

9. **Define starvation in CPU scheduling.**  
   - A process waits indefinitely due to low priority.  

10. **What is a safe sequence in Banker’s Algorithm?**  
   - A sequence where processes execute without causing a deadlock.  

11. **What does mutual exclusion mean?**  
   - Only one process can access a resource at a time.  

12. **Name a deadlock avoidance algorithm.**  
   - Banker’s Algorithm.  

13. **What is a blocking system call?**  
   - A system call where the process waits until execution completes.  

14. **Give an example of a user-level thread library.**  
   - POSIX Threads (Pthreads).  

15. **What is a resource allocation graph?**  
   - A graphical representation of resource allocation in a system.  

---

## **5 Long-Answer Questions (10 Marks Each)**  

### **1. Explain different memory management strategies used in operating systems.**  
#### **Answer:**  
Memory management is responsible for efficiently allocating and deallocating memory to processes. There are several strategies used:  

1. **Swapping:**  
   - A process is temporarily moved from main memory to disk and brought back when needed.  
   - Reduces CPU idle time but increases disk I/O overhead.  

2. **Contiguous Memory Allocation:**  
   - Each process gets a single continuous block of memory.  
   - **Types:**  
     - **Fixed Partitioning:** Divides memory into fixed-size blocks.  
     - **Dynamic Partitioning:** Allocates memory dynamically based on process size.  

3. **Paging:**  
   - Divides memory into **fixed-sized pages**, and processes into **equal-sized page frames**.  
   - The OS uses a **page table** to map logical addresses to physical addresses.  

4. **Segmentation:**  
   - Divides memory into **variable-sized segments** based on program structures (code, data, stack).  
   - Provides better program organization but leads to **external fragmentation**.  

5. **Virtual Memory Management:**  
   - Uses **demand paging** to execute programs larger than RAM by keeping only needed pages in memory.  
   - Uses **page replacement algorithms** to remove old pages when memory is full.  

---

### **2. Explain paging and how it works. How does it solve the problem of external fragmentation?**  
#### **Answer:**  
Paging is a **non-contiguous memory allocation** technique that divides memory into fixed-size pages.  

**How Paging Works:**  
- The logical address space of a process is divided into **pages** (fixed-size).  
- The physical memory is divided into **page frames** of the same size.  
- A **page table** maintains mappings between logical page numbers and physical frame numbers.  

**Advantages:**  
- **Eliminates external fragmentation** since any free page frame can be allocated.  
- **Simplifies memory allocation** because all pages are of fixed size.  

**Example:**  
- Suppose a process needs **8 KB** memory, and page/frame size = **2 KB**.  
- The process will be divided into **4 pages**, which can be loaded into any available frames in memory.  

---

### **3. Explain segmentation with an example. What are its advantages and disadvantages?**  
#### **Answer:**  
Segmentation divides a process into **variable-sized logical units** called segments (e.g., code, data, stack).  

**Example:**  
Consider a process with:  
- **Code segment (4 KB)**  
- **Data segment (6 KB)**  
- **Stack segment (2 KB)**  

Each segment gets a separate **segment number** and an **offset** within that segment.  

**Advantages:**  
- Better **program structure** (matches how programs are written).  
- Can have **different segment sizes** based on actual requirements.  

**Disadvantages:**  
- Leads to **external fragmentation** as segments vary in size.  
- Requires a **segment table** for address translation.  

---

### **4. What is virtual memory? Explain demand paging and its advantages.**  
#### **Answer:**  
**Virtual memory** allows programs to execute without loading the entire process into RAM. It extends memory by using disk space as **swap space**.  

**Demand Paging:**  
- A page is loaded into memory **only when needed**, rather than loading the whole program.  
- If a page is not in memory, a **page fault** occurs, and the OS loads it from disk.  

**Advantages:**  
- **Allows large programs to run** with limited RAM.  
- **Reduces memory wastage** by loading only needed pages.  
- **Faster process startup** since not all pages are loaded initially.  

---

### **5. Explain page replacement algorithms. What is thrashing?**  
#### **Answer:**  
When memory is full, a **page replacement algorithm** decides which page to remove.  

**Page Replacement Algorithms:**  
1. **FIFO (First-In-First-Out):**  
   - Oldest page is removed first.  
   - Simple but may remove frequently used pages.  
2. **Optimal (OPT):**  
   - Replaces the page that will not be used for the longest time.  
   - Not practical since future requests are unknown.  
3. **LRU (Least Recently Used):**  
   - Replaces the page that was used the **longest time ago**.  
   - More efficient than FIFO but needs extra tracking.  

**Thrashing:**  
- Occurs when excessive paging slows down the system.  
- The CPU spends more time swapping pages than executing processes.  

---

## **10 Medium-Answer Questions (3 Marks Each)**  

1. **What is swapping in memory management?**  
   - A process is moved to disk when inactive and brought back when needed.  

2. **What is internal fragmentation?**  
   - Wasted memory inside a fixed-size block (e.g., a 4 KB block storing 3 KB data).  

3. **What is external fragmentation?**  
   - Wasted memory between allocated blocks due to variable-sized allocation.  

4. **What is the difference between paging and segmentation?**  
   - **Paging:** Fixed-size pages, no external fragmentation.  
   - **Segmentation:** Variable-sized segments, may cause fragmentation.  

5. **What is a page fault?**  
   - Occurs when a required page is not in RAM and must be fetched from disk.  

6. **What is the main advantage of demand paging?**  
   - Saves memory by loading only needed pages.  

7. **What is thrashing, and how can it be avoided?**  
   - Thrashing happens when excessive paging slows down the system. **Solutions:**  
     - Increase RAM.  
     - Use better page replacement algorithms.  

8. **What is a translation lookaside buffer (TLB)?**  
   - A small, fast memory that caches frequently used page table entries.  

9. **How does the optimal page replacement algorithm work?**  
   - Removes the page that will not be used for the longest time.  

10. **Why does FIFO page replacement perform poorly?**  
   - It may remove important pages, leading to frequent page faults.  

---

## **15 Short-Answer Questions (1 Mark Each)**  

1. **What is the main goal of memory management?**  
   - Efficient allocation and deallocation of memory.  

2. **What is a page?**  
   - A fixed-size block of a process's memory.  

3. **What is a page frame?**  
   - A fixed-size block of physical memory.  

4. **What does a page table do?**  
   - Maps logical pages to physical frames.  

5. **What is internal fragmentation?**  
   - Wasted memory inside allocated blocks.  

6. **What is a page fault?**  
   - When a required page is not found in RAM.  

7. **What is the advantage of paging?**  
   - Eliminates external fragmentation.  

8. **What is the disadvantage of paging?**  
   - Requires additional memory for page tables.  

9. **What is virtual memory?**  
   - A technique that allows processes to use more memory than physically available.  

10. **What is a segment table?**  
   - Stores the base and limit addresses of segments.  

11. **What is a working set?**  
   - The set of pages a process is actively using.  

12. **What is a page replacement algorithm?**  
   - A method to decide which page to remove from memory.  

13. **What is a resident set?**  
   - The set of pages currently loaded into RAM.  

14. **What is the purpose of TLB?**  
   - Speeds up address translation.  

15. **What is demand paging?**  
   - A system that loads pages only when needed.  

---


## **5 Long-Answer Questions (10 Marks Each)**  

### **1. Explain the structure of a file system and its components.**  
#### **Answer:**  
A **file system** is responsible for organizing, storing, and managing data on a storage device. Its components include:  

1. **Files:**  
   - The basic unit of storage, containing user or system data.  

2. **Directories:**  
   - Helps in organizing files in a hierarchical structure.  

3. **File Control Block (FCB):**  
   - Stores metadata about a file, such as name, size, location, permissions, and timestamps.  

4. **Superblock:**  
   - Stores details about the entire file system, such as free space, number of files, and directory structures.  

5. **Inode Table:**  
   - Stores metadata for each file, including its permissions, owner, and block addresses.  

6. **Disk Blocks:**  
   - Physical storage units where file data is stored.  

**File System Layers:**  
- **Application Layer:** User interactions with files.  
- **Logical File System:** Handles file structure and access permissions.  
- **Physical File System:** Manages disk storage and block allocation.  

---

### **2. Explain different file access methods with examples.**  
#### **Answer:**  
File access methods define how data is read from and written to files. The main types are:  

1. **Sequential Access:**  
   - Data is accessed in a linear order.  
   - Example: Reading a text file line by line.  

2. **Direct (Random) Access:**  
   - Any part of the file can be accessed directly using an index.  
   - Example: Databases where records are accessed randomly.  

3. **Indexed Access:**  
   - Uses an index to locate file data efficiently.  
   - Example: B-trees in file systems for faster lookup.  

4. **Memory-Mapped Access:**  
   - Maps a file into memory for faster read/write operations.  
   - Example: OS paging systems.  

---

### **3. What is file system mounting? Explain the process and types.**  
#### **Answer:**  
File system mounting is the process of making a file system accessible to users by attaching it to a directory.  

**Process of Mounting:**  
1. The OS checks if the file system is valid.  
2. It loads the metadata (superblock, FCB, etc.).  
3. It assigns a mount point (a directory where the file system is attached).  

**Types of Mounting:**  
1. **Automatic Mounting:** The OS mounts the file system during boot time.  
2. **Manual Mounting:** Users manually mount a file system using commands like `mount`.  
3. **Virtual Mounting:** Used in cloud-based or network file systems.  

---

### **4. Explain file sharing and file protection mechanisms in an operating system.**  
#### **Answer:**  
**File Sharing:**  
- Users can **share files** in multi-user environments.  
- **Types:**  
  1. **Single-user file sharing:** Files shared between different applications of the same user.  
  2. **Multi-user file sharing:** Files shared between different users.  

**File Protection Mechanisms:**  
1. **Access Control Lists (ACLs):** Specifies read, write, execute permissions for users and groups.  
2. **Password Protection:** Files are accessed using passwords.  
3. **Encryption:** Files are stored in an encrypted format for security.  
4. **User Groups:** Users are divided into groups with specific permissions.  

**Example of File Permissions in Linux:**  
```
-rwxr-xr--  user  group  filename
```
Here,  
- `rwx` (read, write, execute) for the **owner**.  
- `r-x` for the **group**.  
- `r--` for **others**.  

---

### **5. Explain the Kernel I/O system and its components.**  
#### **Answer:**  
The **Kernel I/O system** manages Input/Output operations in an operating system.  

**Components of Kernel I/O System:**  
1. **I/O Scheduler:** Decides the order in which I/O requests are processed.  
2. **Buffering:** Temporarily stores data during input/output operations.  
3. **Caching:** Stores frequently accessed data to improve performance.  
4. **Device Drivers:** Interface between the OS and hardware devices.  
5. **Interrupt Handlers:** Manage interrupts triggered by I/O devices.  

**Example:** When you print a document, the OS:  
1. Spools the data.  
2. Sends it to the printer buffer.  
3. Uses device drivers to communicate with the printer.  

---

## **10 Medium-Answer Questions (3 Marks Each)**  

1. **What is a file system?**  
   - A method for storing, organizing, and managing files on storage devices.  

2. **What are the different types of file systems?**  
   - **FAT32, NTFS (Windows), ext4 (Linux), HFS+ (Mac).**  

3. **What is file metadata?**  
   - Information about a file, including its name, size, type, and permissions.  

4. **What are inodes in file systems?**  
   - Data structures storing file metadata and disk block addresses.  

5. **What is the purpose of a superblock?**  
   - Stores global information about the file system, such as block size and free space.  

6. **What is the difference between absolute and relative file paths?**  
   - **Absolute path:** Full file location from the root directory.  
   - **Relative path:** Location relative to the current directory.  

7. **What is an Access Control List (ACL)?**  
   - A security mechanism defining file access permissions for users.  

8. **What is journaling in a file system?**  
   - A method to track changes before committing them to prevent data loss.  

9. **What is the function of a disk cache?**  
   - Stores frequently accessed disk data in RAM to improve performance.  

10. **What is the role of device drivers in the Kernel I/O system?**  
   - Enable communication between the OS and hardware devices.  

---

## **15 Short-Answer Questions (1 Mark Each)**  

1. **What is a file?**  
   - A collection of data stored in a storage system.  

2. **What is the difference between a directory and a file?**  
   - A directory contains multiple files, whereas a file stores data.  

3. **What is a mount point?**  
   - A location where a file system is attached to the main system.  

4. **What is an inode number?**  
   - A unique identifier for a file in a UNIX-like file system.  

5. **What does NTFS stand for?**  
   - **New Technology File System** (Windows file system).  

6. **What is the purpose of the file allocation table (FAT)?**  
   - Maps file blocks on the disk to track file locations.  

7. **What does ext4 stand for?**  
   - Fourth extended file system, used in Linux.  

8. **What is a soft link?**  
   - A pointer to another file, similar to a shortcut.  

9. **What is a hard link?**  
   - A direct reference to a file’s inode, not just its name.  

10. **What command is used to mount a file system in Linux?**  
   - `mount`  

11. **What is the function of a file descriptor?**  
   - A unique identifier for an open file.  

12. **What does the chmod command do?**  
   - Changes file permissions in Linux.  

13. **What is the difference between sequential and random access?**  
   - Sequential: Reads data in order.  
   - Random: Accesses any part directly.  

14. **What does I/O buffering do?**  
   - Temporarily stores data during input/output operations.  

15. **What is the purpose of a journaling file system?**  
   - Prevents data loss by recording changes before committing them.  

---
