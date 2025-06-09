# Port Scanning

Port scanning is a technique used to discover open ports and services on a computer or network device.

Imagine a building with many doors (ports). You want to check:

-Which doors are open

-Which are closed

-What kind of service is behind each door (e.g., a shop, an office, a storage room, etc.)

In networking, each port represents a potential communication endpoint for a specific service or application (like a web server, email server, SSH, etc.).

## How it works?

-Every device connected to a network has 65,535 ports (TCP/UDP).

-A port scanner (like Nmap) sends packets to these ports and waits for a response.

-Based on the response, it can tell:
Port is open --> Service is running

Port is closed --> No service

Port is filtered --> protected by firewall