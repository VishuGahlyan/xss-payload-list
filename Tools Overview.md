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
 ```
     git clone https://github.com/ethicalhackeragnidhra/BruteXSS
     cd BruteXSS
     python3 brutexss.py -u http://target.com/page
 ```
### 2. [BruteXSS Terminal](https://github.com/ethicalhackeragnidhra/BruteXSS)

**Description:**  
BruteXSS GUI ek graphical user interface (GUI) version hai BruteXSS tool ka, jo users ko ek visual interface provide karta hai XSS vulnerabilities ko detect karne ke liye.

**Features:**  
- Graphical user interface  
- Simplified XSS vulnerability detection  
- Cross-platform support  

**Installation:**  
    ```bash
     git clone https://github.com/rajeshmajumdar/BruteXSS
     cd BruteXSS
     python3 brutexss.py -u http://target.com/page
    ``

### 5. [XSSer](https://github.com/epsylon/xsser)

**Description:**  
XSSer ek automatic framework hai jo XSS vulnerabilities ko detect, exploit, aur report karta hai web-based applications mein. Yeh various injection techniques aur GTK+ interface ko support karta hai.

**Features:**  
- Automated vectors (~1300)  
- Different injections: XST, XSS, XSA, XSR, DOM, DCP, Induced  
- GTK+ Interface  
- Wizard helper  
- Exploiting methods  
- Geomapping  
- HTML5 vectors  
- Encoding bypassers: String.FromCharCode, Unicode, Decimal, Hexadecimal  
- Special final injections: onMouseMove(), Iframes  
- Different spoofing methods  
- Anti-antiXSS/IDS rules  

**Installation:**  
  ```
     git clone https://github.com/epsylon/xsser
     cd xsser
     python3 xsser.py -u http://target.com/page
  ```

### 6. [xsscrapy](https://github.com/DanMcInerney/xsscrapy)

**Description:**  
xsscrapy ek fast aur thorough XSS aur SQL injection spider hai. Yeh website ko crawl karta hai aur har link ko XSS aur kuch SQL injection vulnerabilities ke liye test karta hai.

**Features:**  
- Crawl aur test all links  
- Detects XSS aur SQL injection vulnerabilities  
- Supports login aur cookies  
- Configurable connection limits aur rate limiting  

**Installation:**  
  ```
    git clone https://github.com/DanMcInerney/xsscrapy
    cd xsscrapy
    python3 xsscrapy.py -u http://target.com
 ```
 
### 7. [Cyclops](https://github.com/v8blink/Chromium-based-XSS-Taint-Tracking)

**Description:**  
Cyclops ek web browser hai jisme XSS detection features hain. Yeh taint tracking ka use karke XSS vulnerabilities ko detect karta hai web applications mein.

**Features:**  
- Chromium-based browser  
- XSS detection using taint tracking  
- Open-source aur customizable  

**Installation:**  
- Download the latest release from [https://github.com/v8blink/Chromium-based-XSS-Taint-Tracking/releases](https://github.com/v8blink/Chromium-based-XSS-Taint-Tracking/releases)  
- Follow the installation instructions provided in the repository  

### 8. [XSS-FINDER](https://github.com/capture0x/XSS-FINDER)

**Description:**  
XSS-FINDER ek exceptional open-source security tool hai jo Cross-Site Scripting (XSS) vulnerabilities ko detect karta hai zero false positives ke saath. Yeh tool geckodriver ke saath kaam karta hai aur jab screen par alert aata hai, tab yeh aapko successful payload ke baare mein notify karta hai.

**Features:**  
- Zero false positives  
- Geckodriver ke saath kaam karta hai  
- Screen par alert hone par notification deta hai  

**Installation:**  
``````
  git clone https://github.com/capture0x/XSS-FINDER/
  cd XSS-FINDER
  bash aa.sh
  pip3 install -r requirements.txt
  chmod -R 755 xss.py
  python3 xss.py
 ``````

*Yeh tools aapko web applications mein XSS vulnerabilities ko detect karne mein madad karenge. Har tool ki apni unique features hain, jo aapke specific requirements ke hisaab se useful ho sakte hain.*
