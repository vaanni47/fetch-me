# fetch.me
> A minimalist, privacy-focused personal web archive.

`fetch.me` is a lightweight static site built with an emphasis on speed, clean typography, and subtle user engagement. Inspired by the "brutalist" web design movement.

---

### 🛠 Tech Stack
* **Frontend:** Semantic HTML5 & CSS3 (Custom Properties)
* **Scripting:** Vanilla JavaScript (ES6+)
* **Architecture:** Static Site (No-JS fallback supported)
* **Hosting:** GitHub Pages
* **License:** MIT

### 📦 Databases & Backend
* **Database:** None (Zero-database architecture for maximum security and $O(1)$ load times).
* **Backend:** Serverless. All content is served as static assets via GitHub's global CDN.

### ✨ Key Features
* **Dynamic Visibility Logic:** Uses the browser's `Visibility API` to change the tab title and favicon when the user switches contexts (the "Instagram/Notification" trick).
* **Terminal Aesthetic:** Monospace-first design with a blinking command-line cursor effect.
* **Privacy by Design:** Zero tracking scripts, zero cookies, and zero third-party fonts.
* **Responsive:** Fully fluid layout that adapts to mobile, tablet, and ultra-wide displays.

---

### 🚀 Local Development
1. Clone the repo:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/fetch-me.git](https://github.com/YOUR_USERNAME/fetch-me.git)
