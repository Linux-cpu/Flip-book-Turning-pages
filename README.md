📖 Jit Davindra Boutique — Flipbook Lookbook

An interactive, tactile digital lookbook for Jit Davindra Boutique — built with a realistic page-flip physics engine so browsing the catalog feels like holding a real printed booklet in your hands.

---

✨ Features

· Realistic page-turn physics powered by Turn.js with dynamic lighting, gradients, and heavy paper drop shadows.
· True touch drag support — grab any edge or corner of a page and play with it in real time.
· Single-page (portrait) mode — optimized for both mobile and desktop viewing.
· Cinematic spotlight background that makes the warm, textured paper pop.
· Authentic paper grain rendered via inline SVG noise + edge crease shading.
· Fully responsive — recalculates book size on window resize using ResizeObserver.
· Keyboard navigation — use ← and → arrow keys on desktop.
· Mobile-optimized — disables zoom/scroll fighting, respects safe-area insets, uses 100dvh.

---

🖼️ What's Inside

Page Content
1 Cover — "Har Dhaage vich khoobsurti"
2 Mint Green Phulkari — ₹4,500
3 Maroon Velvet Sharara — ₹6,200
4 Classic Silk Lehenga — ₹8,900
5 Golden Zari Detail — Custom Pricing
6 Royal Blue Kurta Set — ₹3,800
7 Heavily Embroidered Dupatta — ₹2,100
8 Pastel Palazzo Suit — ₹4,100
10 Thank You

---

🚀 Getting Started

1. Clone or create the folder

```bash
mkdir flipbook
cd flipbook
```

2. Create the file

```bash
nano index.html
```

Paste the full HTML from the script above, then save:

· Ctrl + O → Enter → Ctrl + X

3. Open it

Just double-click index.html, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit 👉 http://localhost:8000

---

📦 Uploading to GitHub

```bash
# inside the flipbook/ folder
git init
git add .
git commit -m "Initial commit: Jit Davindra Boutique flipbook"
git branch -M main
git remote add origin https://github.com/<your-username>/flipbook.git
git push -u origin main
```

🌐 Enable GitHub Pages (free hosting)

1. Go to Settings → Pages in your repo.
2. Under Source, pick Deploy from a branch.
3. Choose main branch, / (root) folder.
4. Save — your lookbook goes live at:

```
https://<your-username>.github.io/flipbook/
```

---

🛠️ Customization Tips

· Swap products → Replace the src on each <img> tag and edit the .product-title, .product-desc, and .product-price.
· Add pages → Duplicate a .page block and drop it before the closing </div> of #flipbook.
· Change accent color → Edit --accent in the :root CSS block.
· Change contact number → Update the text in Page 9.

---

📱 Contact

Jit Davindra Boutique
📞 for more information send message on telegram: @infernoaxe

"Har Dhaage vich khoobsurti" — Beauty in every thread.

---

📜 License

Personal project for Jit Davindra Boutique. Feel free to fork and adapt for your own catalog.

---

💡 Made with

· jQuery 3.7.1
· Turn.js 3
· A whole lot of CSS love for paper realism 🖋️
