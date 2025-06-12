# 🔥 XSS LABS - Enhanced UI

A modern, interactive playground to practice and understand various types of **Cross-Site Scripting (XSS)** vulnerabilities. This lab is designed with a sleek cyberpunk-inspired UI to make learning web security more immersive and engaging.

🌐 **Live Demo:**  
👉 [XSS-LAB:01](https://povzayd.github.io/XSS-LABS/LABS/lab1.html)

---

## 🚀 Features

- 🧪 **Reflected XSS** – via the `search` query parameter.
- 💾 **Stored XSS** – via a local comment system backed by `localStorage`.
- 🔍 **DOM-based XSS** – using URL `#hash` injection for DOM manipulation.
- 🎉 **Custom `xssSuccess()` Handler** – visually stylish toast appears instead of basic `alert()`.

---

## ⚠️ Disclaimer

> This project is **strictly for educational purposes** and must **not** be hosted on any production or public-facing systems.  
> Always practice ethical hacking and test only in safe, controlled environments.

---

## 📘 How to Use

1. **Visit the Live Page**  
   👉 [XSS-LAB:01](https://povzayd.github.io/XSS-LABS/LABS/lab1.html)

2. **Try Input-Based XSS Attacks**

   - Reflected XSS:
     ```
     ?search=<script>alert("XSS")</script>
     ```

   - Stored XSS:
     ```
     <img src=x onerror=alert("XSS")>
     ```

   - DOM-based XSS:
     ```
     #<img src=x onerror=alert("XSS")>
     ```

3. **Watch for the Toast Notification**  
   Successfully triggering `alert("XSS")` will show a glowing "🎉 XSS Triggered Successfully!" toast.

---


## 📈 Roadmap

✅ **Current Lab:**

* Reflected, Stored, and DOM-based XSS demos.                                                                                     
Access Now : [XSS-LAB:01](https://povzayd.github.io/XSS-LABS/LABS/lab1.html)

🧪 **Coming Soon:**

* CSP bypass labs
* Polyglot payload practice
* XSS via iframe injections
* Advanced filter evasion labs
* Real-world vulnerable app simulations

Stay tuned 🐢 
---
---
