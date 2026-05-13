# Day 2 - TCP/IP and Port Analysis

## TCP vs UDP

### TCP
- Reliable
- Uses handshake
- Used for HTTP, HTTPS, SSH, RDP

### UDP
- Faster
- No handshake
- Used for DNS, VoIP, streaming

---

## TCP 3-Way Handshake

1. SYN
2. SYN-ACK
3. ACK

Connection established after ACK.

---

## Nmap Commands

### SYN Scan

```bash
sudo nmap -sS 127.0.0.1
```

### Version Detection

```bash
sudo nmap -sV scanme.nmap.org
```

---

## Key Learnings

- Learned difference between TCP and UDP
- Understood SYN scanning
- Learned port states
- Practiced active reconnaissance
- Practiced service detection
