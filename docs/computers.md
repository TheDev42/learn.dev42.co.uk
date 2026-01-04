# Computer Systems and Databases:

A computer system consists of **hardware** and **software** that work together to process data or complete tasks. 

- **Hardware** - the physical stuff that make up your computer
- **Software** - the programs that a computer runs, you can have;

  - Application Software - programs that help the user <ins>complete specific tasks</ins> e.g. word processors, web browsers, databases, software, games etc.
  - System Software - designed to <ins>run and maintain</ins> a computer system e.g. OS, utilities etc.

### General Purpose Computers:
- Definition - designed to perform many tasks and functions 
- Examples - PCs, tablets, phones
- Advantages - can perform <ins>a wide variety of tasks</ins>, more <ins>affordable</ins> for multiple uses, and they can be <ins>upgraded for new changes/needs</ins> by 
  being upgraded with new hardware/software

### Embedded Systems:
- Definition - dedicated computers built into other devices to monitor and control machinery by being used as control systems
- Examples - dishwashers, microwaves, TVs
- Advantages - since they are dedicated, they are <ins>easier to design</ins>, <ins>cheaper to produce</ins>, and <ins>more efficient</ins> that general purpose computers

<img width="443" alt="image" src="https://github.com/user-attachments/assets/15284186-5b94-4a67-b224-18765c2bca57" />

- **Power Supply** - supplies power to motherboard, optical drives, hard drives and other hardware
- **Case Cooling Fan** - extracts hot air from the computer case
- **CPU Heatsink** and Cooling Fan - keeps CPU at a steady temperature
- **CPU** - (hidden under the heat sink), the most important components as it does all the processing
- **Optical Drive** - for read/writing of optical disks
- **RAM sticks** - computer memory slots in here
- **Motherboard** - the main circuit board in the computer where the hardware is connected
- **Hard Disk Drive** - internal secondary storage
- **Graphics Card** - handles graphics and image processing

## The CPU:

This is the brain of the computer as it <ins>processes all of the data and instructions</ins> that make the system work. <ins>Von Neumann architecture</ins> describes the main components of the CPU and how they interact with one another. A key feature is that it only uses <ins>one memory for both the data and the instructions.</ins>

**The Control Unit (CU):**
- Overall control of CPU
- Performs <ins>Fetch-Decode-Execute cycle</ins>
  - Fetch - The CU reads the memory address of an instruction and the instruction stored with that address is copied from memory to the registers
  - Decode - The instruction copied from memory is then decoded in the CU and the CU then prepares for the next step
  - Execute - The instruction is performed (write data to memory/ do a caluculation using ALU/ halt a program etc.)
- Controls flow of data inside the CPU (to other components; registers, ALU, cache) and outside CPU (to main memory and I/O devices)
- Keeps track of memory addresses of instructions for each cycle

**The Algrothmic Logic Unit (ALU):**
- Does all the collections
- Performs <ins>algorithmic</ins> instructions - addition, subtraction, multiplication, division and comparisons
- Performs <ins>logic</ins> instructions - AND, OR, NOT, XOR etc.
- Registers hold the intermediate results of calculations

**Cache:**
- Very fast <ins>memory</ins> in the CPU (faster than RAM but slower than registers)
- Stores regularly used data so CPU can access it quickly
- When CPU requests data, first checks cache; if not there then goes to RAM
- <ins>Low capacity and expensive</ins> in comparison to RAM and secondary storage

- A <ins>larger cache</ins> means the CPU has <ins>faster</ins> access to a <ins>larger</ins> amount of data it needs to process

**The Clock:**
- Sends out a signal that continually cycles between 1 and 0, usually at a constant rate
- Signal used to synchronise when instructions are carried out and helps coordinate flow of data
- clock speed is number of clock cycles per second

- A typical desktop computer has a clock speed of around <ins>3.5 GHz</ins> (3.5 billion clock cycles per second)
- The higher the clock speed, the <ins>more instructions</ins> that can be carried out in <ins>one second</ins>

**Buses:**
- <ins>Collection of wires</ins> used to transmit data between components of the CPU and the CPU system
- A processor may have seperate buses for carrying data, instructions and memory addresses

**Registers:**
- Super quick memory to write into
- They <ins>temporarily hold tiny bits of data</ins> (data instructions and memory addresses) needed by the CPU
- There are specific registers for different tasks

**Cores:**
- Each core can process an instruction independantly to the rest
- <ins>More cores</ins> means <ins>more instructions</ins> can be processed at any one time

## Memory:

**Random Access Memory (RAM):**
- main memory in a computer
- can be <ins>read</ins> and <ins>written</ins> into
- <ins>volatile</ins> - memory is temporary and if power is lost, any data is also lost
- all data, files and programs are stored here when in use
- software applications, documents and files are copied from secondary storage to RAM when in use
- slower than cache and registers but faster than secondary storage

**Read Only Memory (ROM):**
- <ins>non-volatile</ins> memory
- can only be read, not written into
- contains <ins>BIOS</ins> - instructions to boot up the computer

### Secondary Storage:
