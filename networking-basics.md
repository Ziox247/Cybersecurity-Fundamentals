\## What is Computer Networking? ##



Networking is the practice of connecting devices to exchange data securely and reliably.



Why security cares:



\#Attacks travel over networks

\#Ports and protocols expose services

\#Misconfigurations cause breaches



\## TCP vs UDP ##

\# TCP (Transmission Control Protocol)



Connection-oriented

Reliable and ordered delivery

Error checking and retransmission

Slower but secure



Used for:

Web traffic

Email

File transfer

Remote access



\# UDP (User Datagram Protocol)



Connectionless

No delivery guarantee

Faster and lightweight

No retransmission



Used for:

Video streaming

DNS queries

VoIP

Online gaming



\## OSI Model ## 



| Layer | Name         | Example            |

| ----- | ------------ | ------------------ |

| 7     | Application  | HTTP, FTP, DNS     |

| 6     | Presentation | SSL/TLS            |

| 5     | Session      | Session management |

| 4     | Transport    | TCP, UDP           |

| 3     | Network      | IP                 |

| 2     | Data Link    | MAC, ARP           |

| 1     | Physical     | Cables             |



\#Security mapping:

Firewalls → Layer 3 \& 4

WAF → Layer 7



\#TCP/IP Model



| Layer          | Function        |

| -------------- | --------------- |

| Application    | HTTP, FTP, SMTP |

| Transport      | TCP, UDP        |

| Internet       | IP, ICMP        |

| Network Access | Ethernet        |





\## Common Network Protocols ##



HTTP – Web traffic (unencrypted)



HTTPS – Secure web traffic



FTP – File transfer (insecure)



SFTP – Secure file transfer



SMTP – Sending emails



POP3 / IMAP – Receiving emails



DNS – Domain name resolution



DHCP – IP address assignment



SNMP – Network monitoring



NTP – Time synchronization



ICMP – Network diagnostics



\## Common Ports (Well-Known \& Important) ##



\#Secure \& Remote Access



22 – SSH

3389 – RDP

5900 – VNC



\#Web \& Application



80 – HTTP

443 – HTTPS

8080 – Alternate HTTP

8443 – Alternate HTTPS



\#Email



25 – SMTP

465 – SMTPS

587 – SMTP (Secure)

110 – POP3

995 – POP3S

143 – IMAP

993 – IMAPS



\#File Transfer



20 / 21 – FTP

22 – SFTP

69 – TFTP



\#Network Services



53 – DNS

67 / 68 – DHCP

123 – NTP

161 / 162 – SNMP



\# Databases (Security-Critical)



3306 – MySQL

5432 – PostgreSQL

1433 – Microsoft SQL

27017 – MongoDB

6379 – Redis



⚠️ Security note:

Databases should never be exposed publicly.



\## Subnetting (High-Level) ##



Divides networks into smaller segments

Improves security and performance

Uses CIDR notation



