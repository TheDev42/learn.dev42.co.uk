# Networking

## Network Layers

### Network Layer (L3)

#### IP (Internet Protocol) - Network Layer

IP routes one packet from a source machine to a destination machine. IP wraps other higher level protocols such as TCP, UDP, etc, which handle routing packets to a specific application/port on the destination machine.

### Transport Layer (L4)

#### TCP (Transmission Control Protocal) - Transport Layer

TCP routes data to a specific port. TCP provides acknowledgements to verify that a packet was recieved by the destination as well as ensures ordering of packets.

#### UDP (User Datagram Protocol) - Transport Layer

UDP is a lightweight protocol that routes a packet to a specific port. UDP does not handle any acknowledgement or ordering of packets.

## TCP/IP

Introduction to TCP/IP and sockets P1: Introducing the protocols and API
