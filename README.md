# Simple Ping in C
A stripped down version of the original Ping tool created by Mike Muuss back in 1983.  My ping program was written for a tutorial in network security at Marlboro College. The assignment was designed to be an introduction to socket programming and a chance to bone up on C.

# Running
Change the src and dst IP addresses in ping.c to your own / that of your router's.
```
$ cc ping.c
$ sudo ./a.out
Bytes received: 28

IP HEADER
	IP version: 4
	Protocol: 1
	Identification: 0xAECE
	Header len: 20
	Checksum: 0x7208
	TTL: 64
	Source IP: 172.17.0.1
	Destination IP: 172.17.1.211

ICMP HEADER
	Type: 0
	Code: 0
	Checksum: 0xF8E9
	Identifier: 1337
```
The program returns the recieved ICMP packet.
