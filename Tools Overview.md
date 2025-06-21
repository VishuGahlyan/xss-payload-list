# XSS Vulnerability Scanner Tools
Yeh tools penetration testing, bug bounty hunting aur web application security audits mein kaafi useful hain.

## 🔧 Tools Overview

### 1. [XSStrike](https://github.com/s0md3v/XSStrike)
- **Description:** Python-based advanced XSS scanner jo reflected, DOM aur blind XSS vulnerabilities detect karta hai. Isme intelligent payload generation, context analysis, fuzzing engine, WAF fingerprinting & evasion features hain.
- **Features:**
  - Reflected aur DOM XSS scanning
  - Multi-threaded crawling
  - Context analysis
  - Configurable core
  - WAF detection & evasion
  - Outdated JS lib scanning
  - Intelligent payload generator
  - Handmade HTML & JavaScript parser
  - Powerful fuzzing engine
  - Blind XSS support
  - Highly researched workflow
  - Complete HTTP support
  - Bruteforce payloads from a file
  - Powered by Photon, Zetanize aur Arjun
  - Payload encoding
- **Installation:**
  ```bash
  git clone https://github.com/s0md3v/XSStrike
  cd XSStrike
  pip3 install -r requirements.txt
  python3 xsstrike.py -u http://target.com/page

### 2. [BruteXSS Terminal](https://github.com/ethicalhackeragnidhra/BruteXSS)

**Description:**  
BruteXSS ek Python-based terminal tool hai jo Cross-Site Scripting (XSS) vulnerabilities ko brute force method se detect karta hai. Yeh tool GET aur POST requests ko handle karta hai, aur specified wordlist se payloads inject karke parameters ko test karta hai.

**Features:**  
- GET aur POST requests dono ko support karta hai  
- Custom wordlist se payload injection  
- User-friendly terminal interface  
- Accurate scanning with minimal false positives  
- Lightweight aur fast execution  

**Installation:**  
```bash
git clone https://github.com/ethicalhackeragnidhra/BruteXSS
cd BruteXSS
python3 brutexss.py -u http://target.com/page
