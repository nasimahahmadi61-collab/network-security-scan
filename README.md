# network-security-scan
# Network Security Scan

This project demonstrates basic network scanning using Nmap.

## Objective
To identify open ports and analyze potential security risks.

## Tools Used
- Nmap

## Command Used
nmap -sS -sV scanme.nmap.org

## Results

Open ports identified:
- 22/tcp (SSH)
- 80/tcp (HTTP)
- 9929/tcp (nping-echo)
- 31337/tcp (tcpwrapped)

Several ports were filtered, indicating firewall protection.

## What I Learned
- Network scanning basics
- Identifying open ports
- Understanding security risks
