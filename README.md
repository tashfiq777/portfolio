# Tashfiqur Rahman — Engineering Portfolio

## Folder Structure
- `index.html` — Complete responsive portfolio website (HTML, CSS, and JavaScript).
- `assets/` — All 19 optimized engineering screenshots and portrait photo.

## How to Edit Your Information
1. Open `index.html` in VS Code (or any code editor).
2. **Personal info, hero text, about, skills, education & contact links:** Edit the corresponding HTML sections (`#top`, `#about`, `#skills`, `#journey`, `#contact`).
3. **Projects & case studies:** Scroll to `const PORTFOLIO_DATA` inside the `<script>` tag near the bottom of `index.html`. Every project's title, metrics, tools, gallery images, captions, and validation table live in one clean JavaScript object.
4. **Adding new images:** Drop new `.jpg`/`.png` files into `assets/` and reference them as `assets/your_image.jpg` inside `PORTFOLIO_DATA`.

## How to Run Locally
- Double-click `index.html` to open directly in any modern browser, or run `python3 -m http.server 8000` in this folder and visit `http://localhost:8000`.

## How to Deploy for Free (2 Minutes)
- **GitHub Pages:** Create a repo (e.g., `tashfiqdevs.github.io`), upload `index.html` and `assets/`, then enable GitHub Pages in **Settings → Pages → Deploy from branch (`main`)**.
- **Netlify / Vercel:** Drag and drop this entire folder onto [app.netlify.com/drop](https://app.netlify.com/drop) or import the GitHub repo on Vercel.
