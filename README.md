# Network Recon Lab

## Objective

This project documents my cybersecurity networking fundamentals and reconnaissance practice.

## Topics Covered

- Linux networking
- PowerShell networking
- TCP/IP basics
- Ports and services
- Network reconnaissance

## Tools Used

- Kali Linux
- PowerShell
- Nmap
- netstat
- ss
- ipconfig

## Skills Learned

- Identifying IP addresses
- Finding gateways
- Reading active connections
- Understanding listening ports
- Basic reconnaissance methodology

- ## Lab Results

### Linux Network Information

- IP Address: 10.0.2.15
- Gateway: 10.0.2.2
- Network Range: 10.0.2.0/24

### Observations

- No listening services detected with ss -tuln
- Active HTTPS connections observed
- DHCP traffic identified
- VirtualBox NAT environment detected

## Commands Practiced

### Linux

bash
ip a
ip route
ss -tuln
netstat -ano
arp -a


 PowerShell

 powershell
ipconfig
ipconfig /all
netstat -ano
Test-Connection google.com

## Day 2 - TCP/IP and Port Analysis

### Concepts Learned

- TCP vs UDP
- TCP 3-Way Handshake
- Open vs Closed vs Filtered ports
- Active reconnaissance
- SYN scanning

### Commands Practiced

#### Linux

```bash
ss -ant
sudo nmap -sS 127.0.0.1
sudo nmap -sV scanme.nmap.org
```

#### PowerShell

```powershell
Get-NetTCPConnection
Test-NetConnection google.com -Port 443
```
## Day 3 - Linux Fundamentals and Privileges

### Concepts Learned

- Linux filesystem structure
- Users and groups
- Linux permissions
- sudo privileges
- Sensitive files
- Running processes

### Commands Practiced

```bash
whoami
id
pwd
ls -la
cat /etc/passwd
sudo -l
ps aux
```

### Important Files

```text
/etc/passwd
/etc/shadow
```
