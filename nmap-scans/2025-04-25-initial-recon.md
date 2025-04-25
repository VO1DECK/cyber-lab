# Initial Recon and Enumeration

Date: April 25, 2025
Operator: VO1DΞCK

## Commands Executed
- `ip a`
- `hostnamectl`
- `netstat -tuln`
- `nmap -sn 127.0.0.1`
- `nmap -sS -T4 -Pn 127.0.0.1`

## Observations
- Interface: wlp9s0f0 (wireless)
- VPN Interface Detected: wg0 (WireGuard)
- Services: DNS resolved, no exposed external ports
