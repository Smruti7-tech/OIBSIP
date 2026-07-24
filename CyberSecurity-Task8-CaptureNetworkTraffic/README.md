# Task 8: Capture Network Traffic Using Wireshark

## Objective

In this task, I learned how to capture network traffic using Wireshark. Moreover we discussed how to use filters and get valuable information about network communication via packets. Finally, we learned how to ensure secure communication.

## Tools

- Wireshark

- Windows 11 (Wi-Fi)

- Wi-Fi Network

## Installation

I have installed Wireshark on my computer. In the installation process, the program requested administrator privileges to install the packet capturing driver in order to capture packets.

## Wireshark Process

First of all, in Wireshark, I opened our Wi-Fi interface and started capturing packets. Then, for testing purposes, I opened some sites on my browser. After that, using the HTTP filter, I captured HTTP packets and saw HTTP messages in the packets. Moreover, using the DNS filter, I captured DNS packets and observed DNS queries. Similarly, using the TCP filter, I captured TCP packets and saw TCP messages. Finally, I saved the captured packets as ‘wireshark_capture.pcap’.

## HTTP

By using the HTTP filter, I captured HTTP packets and observed HTTP messages in the packets. In particular, I captured an HTTP GET request. Since the communication was not encrypted, it was possible to observe some of the information sent from the client to the server.

## DNS

By using the DNS filter, I captured DNS packets and observed DNS queries and responses. In particular, by looking at the DNS packets, one can see the correspondence between the website address and its IP address.

## TCP

By using the TCP filter, I captured TCP packets and observed TCP messages. In particular, TCP packets contain SYN, SYN-ACK, and ACK to establish a reliable connection in order for data to be transmitted from one computer to another.

## Why Is HTTP Dangerous

Since the data transmitted using the HTTP protocol is not encrypted, it might be vulnerable and can be sniffed using packet capture tools such as Wireshark.

## How Does HTTPS Make Communication Secure

The communication using the HTTPS protocol is encrypted using some cryptographic algorithms. Therefore, it is way more secure compared to the HTTP protocol.

## Glossary

Packet – A unit of data that is sent from one computer to another.

Protocol – A set of rules that defines how data is transmitted from one computer to another.

Port – Specific endpoints that are used by network applications.

Payload – Data that is sent using networks.

Handshake – A process of establishing a connection between two nodes in a network.

## Files

- README.md

- wireshark_capture.pcap

- HTTP Filter Screenshot.png

- DNS Filter Screenshot.png

- TCP Filter Screenshot.png

## Conclusion

At this lab, I have learned how to capture network packets using Wireshark. Moreover, we discussed the difference between encrypted and non-encrypted data transmission. Furthermore, I have observed the difference between TCP and UDP packets and learned how to use some filters in Wireshark.
