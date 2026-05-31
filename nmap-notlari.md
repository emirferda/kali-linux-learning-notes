# 🌐 Nmap Notes

## What is Nmap?

Nmap (Network Mapper) is an open-source tool used for network discovery and security auditing.

---

## Basic Scan

```bash
nmap 192.168.1.1
```

Scans the most common ports on the target system.

---

## Service Detection

```bash
nmap -sV 192.168.1.1
```

Attempts to identify services and versions running on open ports.

---

## Operating System Detection

```bash
nmap -O 192.168.1.1
```

Attempts to identify the target operating system.

---

## Port Scan

```bash
nmap -p 80,443 192.168.1.1
```

Scans only specific ports.

---

## Learning Notes

- Nmap is one of the most commonly used tools during reconnaissance.
- Information gathering is a critical phase of penetration testing.
- Open ports may reveal running services and potential attack surfaces.
