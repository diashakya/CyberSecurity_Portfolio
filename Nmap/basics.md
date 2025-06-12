# Network Scanning

1. Technique for identifying "devices"

2. These devices have IPs & MAC addresses

3. IP addresses have TCP/UDP ports (1-65,535)

4. Ports are open, closed, filtered or unfiltered

5. Ports run OS & services

## Common Ports

21(Port number)-FTP

22-SSH

23-Telnet

25-SMTP

53-DNS

80-HTTP

88-kerberos

110-POP3

111-NIX

135-RPC

139-SMB(old)

143-IMAP4

161-SNMP

162-SNMP traps

389-LDAP

443-HTTPS

445-SMB

3389-RDP

# What is Nmap?

- Free,Powerful Network Discovery tool

    - IP/Host/Port scanning
    - Services discovery
    - Version detection
    - OS detection
    - Scriptable interaction with targets(NSE)
    - Info on targets, including reverse DNS names, devices types, and MAC addresses


## Who used Nmap?

1. Pen-testers/ Ethical Hackers 

    - Reconnaissance & Info gatherting

2. IT Personnel

    - Inventory, network topology

3. Adversary entities

    - Post-intrusion activites
    
## Syntax

- nmap[Scan Types] [Options] <target>

- nmap -sS-p 22 192.168.1.0

## target Options

192.168.0.1             Single IP

dan.host.me             Single Host

192.168.1.0/24          Entire subnet

dan.host.me/24          Entire subnet

192.168.1.*             Entire subnet

192.168.1.10-50         IP Range

192.168.1.10-50,11.56   Multiple targets

## Basic Scans

-h                              nmap help

-sP                             Hosts up

-sS                             TCP SYN Scan (half-open)

-sT                             TCP Complete Scan

-Pn                             No Ping

-sV                             get service version

-sU                             UDP scan

-sL                             List Targets

-SA                             Test for Firewall protection

-r                              No random

--top-ports                     Top Ports

-6                              IPV6

-iL <file>                      Input File

-oA/-oX/-oN <file>              Output to file

--exclude                       Exclude from scan

-n                              Don't resolve name

-R                              Reverse DNS lookup

-F                              Fast Mode

-O                              OS Detection

-A                              OS/Sevies/script/traceroutr

--version-intensity <level>     Light to all probes(0-9)

-sC                             All default scripts

-v,-vv                          Verbosity levels

-PR                             ARP

-sn                             No port

-PS <port list>                 Specified ports