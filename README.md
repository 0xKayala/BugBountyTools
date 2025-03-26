# 🕵️ **A-to-Z Bug Bounty Hunting Tools** [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of tools used by Bug Bounty hunters and security researchers for testing web applications, APIs, mobile apps, cloud applications, and network components. These tools assist in reconnaissance, scanning, fuzzing, exploitation, and reporting vulnerabilities.  

---

## 📌 Table of Contents  
- [Reconnaissance](#-reconnaissance)  
- [Subdomain Enumeration](#-subdomain-enumeration)  
- [Web Application Testing](#-web-application-testing)  
- [API Security Testing](#-api-security-testing)  
- [Mobile App Security Testing](#-mobile-app-security-testing)  
- [Cloud Security Testing](#-cloud-security-testing)  
- [Network Security Testing](#-network-security-testing)  
- [Vulnerability Scanners](#-vulnerability-scanners)  
- [Fuzzing Tools](#-fuzzing-tools)  
- [Exploitation Tools](#-exploitation-tools)  
- [Reporting & Automation](#-reporting--automation)  

---

## 🔍 Reconnaissance  

Tools for gathering public information about the target.  

- **[Amass](https://github.com/owasp-amass/amass)** - In-depth reconnaissance and DNS enumeration  
- **[Subfinder](https://github.com/projectdiscovery/subfinder)** - Passive subdomain discovery  
- **[Assetfinder](https://github.com/tomnomnom/assetfinder)** - Find related domains  
- **[Hakrawler](https://github.com/hakluke/hakrawler)** - Crawl web applications for endpoints  
- **[Gauplus](https://github.com/bp0lr/gauplus)** - Fetch URLs from various sources  
- **[Waybackurls](https://github.com/tomnomnom/waybackurls)** - Fetch URLs from the Wayback Machine  
- **[Katana](https://github.com/projectdiscovery/katana)** - Advanced web crawler  
- **[Findomain](https://github.com/Findomain/Findomain)** - Fast domain discovery  

---

## 🌐 Subdomain Enumeration  

Essential for mapping an application's attack surface.  

- **[Sublist3r](https://github.com/aboul3la/Sublist3r)** - Subdomain enumeration using multiple sources  
- **[Knockpy](https://github.com/guelfoweb/knock)** - Subdomain discovery using dictionary attack  
- **[Chaos](https://github.com/projectdiscovery/chaos-client)** - Find bug bounty subdomains from Chaos DB  

---

## 🛠 Web Application Testing  

Tools for testing security vulnerabilities in web applications.  

- **[Burp Suite](https://portswigger.net/burp)** - Web security testing framework  
- **[OWASP ZAP](https://www.zaproxy.org/)** - Open-source web application scanner  
- **[SQLmap](https://github.com/sqlmapproject/sqlmap)** - Automated SQL injection tool  
- **[XSStrike](https://github.com/s0md3v/XSStrike)** - Advanced XSS scanner  
- **[Nuclei](https://github.com/projectdiscovery/nuclei)** - Fast vulnerability scanner using custom templates  
- **[Kxss](https://github.com/Emoe/kxss)** - Detect cross-site scripting (XSS) vulnerabilities  
- **[CRLFuzz](https://github.com/dwisiswant0/crlfuzz)** - Detect CRLF injection vulnerabilities  

---

## 🔌 API Security Testing  

Tools for testing REST, GraphQL, and SOAP APIs.  

- **[Postman](https://www.postman.com/)** - API testing and security research  
- **[GraphQLmap](https://github.com/swisskyrepo/GraphQLmap)** - Automated GraphQL security testing  
- **[NoSQLMap](https://github.com/codingo/NoSQLMap)** - Detect and exploit NoSQL injection vulnerabilities  
- **[JWT_Tool](https://github.com/ticarpi/jwt_tool)** - Manipulate and test JWT tokens  
- **[Kiterunner](https://github.com/assetnote/kiterunner)** - Brute-force API endpoints  

---

## 📱 Mobile App Security Testing  

Tools for testing Android and iOS applications.  

- **[MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF)** - Mobile security testing framework  
- **[Frida](https://frida.re/)** - Dynamic instrumentation toolkit for runtime manipulation  
- **[Objection](https://github.com/sensepost/objection)** - Runtime mobile security assessment toolkit  
- **[APKTool](https://github.com/iBotPeaches/Apktool)** - Reverse engineer Android apps  
- **[Dex2Jar](https://github.com/pxb1988/dex2jar)** - Convert Android DEX files to JAR  

---

## ☁ Cloud Security Testing  

Tools for testing AWS, Azure, GCP, and other cloud platforms.  

- **[CloudBrute](https://github.com/0xsha/CloudBrute)** - Cloud asset discovery  
- **[Pacu](https://github.com/RhinoSecurityLabs/pacu)** - AWS penetration testing toolkit  
- **[CloudMapper](https://github.com/duo-labs/cloudmapper)** - Visualize cloud assets and permissions  
- **[ScoutSuite](https://github.com/nccgroup/ScoutSuite)** - Multi-cloud security auditing tool  

---

## 🌍 Network Security Testing  

Tools for assessing network security vulnerabilities.  

- **[Nmap](https://nmap.org/)** - Network scanning and fingerprinting  
- **[Masscan](https://github.com/robertdavidgraham/masscan)** - Fast network scanning  
- **[Shodan](https://www.shodan.io/)** - Internet-wide network reconnaissance  
- **[RustScan](https://github.com/RustScan/RustScan)** - Fast network port scanning  
- **[Zmap](https://github.com/zmap/zmap)** - Large-scale network scanner  

---

## 🔎 Vulnerability Scanners  

Automated tools for identifying vulnerabilities.  

- **[NucleiFuzzer](https://github.com/0xKayala/NucleiFuzzer)** - A Powerful Automation Tool for Web Vulnerability Scanning
- **[Nessus](https://www.tenable.com/products/nessus)** - Commercial vulnerability scanner
- **[OpenVAS](https://www.openvas.org/)** - Open-source vulnerability scanner  
- **[Nikto](https://github.com/sullo/nikto)** - Web server vulnerability scanner  
- **[WhatWeb](https://github.com/urbanadventurer/WhatWeb)** - Detect web technologies and vulnerabilities  

---

## 🧪 Fuzzing Tools  

Tools for fuzzing web applications and APIs.  

- **[ffuf](https://github.com/ffuf/ffuf)** - Fast web fuzzing  
- **[wfuzz](https://github.com/xmendez/wfuzz)** - Web application fuzzing  
- **[Dirsearch](https://github.com/maurosoria/dirsearch)** - Directory brute-forcing  
- **[Gobuster](https://github.com/OJ/gobuster)** - Directory and DNS brute-forcing  

---

# Red Teaming Engagements stages and Tools used within them

> A curated list of security tools for bug bounty hunters, penetration testers, and ethical hackers. These tools help in reconnaissance, exploitation, privilege escalation, and more.

## 🔍 Reconnaissance  

Tools for gathering information about the target.  

- **[Amass](https://github.com/owasp-amass/amass)** - Subdomain enumeration and DNS mapping  
- **[Subfinder](https://github.com/projectdiscovery/subfinder)** - Passive subdomain enumeration  
- **[Assetfinder](https://github.com/tomnomnom/assetfinder)** - Find related domains  
- **[Hakrawler](https://github.com/hakluke/hakrawler)** - Web crawling for endpoints  
- **[Gauplus](https://github.com/bp0lr/gauplus)** - Fetch URLs from multiple sources  
- **[Waybackurls](https://github.com/tomnomnom/waybackurls)** - Fetch URLs from the Wayback Machine  
- **[Katana](https://github.com/projectdiscovery/katana)** - Web crawler for web application mapping  

---

## 🎯 Initial Access  

Tools for gaining a foothold in a system.  

- **[Metasploit](https://github.com/rapid7/metasploit-framework)** - Exploitation framework  
- **[Routersploit](https://github.com/threat9/routersploit)** - Router and IoT exploitation  
- **[Evilginx2](https://github.com/kgretzky/evilginx2)** - Phishing and man-in-the-middle framework  

---

## 📤 Delivery  

Tools for delivering payloads to the target.  

- **[Bettercap](https://github.com/bettercap/bettercap)** - Network attack framework  
- **[Empire](https://github.com/EmpireProject/Empire)** - Post-exploitation framework  

---

## 📡 Command and Control (C2)  

Tools for establishing remote access and control.  

- **[Sliver](https://github.com/BishopFox/sliver)** - C2 framework for red teaming  
- **[Covenant](https://github.com/cobbr/Covenant)** - C2 framework with .NET payloads  

---

## 🔑 Credential Dumping  

Tools for extracting credentials from the system.  

- **[Mimikatz](https://github.com/gentilkiwi/mimikatz)** - Windows credential dumping  
- **[LaZagne](https://github.com/AlessandroZ/LaZagne)** - Extract stored credentials  

---

## 🚀 Privilege Escalation  

Tools for escalating privileges after gaining access.  

- **[LinPEAS](https://github.com/carlospolop/PEASS-ng/tree/master/linPEAS)** - Privilege Escalation for Linux  
- **[WinPEAS](https://github.com/carlospolop/PEASS-ng/tree/master/winPEAS)** - Privilege Escalation for Windows  
- **[BeRoot](https://github.com/AlessandroZ/BeRoot)** - Windows/Linux privilege escalation  

---

## 🛡 Defense Evasion  

Tools for bypassing security defenses.  

- **[BypassAV](https://github.com/TideSec/BypassAV)** - Tool for bypassing antivirus detection  
- **[Shellter](https://www.shellterproject.com/)** - AV evasion for shellcode injection  

---

## 📌 Persistence  

Tools for maintaining access to the system.  

- **[Sticky Keys Attack](https://www.hackingarticles.in/windows-privilege-escalation-using-sticky-keys/)** - Enable backdoor access on Windows  
- **[PowerSploit](https://github.com/PowerShellMafia/PowerSploit)** - PowerShell attack scripts  

---

## 🔄 Lateral Movement  

Tools for spreading through a network.  

- **[CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec)** - Network lateral movement  
- **[Impacket](https://github.com/SecureAuthCorp/impacket)** - Tools for Windows authentication and exploitation  

---

## 📤 Exfiltration  

Tools for extracting data from compromised systems.  

- **[Rclone](https://rclone.org/)** - Sync files to cloud storage  
- **[Metasploit’s Meterpreter](https://github.com/rapid7/metasploit-framework)** - File exfiltration module  

---

## 📢 Contributing  

If you have any additional tools to suggest, feel free to submit a pull request!  

---

## 📜 License  

This project is licensed under the [MIT License](LICENSE).
