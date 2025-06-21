# 🛡️ Cross‑Site Scripting (XSS) Resources

## ❓ What is XSS?
- **Cross‑Site Scripting (XSS)** overview — see OWASP page:  
  👉 [https://www.owasp.org/index.php/Cross-site_Scripting_(XSS)](https://www.owasp.org/index.php/Cross-site_Scripting_(XSS)) :contentReference[oaicite:0]{index=0}

---

## 📘 Prevention Cheat Sheets

- **XSS (Cross‑Site Scripting) Prevention Cheat Sheet** (OWASP)  
  👉 [https://www.owasp.org/index.php/XSS_(Cross_Site_Scripting)_Prevention_Cheat_Sheet] :contentReference[oaicite:1]{index=1}

- **DOM‑based XSS Prevention Cheat Sheet** (OWASP)  
  👉 [https://cheatsheetseries.owasp.org/cheatsheets/DOM_based_XSS_Prevention_Cheat_Sheet.html] :contentReference[oaicite:2]{index=2}

- **Veracode XSS Cheat Sheet**  
  👉 [https://www.veracode.com/security/xss](https://www.veracode.com/security/xss) :contentReference[oaicite:3]{index=3}

---

## 🔍 Testing Methodologies

- **Testing for Reflected XSS (OTG‑INPVAL‑001)** — OWASP WSTG  
  👉 [https://www.owasp.org/index.php/Testing_for_Reflected_Cross_site_scripting_(OTG-INPVAL-001)] :contentReference[oaicite:4]{index=4}

- **Testing for Stored XSS (OTG‑INPVAL‑002)** — OWASP WSTG  
  👉 [https://www.owasp.org/index.php/Testing_for_Stored_Cross_site_scripting_(OTG-INPVAL-002)] :contentReference[oaicite:5]{index=5}

- **Testing for DOM‑based XSS (OTG‑CLIENT‑001)** — OWASP WSTG  
  👉 [https://www.owasp.org/index.php/Testing_for_DOM-based_Cross_site_scripting_(OTG-CLIENT-001)] :contentReference[oaicite:6]{index=6}

---

## 🧠 Further Reading & References

- **DOM‑Based XSS** — in-depth OWASP article  
  👉 [https://www.owasp.org/index.php/DOM_Based_XSS](https://www.owasp.org/index.php/DOM_Based_XSS) :contentReference[oaicite:7]{index=7}

- **OWASP XSS Filter Evasion Cheat Sheet** — examples of bypass techniques  
  👉 [https://cheatsheetseries.owasp.org/cheatsheets/XSS_Filter_Evasion_Cheat_Sheet.html](https://cheatsheetseries.owasp.org/cheatsheets/XSS_Filter_Evasion_Cheat_Sheet.html) :contentReference[oaicite:8]{index=8}

---

## 📚 Recommended Books

- **XSS Attacks: Cross‑site Scripting Exploits and Defense**
- **XSS Cheat Sheet** (community or standalone guides)

---

## 📂 How to Use This Repo

1. Navigate through the OWASP & Veracode links for detailed XSS best practices.
2. Follow OWASP testing guides to assess for:
   - Reflected XSS
   - Stored XSS
   - DOM‑based XSS
3. Apply preventative techniques:
   - Contextual output encoding
   - Safe DOM methods (e.g., `textContent` instead of `innerHTML`)
   - Content Security Policy (CSP)
4. Leverage automated scans (e.g., Veracode Static Analysis, DAST) as explained in Veracode resources :contentReference[oaicite:9]{index=9}
5. Investigate recommended books for deeper coverage.

---

## ⚠️ Quick Reference Summary

| XSS Type     | Testing Guide                | Prevention Resource                                 |
|--------------|------------------------------|-----------------------------------------------------|
| Reflected    | OTG‑INPVAL‑001 (OWASP)       | OWASP XSS Prevention Cheat Sheet                    |
| Stored       | OTG‑INPVAL‑002 (OWASP)       | OWASP XSS Prevention Cheat Sheet                    |
| DOM‑Based    | OTG‑CLIENT‑001 (OWASP)       | DOM‑based XSS Prevention Cheat Sheet                |

---

### ✅ Additional Tips

- **Use safe DOM sinks** (`textContent`, `innerText`) to avoid script injection :contentReference[oaicite:10]{index=10}  
- **Enforce CSP headers** to restrict script execution sources :contentReference[oaicite:11]{index=11}  
- **Input validation & output encoding** are crucial across all contexts :contentReference[oaicite:12]{index=12}

---

Feel free to clone, extend with code snippets or sample payloads, or integrate CI testing workflows. Happy securing! 🎯
