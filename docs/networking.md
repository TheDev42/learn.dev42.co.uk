## Network Layers And Protocols
> [!IMPORTANT]
> This Page Is Still A Working Progress.

##### Network Protocols refer to a set of rules and conventions that define how data is transmitted and received over a network. They establish the methods and procedures for communication between different network devices.

### Physical Layer (L1)
Transmission of raw bitstreams over physical mediums.

- USB (Universal Serial Bus): 

- DSL (Digital subscriber line):

- ADSL (Asymmetric Digital Subscriber Line)

- 802.11 WiFi (wireless fidelity):
   - 802.11
      - WiFi 1 Released: 1997 Frequency: 2.4GHz
   - 802.11b
      - WiFi 2 Released: 1999 Frequency: 2.4GHz
   - 802.11a
      - Wifi 3 Released: 1999 Frequency: 5GHz
      - Released: 2003 Frequency: 2.4GHz
   - 802.11g
      - WiFi 4 Released: 2009 Frequency: 2.4GHz, 5GHz 
   - 802.11n
      - WiFi 5 Released: 2013 Frequency: 5GHz 
   - 802.11ac
      - WiFi 6 Released: 2021 Frequency: 2.4GHz, 5GHz 
   - 802.11ax
      - WiFi 6E Released: 2024 Frequency: 6GHz 
   - 802.11be
      - WiFi 7 Released: 2024 Frequency: 2.4GHz, 5GHz, 6GHz
   - 802.11bn
      - WiFI 8 Released: a Frequency: 2.4GHz, 5GHz, 6GHz
 
- 1000BASE-T

### Data Link Layer (L2)
Link Layer Protocols: Protocols that work at the network interface level, facilitating data transfer between devices on the same local network, like Ethernet.

- MAC

- Ethernet

- VLan

### Network Layer (L3)
Routing data packets through the network.

- IP (Internet Protocol): Routes one packet from a source machine to a destination machine. IP wraps other higher level protocols such as TCP, UDP, etc, which handle routing packets to a specific application/port on the destination machine.

- NAT

### Transport Layer (L4)
Transport Protocols: Protocols responsible for end-to-end communication, ensuring complete data transfer. Examples include TCP (Transmission Control Protocol) and UDP (User Datagram Protocol).

- TCP (Transmission Control Protocol): Routes data to a specific port. TCP provides acknowledgements to verify that a packet was recieved by the destination as well as ensures ordering of packets.

- UDP (User Datagram Protocol): A lightweight protocol that routes a packet to a specific port. UDP does not handle any acknowledgement or ordering of packets.

### Session Layer (L5)
Maintaining sessions and controlling connections.

- SMB

- RTCP

- SOCKetS

### Presentation Layer (L6)
Translation of data formats and encryption.

- TLS

- SSL

### Application Layer (L7)
Application Protocols: These protocols provide services directly to end-users and define how applications interact over a network, such as HTTP for web browsing and SMTP for email.

- HTTP (Hypertext Transfer Protocol): Used to access web pages.

- FTP (File Transfer Protocol): Used for transferring files between computers.

- DHCP

- DNS

- HTTPS

- NFS

- POP3

- SMTP

- SNMP

- NTP

- IRC

- SSH

- IMAP

## OSI Model
> [!NOTE]
> We Dont Need To Know This For GCSE AQA!

The Open Systems Interconnection (OSI) model describes seven layers that computer systems use to communicate over a network. The OSI model is divided into seven distinct layers, each with specific responsibilities, ranging from physical hardware connections to high-level application interactions.

Each layer of the OSI model interacts with the layer directly above and below it, encapsulating and transmitting data in a structured manner. The OSI model serves as a universal language for networking, providing a common ground for different systems to communicate effectively.

<p align="left">
	<img src="files/OSI-vs-TCP/IP-models.jpg">
</p>

### OSI vs. TCP/IP Model
The Transfer Control Protocol/Internet Protocol (TCP/IP) is older than the OSI model and was created by the US Department of Defense (DoD). A key difference between the models is that TCP/IP is simpler, collapsing several OSI layers into one:

- OSI layers 5, 6, 7 are combined into one Application Layer in TCP/IP
- OSI layers 1, 2 are combined into one Network Access Layer in TCP/IP – however TCP/IP does not take responsibility for sequencing and acknowledgement functions, leaving these to the underlying transport layer.

Other important differences:
- TCP/IP is a functional model designed to solve specific communication problems, and which is based on specific, standard protocols. OSI is a generic, protocol-independent model intended to describe all forms of network communication.
- In TCP/IP, most applications use all the layers, while in OSI simple applications do not use all seven layers. Only layers 1, 2 and 3 are mandatory to enable any data communication.

- [ ] test
- [x] nope

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

