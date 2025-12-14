# 🛡️ Cybersecurity Foundations Lab

**Networking | Linux | Cryptography | Security Tools**

---

## 📌 Objective

The objective of this lab is to build strong fundamentals in **cybersecurity, networking, cryptography**, and to set up a **professional and safe ethical hacking lab**.
This lab provides hands-on exposure to Linux, networking protocols, cryptographic concepts, and industry-standard security tools within an isolated environment.

---

## 🧭 Lab Roadmap & Notes

---

## 1️⃣ Cybersecurity Basics

### 🔐 CIA Triad

* **Confidentiality** – Protect data from unauthorized access
* **Integrity** – Ensure data accuracy and trustworthiness
* **Availability** – Ensure systems and data are accessible when needed

### ⚠️ Threat Types

* Phishing
* Malware
* DDoS
* SQL Injection
* Brute Force Attacks
* Ransomware

### 🎯 Attack Vectors

* Social Engineering
* Wireless Attacks
* Insider Threats

---

## 2️⃣ Lab Environment Setup

### 🖥️ Virtualization

* VMware Workstation or VirtualBox

### 🐉 Attacker Machine

* **Kali Linux**

### 🎯 Target Machines

* **Metasploitable2**
* **DVWA (Damn Vulnerable Web Application)**

### 🔌 Network Configuration

* **Host-Only Adapter**
* Isolated and safe lab network
* No exposure to the internet

---

## 3️⃣ Linux Fundamentals (Notes + Cheat Sheet)

### 📁 File System Navigation

```bash
pwd        # show current directory
ls         # list files
ls -la     # detailed listing
cd /path   # change directory
mkdir dir  # create directory
rm file    # remove file
```

### 🔐 Permissions & Ownership

```bash
ls -l file.txt
chmod 755 file.txt
chmod +x script.sh
sudo chown user:user file.txt
```

### 📦 Package Management

```bash
sudo apt update
sudo apt upgrade
sudo apt install <package>
dpkg -l
```

### 🌐 Networking Commands

```bash
ifconfig
ip a
ping <ip>
netstat -tulnp
ss -tulnp
traceroute <ip>
```

---

## 4️⃣ Networking Basics

### 🌐 OSI Model Layers

1. Physical
2. Data Link
3. Network
4. Transport
5. Session
6. Presentation
7. Application

### 🔌 TCP/IP Protocol Suite

* TCP
* UDP
* IP
* ICMP
* ARP

### 🌍 DNS & HTTP/HTTPS

* DNS name resolution
* HTTP request/response cycle
* HTTPS encryption using SSL/TLS

### 🧮 IP Addressing & NAT

* IPv4 / IPv6
* Private vs Public IP
* Subnetting (CIDR)
* NAT (Network Address Translation)

---

## 5️⃣ Cryptography Basics

### 🔑 Encryption Types

* **Symmetric**: AES, DES
* **Asymmetric**: RSA, ECC

### 🧮 Hashing Algorithms

* MD5
* SHA-256

### 🔏 Digital Certificates & SSL/TLS

* Public & Private keys
* Certificate Authorities
* Secure communication over HTTPS

### ⚙️ OpenSSL Hands-On

```bash
openssl enc -aes-256-cbc -salt -in file.txt -out encrypted.bin
openssl enc -aes-256-cbc -d -in encrypted.bin -out decrypted.txt
```

---

## 6️⃣ Tool Familiarization

### 🟦 Wireshark (Packet Capture)

* Capture and analyze network traffic
* Filters:

```text
http
ip.addr == <ip>
tcp.port == 80
```

### 🟩 Nmap (Network Scanning)

```bash
nmap <ip>
nmap -sV <ip>
nmap -A <ip>
```

### 🟧 Burp Suite (Web Proxy)

* Intercept HTTP requests
* Analyze web vulnerabilities

### 🟨 Netcat (Network Debugging)

```bash
nc -lvp 4444
nc <ip> 4444
```

---

## 🏁 Conclusion

This lab provides a complete foundation for anyone starting a career in **cybersecurity**, **SOC analysis**, or **ethical hacking**. It combines theoretical understanding with hands-on practice using industry-standard tools in a safe environment.

---

## ⚠️ Disclaimer

All activities performed in this lab are strictly for **educational purposes** and conducted in an isolated environment.

---
