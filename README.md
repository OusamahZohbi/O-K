# 💌 Eid Gift Website — Ousamah & Klementina

A romantic multi-page website built as an Eid gift for Klementina.

---

## 📁 File Structure

```
eid-gift/
├── index.html       ← Home / Welcome page
├── story.html       ← Our Story (timeline)
├── letters.html     ← Love Letters
├── reasons.html     ← Why I Love You
├── moments.html     ← Favourite Moments + Photo Grid
├── dreams.html      ← Future Dreams & Wishes
├── css/
│   └── style.css    ← All styles
├── js/
│   └── main.js      ← Animations & nav
└── README.md
```

---

## ✏️ How to Personalize

### 1. Fill in Your Stories
Open each HTML file and replace the placeholder text with your real memories.
Look for comments or descriptive placeholder paragraphs — they guide you on what to write.

### 2. Add Your Photos (moments.html)
In `moments.html`, find the `.photo-grid` section. Replace each placeholder div like this:

```html
<!-- BEFORE (placeholder) -->
<div class="photo-slot"><span>📷</span>Add a photo here</div>

<!-- AFTER (with your photo) -->
<div class="photo-slot">
  <img src="images/our-photo.jpg" alt="A memory">
</div>
```

Create an `images/` folder in the project root and put your photos there.

### 3. Update the Year
The footer says "Eid 2025" — update this if needed in all HTML files.

---

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `eid-gift`)
2. Push all files to the `main` branch
3. Go to **Settings → Pages**
4. Under **Source**, select `main` branch and `/ (root)`
5. Click **Save**
6. Your site will be live at: `https://yourusername.github.io/eid-gift`

That's it! Share the link with Klementina. 🌙

---

## 🌸 Tips

- The site works on mobile — navigation collapses into a menu
- All animations are CSS/JS — no libraries needed
- Google Fonts are loaded from CDN (requires internet connection)
- To make it work offline too, download the fonts and host them locally

---

*Made with love, for Klementina. Eid Mubarak. 💌*
