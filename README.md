# Muhammad Shaheem — Cybersecurity Student @ GIKI

Cybersecurity undergraduate building hands-on experience in **applied cryptography, secure software development, and network security**. I work on real projects — from benchmarking post-quantum algorithms to building encrypted systems — and document everything.

---

## 🚀 Projects

### 🔬 [kyber-ecc-performance-analysis](https://github.com/Shaheem22/kyber-ecc-performance-analysis)
**Post-Quantum vs Classical Cryptography — IoT Performance Benchmarking (Python)**

Empirical comparison of **Kyber (post-quantum KEM)** and **ECC (classical)** under simulated IoT network conditions using MQTT over TLS.
- 30 trials per scenario across 7 packet loss levels (0–10%) and 3 jitter levels (0–50ms)
- Kyber averaged ~330ms handshake vs ECC's ~590ms — faster and more stable under stress
- Both maintained 100% success rate across all tested conditions
- Full statistical analysis: mean, std dev, P95, jitter sensitivity index, failure cliff detection

---

### 🔐 [Encrypted-Campus-Complaint-System](https://github.com/Shaheem22/Encrypted-Campus-Complaint-System)
**Encrypted Complaint Management System — CY321 Secure Software Design (Node.js)**

Secure web-based complaint platform with strong authentication and role-based access control.
- End-to-end encryption, input validation, and secure data handling
- Role-based access for students, staff, and admins
- Built following secure development principles (CY321)

---

### 🔍 [codeql-security-lab](https://github.com/Shaheem22/codeql-security-lab)
**Static Analysis & SQL Injection Detection using CodeQL — CY321 Secure Software Design (Python + CodeQL)**

Wrote a custom CodeQL query to automatically detect SQL injection vulnerabilities in Python code using taint tracking.
- Modelled user input → SQL sink data flow to flag unsanitized query construction
- Query successfully detected all vulnerabilities in intentionally insecure code, zero false positives on secure version
- Built and queried a CodeQL database from a Python codebase using the CLI
- CodeQL is used in production security engineering at companies like Microsoft and Google

---

### 🔐 [password-manager-xor-cpp](https://github.com/Shaheem22/password-manager-xor-cpp)
**CLI Password Manager with XOR Encryption (C++)**

Command-line credential vault with encryption, file I/O, and a menu-driven interface.
- Vault encryption/decryption with user-provided key
- Practical implementation of file handling and basic crypto concepts

> XOR is used for learning purposes, not production security.

---

### 📦 [file-huffman-xor-tool](https://github.com/Shaheem22/file-huffman-xor-tool)
**File Compression + XOR Encryption Tool (C++)**

Combines **Huffman coding** for lossless compression with XOR-based encryption in a single CLI tool.
- Huffman tree construction, encoding, and decoding
- Integrated encryption stage with user key
- Focus on algorithms, data structures, and binary file processing

---

### 📱 [ceh-module17-mobile-labs](https://github.com/Shaheem22/ceh-module17-mobile-labs)
**CEH Module 17 — Mobile Security Labs (ParrotOS)**

Hands-on controlled labs covering mobile attack vectors and security testing.
- Android emulator + ParrotOS environment setup
- Tool usage (Phonesploit, SET) with documented outcomes
- Step-by-step write-ups of each lab

---

### 📁 [google-cybersecurity-portfolio](https://github.com/Shaheem22/google-cybersecurity-portfolio)
**Google Cybersecurity Professional Certificate — Portfolio**

Security artifacts produced throughout the Google Cybersecurity Certificate.
- Risk assessments and security audits
- Network incident analysis and response documentation
- Linux and SQL-based security investigations

---

## 🧰 Tech Stack

**Languages:** Python · C++ · JavaScript (Node.js) · SQL · CodeQL  
**Security:** Applied cryptography · Secure software development · Network security · Vulnerability assessment  
**Tools:** Wireshark · Nmap · Metasploit (lab) · Cisco Packet Tracer · Social Engineering Toolkit  
**OS:** Linux (ParrotOS, Kali, Ubuntu) · Windows  
**Networking:** TCP/IP · MQTT/TLS · Packet analysis · Network simulation  

---

## 📌 Currently

- Benchmarking post-quantum cryptography for IoT environments (WAMS project — complete)
- Building an encrypted complaint management system with secure auth (SSD — near complete)
- Designing a constraint-based timetable generator (DAA — near complete)
- Configuring a simulated secure network in Cisco Packet Tracer (CCN)
- Writing CodeQL queries for static analysis and vulnerability detection (SSD Lab — complete)
- Completing CEH labs and TryHackMe paths
- Progressing through the Google Cybersecurity Professional Certificate

---

## 🎓 Education

**BS Cybersecurity** — Ghulam Ishaq Khan Institute of Engineering Sciences and Technology (GIKI) | 2023–2027  
Relevant coursework: Wireless & Mobile Security · Secure Software Design · Information Security · Computer Communications & Networks · Data Structures & Algorithms · Design & Analysis of Algorithms · Database Management Systems · Operating Systems
