# Deployment Guide – Rainwater Convention Website

This guide explains how to run the Rainwater Convention website locally or host it using GitHub Pages.

---

## 1️⃣ Run the Website Locally (VS Code + Live Server)

Follow these steps:

1. Clone or download the repository  
   ```bash
   git clone https://github.com/marufa-akhter/rainwater-convention.git
   ```

2. Open the folder in **VS Code**

3. Install the **Live Server** extension (if not installed already)

4. Right-click on `home.html`  
   → Select **"Open with Live Server"**

5. Your website will automatically open at:  
   ```
   http://127.0.0.1:5500/home.html
   ```

---

## 2️⃣ Deploy Using GitHub Pages (Live Hosting)

1. Open your GitHub repository  
2. Go to **Settings → Pages**  
3. Under “Source”, select:
   - Branch: **main**
   - Folder: **/root**
4. Click **Save**

Your website will be available at:  
🔗 https://marufa-akhter.github.io/rainwater-convention/

---

## 3️⃣ UI/UX Design Prototype

The design prototype used for planning the layout & UI:

👉 https://www.figma.com/design/8IauGu6umNHXmZnxZ6Nd9S/Rain_Water?node-id=0-1&t=P7Zse23FvUCPgNNL-1
---

## Notes

- No backend is used — all data is saved in **localStorage**.
- Keep all files together in the same folder for proper functioning.
- Admin page automatically loads saved registrations from the browser.


   
