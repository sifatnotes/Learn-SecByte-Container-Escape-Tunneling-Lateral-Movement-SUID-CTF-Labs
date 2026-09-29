# Learn-SecByte-Container-Escape-Tunneling-Lateral-Movement-SUID-CTF-Labs
Hands-on cybersecurity and CTF labs covering host discovery, fping reconnaissance, lab setup, container escape, tunneling, lateral movement, MySQL enumeration, Chisel, SSH-style pivoting, and SUID privilege escalation.
# Learn SecByte Container Escape, Tunneling, Lateral Movement & SUID CTF Labs

A focused collection of hands-on cybersecurity and CTF labs from Learn SecByte covering host discovery, network reconnaissance, container escape, tunneling, lateral movement, MySQL security, Chisel, network pivoting, and Linux privilege escalation.

These labs are useful for cybersecurity students, CTF players, penetration testers, SOC analysts, and security learners developing practical skills in network and Linux security.

## Introduction

Modern penetration testing can involve more than discovering an exposed service. Security assessments may require understanding network paths, pivoting through controlled environments, analyzing containers, and identifying local privilege-escalation opportunities.

This repository organizes Learn SecByte labs around reconnaissance, tunneling, lateral movement, container security, database access, and Linux privilege escalation.

## Lab Collection

| Lab | Topic / Category | Tool or Technique |
|---|---|---|
| [Host Hunt Web to Root](https://learn.secbyte.org/ctf/host-hunt-web-to-root) | Host Discovery / Web-to-Root | Host Enumeration |
| [Fping First Then Find](https://learn.secbyte.org/ctf/fping-first-then-find) | Network Reconnaissance | fping |
| [Scope and Setup Lab Before Loot](https://learn.secbyte.org/ctf/scope-and-setup-lab-before-loot) | Lab Preparation / Reconnaissance | Scoping |
| [Container Escape Final Root](https://learn.secbyte.org/ctf/container-escape-final-root) | Container Security / Privilege Escalation | Container Escape |
| [Tunnel Run Lateral Movement](https://learn.secbyte.org/ctf/tunnel-run-lateral-movement) | Network Pivoting / Lateral Movement | Tunneling |
| [Containment Crack MySQL Loot](https://learn.secbyte.org/ctf/containment-crack-mysql-loot) | Database Security | MySQL |
| [Chisel Hopline](https://learn.secbyte.org/ctf/chisel-hopline) | Network Tunneling / Pivoting | Chisel |
| [Tunnel Stack](https://learn.secbyte.org/ctf/tunnel-stack) | Network Pivoting | Tunneling |
| [Keyhole to Root](https://learn.secbyte.org/ctf/keyhole-to-root) | Linux Privilege Escalation | Root Access |
| [Container Route Riddle](https://learn.secbyte.org/ctf/container-route-riddle) | Container / Network Security | Routing |
| [Tunnel Vision](https://learn.secbyte.org/ctf/tunnel-vision) | Network Tunneling | Tunneling |
| [SUID Shadow Bash](https://learn.secbyte.org/ctf/suid-shadow-bash) | Linux Privilege Escalation | SUID / Bash |

> Difficulty and CVE identifiers are not specified by the supplied lab URLs, so they are not assigned here.

## Direct Lab Links

1. https://learn.secbyte.org/ctf/host-hunt-web-to-root
2. https://learn.secbyte.org/ctf/fping-first-then-find
3. https://learn.secbyte.org/ctf/scope-and-setup-lab-before-loot
4. https://learn.secbyte.org/ctf/container-escape-final-root
5. https://learn.secbyte.org/ctf/tunnel-run-lateral-movement
6. https://learn.secbyte.org/ctf/containment-crack-mysql-loot
7. https://learn.secbyte.org/ctf/chisel-hopline
8. https://learn.secbyte.org/ctf/tunnel-stack
9. https://learn.secbyte.org/ctf/keyhole-to-root
10. https://learn.secbyte.org/ctf/container-route-riddle
11. https://learn.secbyte.org/ctf/tunnel-vision
12. https://learn.secbyte.org/ctf/suid-shadow-bash

## Categories

### Host & Network Reconnaissance
- Host discovery
- Network reconnaissance
- fping-based discovery
- Service and route identification
- Security assessment scoping

### Tunneling & Network Pivoting
- Network tunneling
- Pivoting concepts
- Chisel
- Lateral movement
- Route analysis

### Container Security
- Container reconnaissance
- Container networking
- Container escape concepts
- Host-to-container security boundaries

### Database Security
- MySQL enumeration
- Database access analysis
- Credential and data discovery within authorized labs

### Linux Privilege Escalation
- SUID security
- Bash privilege escalation
- Root-access attack paths
- Local privilege-boundary analysis

## Learning Path

A practical sequence for this collection is:

1. Start with **Scope and Setup Lab Before Loot** to understand controlled assessment preparation.
2. Use **Fping First Then Find** and **Host Hunt Web to Root** for host and network discovery.
3. Study **Tunnel Vision** and **Tunnel Stack** to understand tunneling concepts.
4. Continue with **Chisel Hopline** for practical network-pivoting exercises.
5. Explore **Tunnel Run Lateral Movement** and **Container Route Riddle** for controlled lateral-movement and routing scenarios.
6. Study **Containment Crack MySQL Loot** for database-security practice.
7. Progress to **Container Escape Final Root** for container-security and escape concepts.
8. Finish with **Keyhole to Root** and **SUID Shadow Bash** for Linux privilege escalation.

## How to Use the Labs

- Perform all exercises only in authorized lab environments.
- Begin with clear scope and controlled targets.
- Enumerate hosts and services before attempting exploitation.
- Map network routes before performing pivoting exercises.
- Study how tunnels change access between isolated network segments.
- Analyze container boundaries and privileges carefully.
- Document database findings and privilege boundaries.
- Record commands, observations, and lessons learned.
- Consider defensive mitigations for every technique practiced.

## Skills Covered

- Host discovery
- Network reconnaissance
- fping
- Network tunneling
- Chisel
- Network pivoting
- Lateral movement concepts
- Container security
- Container escape concepts
- MySQL security
- Linux privilege escalation
- SUID security
- Bash security
- CTF methodology
- Penetration testing workflows

## Learn SecByte

These exercises are hosted through Learn SecByte's cybersecurity learning platform. Use the individual links above for the original lab exercises and their current instructions.

## Disclaimer

This repository is intended for cybersecurity education, CTF practice, and authorized security testing. Do not use these techniques against systems, networks, containers, databases, or accounts without explicit permission. The repository does not provide unauthorized access, stolen credentials, or instructions for attacking real-world targets.
