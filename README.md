# 🕵️ **A-to-Z Bug Bounty Hunting Tools** [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools used by Bug Bounty hunters and security researchers for testing web applications, APIs, mobile apps, cloud applications, and network infrastructure. These tools assist in reconnaissance, scanning, fuzzing, exploitation, and reporting vulnerabilities.  

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
- **[Assetfinder](https://github.com/tomnomnom/assetfinder)** - Find related domains  
- **[Hakrawler](https://github.com/hakluke/hakrawler)** - Crawl web applications for endpoints  
- **[Gauplus](https://github.com/bp0lr/gauplus)** - Fetch URLs from various sources  
- **[Waybackurls](https://github.com/tomnomnom/waybackurls)** - Fetch URLs from the Wayback Machine  
- **[Katana](https://github.com/projectdiscovery/katana)** - Advanced web crawler  
- **[Findomain](https://github.com/Findomain/Findomain)** - Fast domain discovery  

---

## 🌐 Subdomain Enumeration  

Essential for mapping an application's attack surface.  

- **[Subfinder](https://github.com/projectdiscovery/subfinder)** - Passive subdomain discovery
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

## 💥 Exploitation Tools  

Tools for exploiting discovered vulnerabilities.  

- **[Commix](https://github.com/commixproject/commix)** - Automated All-in-One OS Command Injection Exploitation Tool
- **[Metasploit](https://github.com/rapid7/metasploit-framework)** - Exploitation framework  
- **[Xsploit](https://github.com/BlackArch/blackarch/tree/master/exploits/xsploit)** - Exploit automation  
- **[RouterSploit](https://github.com/threat9/routersploit)** - Exploiting routers and IoT devices  

---

## 📋 Reporting & Automation  

Tools for automating recon and reporting vulnerabilities.  

- **[Bugcrowd Templates](https://github.com/bugcrowd/vulnerability-rating-taxonomy)** - Reporting templates  
- **[HackerOne Templates](https://github.com/Hacker0x01/hacker101)** - Reporting guidelines  
- **[ReconFTW](https://github.com/six2dez/reconftw)** - Automated recon tool  
- **[BountyIt](https://github.com/bassammaged/BountyIt)** - Bug bounty automation  

---

## 📢 Contributing  

If you have any additional tools to suggest, feel free to submit a pull request!  

---

## 📜 License  

This project is licensed under the [MIT License](LICENSE).
