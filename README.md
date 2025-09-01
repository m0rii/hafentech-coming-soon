# 🌐 HafenTech – Coming Soon

Minimal multilingual landing page for **HafenTech – Digitale Lösungen für kleine Unternehmen**.  
Includes **Impressum** and **Datenschutzerklärung** for German legal compliance.

---

## 🚀 Live Website
👉 [https://hafentech.de](https://hafentech.de)  
(also available via [www.hafentech.de](https://www.hafentech.de))

---

## ✨ Features
- **Multilingual**: German (default), English, فارسی (RTL supported)
- **Responsive design** with modern dark theme
- **Email notification form** (via [FormSubmit](https://formsubmit.co/))
- **Legal pages**: Impressum, Datenschutzerklärung
- Hosted free on **GitHub Pages** with HTTPS

---

## 📦 Project Structure
```
├── index.html          # Landing page (de/en/fa)
├── impressum.html      # Legal notice
├── datenschutz.html    # Privacy policy
├── CNAME               # Custom domain (hafentech.de)
└── README.md           # Project documentation
```

---

## 🛠️ Development

### Preview locally
Option 1 – open `index.html` in your browser.  
Option 2 – use VS Code + **Live Server** extension.  
Option 3 – run a local server:
```bash
# Python
python3 -m http.server 8080

# or Node.js
npx serve
```
Then open [http://localhost:8080](http://localhost:8080).

---

## 🚀 Deployment (GitHub Pages)

1. Push changes to `main`:
   ```bash
   git add .
   git commit -m "update site"
   git push origin main
   ```
2. Go to **GitHub → Settings → Pages**
   - Source: `Deploy from branch`
   - Branch: `main` (root folder)
3. Custom domain: `hafentech.de`
4. Enable **Enforce HTTPS** once DNS is verified.

---

## 🔄 Updating Content
- Edit `index.html` text or add translations.  
- Run locally to preview changes.  
- Commit & push to redeploy automatically.

---

## 📧 Contact
**HafenTech** – Digitale Lösungen für kleine Unternehmen  
📍 Sprützmoor 80, 22547 Hamburg  
✉️ [info@hafentech.de](mailto:info@hafentech.de)
