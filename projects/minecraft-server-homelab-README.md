# Minecraft Server Homelab

## Overview
Deployed a Minecraft server on a spare mini PC within my home network and configured the network so friends could connect remotely over the internet. This project gave me hands-on experience with basic server administration, IP addressing, router configuration, and networking fundamentals.

## Objectives
- Host a dedicated Minecraft server on a spare computer.
- Configure router port forwarding so external players can reach the server.
- Understand how IP addresses and ports are used in client-server communication.
- Practice troubleshooting connectivity between clients and a hosted service.

## Hardware and Technologies
- **Hardware:** Mini PC / spare computer
- **Service:** Minecraft dedicated server
- **Networking:** TCP/IP, IP addressing, SOHO router, port forwarding
- **Network concepts:** Private vs. public IP addresses, ports, client-server communication

> Add your operating system, Minecraft server version, and any tools you used once you confirm those details.

## What I Did
1. Set up a Minecraft server on a spare mini PC.
2. Identified the IP address information needed to connect to the server.
3. Configured port forwarding on my home/SOHO router to direct incoming connections to the server.
4. Tested connectivity so friends could join from outside my home network.

## Skills Demonstrated
- Basic server setup and configuration
- TCP/IP networking fundamentals
- IP addressing
- Router configuration
- Port forwarding
- Connectivity troubleshooting

## Security Considerations
Port forwarding exposes a service to connections from the internet. For a safer setup:
- Forward only the required port and protocol for the server.
- Keep the server software and operating system updated.
- Use an allowlist or other access controls where appropriate.
- Avoid exposing router administration, file-sharing, or remote-management ports.
- Review server logs and close the port when the server is no longer needed.

**Note:** Minecraft Java Edition commonly uses TCP port `25565` by default. Verify the port and protocol configured on your own server before documenting them.

## What I Learned
This project helped me connect networking concepts to a real setup. In particular, I learned how port forwarding allows an external client to reach a service hosted on a device inside a private home network.

## Future Improvements
- Configure a DHCP reservation for the mini PC so its private IP address stays consistent.
- Configure the server to start automatically after reboot.
- Set up regular backups of the world and server configuration.
- Monitor server logs and resource usage.
- Document the network layout and troubleshooting steps.

## Project Notes
For privacy and security, do not publish your public IP address, home network details, router credentials, or other sensitive configuration information in this repository.
