## Network Layers And Protocols
> [!IMPORTANT]
> This Page Is Still A Working Progress.

##### Network Protocols refer to a set of rules and conventions that define how data is transmitted and received over a network. They establish the methods and procedures for communication between different network devices.

### Physical Layer (L1)

- USB

- DSL

- 802.11 WiFi

- 1000BASE-T

### Data Link (L2)

- MAC

- Ethernet

- VLan

### Network Layer (L3)

- IP (Internet Protocol): Routes one packet from a source machine to a destination machine. IP wraps other higher level protocols such as TCP, UDP, etc, which handle routing packets to a specific application/port on the destination machine.

- NAT

### Transport Layer (L4)

- TCP (Transmission Control Protocol): Routes data to a specific port. TCP provides acknowledgements to verify that a packet was recieved by the destination as well as ensures ordering of packets.

- UDP (User Datagram Protocol): A lightweight protocol that routes a packet to a specific port. UDP does not handle any acknowledgement or ordering of packets.

### Session Layer (L5)

- SMB

- RTCP

- SOCKetS
- 

### Presentation Layer (L6)

- TLS

- SSL

### Application Layer (L7)

These protocols provide services directly to end-user applications. Some notable application layer protocols are:
- HTTP (Hypertext Transfer Protocol): Used to access web pages.
- FTP (File Transfer Protocol): Used for transferring files between computers.

- DHCP

-DNS

-HTTPS

-NFS

-POP3

-SMTP

-SNMP

-NTP

-IRC

-SSH

-IMAP

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
