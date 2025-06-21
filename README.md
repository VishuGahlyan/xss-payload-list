# xss-payload-list
Cross Site Scripting ( XSS ) Vulnerability Payload List
## 🔍 Overview :

**Cross‑Site Scripting (XSS)** attacks ek tarah ka injection attack hai, jisme attacker malicious scripts ko inject karke ek benign aur trusted website ko compromise kar leta hai. XSS tab hota hai jab attacker web application ka use karke malicious code (mostly browser-side JavaScript) dusre end user ke browser tak bhej deta hai. Ye vulnerability tab exploit hoti hai jab web app user ka input bina validation ya encoding ke output me use kar deti hai—aur ye flaw kaafi common hai. :contentReference[oaicite:0]{index=0}

Attack ka mechanism kuch is tarah ka hai:  
- Attacker XSS ke zariye khatarnaak script bhejta hai unsuspecting user ke browser me.  
- Browser is script ko trusted source (web app) se aane wale code ki tarah samajh leta hai, aur execute kar deta hai.  
- Script browser me store cookies, session tokens, ya sensitive information access kar sakta hai.  
- Ye script HTML page ka content bhi modify (rewrite) kar sakta hai. :contentReference[oaicite:1]{index=1}

Zyada jaankari chahiye XSS ke alag-alag types ke baare me? “Types of Cross‑Site Scripting” section dekh sakte ho.
