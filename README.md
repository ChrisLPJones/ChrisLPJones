# Chris Jones | Security-Focused Developer

Career-changer transitioning from twenty years in professional kitchens into technology, with ten years of hands-on cybersecurity practice as a serious ongoing discipline. I like understanding how systems break, then building things that hold up better.

Currently completing Hack The Box's Certified Penetration Testing Specialist (CPTS), with OSCP planned to follow. Active on Hack The Box and in CTFs, with a home lab running Proxmox, Active Directory, and Windows/Linux VMs built specifically for practising attack and defence.

## Technical Skills

**Security & Offensive**
- Web application testing: SQL injection, XSS, XSLT injection, LFI/RFI, authentication bypass, IDOR
- Active Directory attacks: enumeration, Kerberos abuse, credential reuse, privilege escalation, lateral movement
- Password cracking & hash analysis (Hashcat, John the Ripper)
- Applied cryptography with .NET's `System.Security.Cryptography` (AES-256, PBKDF2)

**Tools**
Burp Suite, Nmap, Metasploit, Wireshark, Nuclei, ffuf, dirbuster, nxc, ldapsearch, sqlmap, tmux, nvim

**Development**
- **Languages:** C#, JavaScript/Node.js, Python, PowerShell, Bash, T-SQL
- **Frameworks:** .NET 8 (ASP.NET Core Minimal APIs), .NET Framework 4.8.1, React (Vite), Express
- **Databases:** SQL Server, PostgreSQL, SQLite
- **Cloud & Infrastructure:** AWS (Lambda, API Gateway, S3, CloudFront, Route 53), Docker & Docker Compose, Proxmox, Linux administration

## Featured Projects

### [ChefClaude](https://github.com/ChrisLPJones/ChefClaude) — [live at chefclaude.com](https://www.chefclaude.com)
Live web app that generates recipes from user-supplied ingredients using the Anthropic Claude API. Serverless architecture on AWS.
**Tech:** React (Vite), Node.js/Express on AWS Lambda, API Gateway, S3, CloudFront, Route 53

### [FileVault](https://github.com/ChrisLPJones/FileVault) (in progress)
Full-stack secure file-sharing web application. User authentication, encrypted file storage on disk, SQL Server metadata tracking, dedicated xUnit test suite. Database containerised via Docker Compose.
**Tech:** ASP.NET Core (.NET 8 Minimal APIs), React, SCSS, SQL Server, raw T-SQL, Docker Compose, xUnit

### [CipherChat](https://github.com/ChrisLPJones/CipherChat)
Console-based multi-user chat where all messages are encrypted client-side with AES-256 before transmission — the server relays only ciphertext it cannot read. Key derivation via PBKDF2 (SHA-256) with random salt, implemented on top of `System.Security.Cryptography`.
**Tech:** C# / .NET 6, TCP client/server

## Certifications

- **Hack The Box CPTS** (Certified Penetration Testing Specialist) — in progress, ~50%
- **OSCP** (Offensive Security Certified Professional) — planned
- **Baseline security clearance** — granted 2026, sponsored by Defence Force Recruiting
- **C# Mastercourse** — Tim Corey (IAmTimCorey), completed 2025
- **Bachelor of Creative Technology** — JMC Academy, 2024

## Get in Touch

Open to conversations about junior security engineering roles, junior developer roles, and applied security work.

---

*"Security is not a product, but a process." — Bruce Schneier*
