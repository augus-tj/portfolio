# Augustine's Portfolio

A personal portfolio website converted from Flutter/Dart to pure HTML/CSS/JS for GitHub Pages deployment.

## 🚀 Deploy to GitHub Pages

1. Create a new repo on GitHub (e.g. `augustinejulian21.github.io` for a user page, or `portfolio` for a project page)
2. Upload all files in this folder to the repo
3. Go to **Settings → Pages → Source → main branch / root**
4. Your site will be live at `https://augustinejulian21.github.io`

## 📁 File Structure

```
portfolio/
├── index.html          ← Main portfolio page
├── know-me-more.html   ← Win98 easter egg page
├── assets/
│   └── duitnowqr.png   ← Add your DuitNow QR image here
└── README.md
```

## ✏️ Customisation Checklist

### index.html
- [ ] Update **skills array** with your real Credly badge image URLs and cert names
- [ ] Update **projects array** with your real GitHub links and project descriptions
- [ ] Replace placeholder project GitHub/demo URLs

### know-me-more.html
- [ ] Add `assets/duitnowqr.png` — your actual DuitNow QR image
- [ ] The rickroll plays via YouTube embed (no video file needed)

### Both files
- [ ] Replace `augustinejulian21` with your real GitHub username if different
- [ ] All contact links (WhatsApp, LinkedIn, email) are already set from your original code

## 🎨 What was improved

- **Rickroll** now uses YouTube embed — no need to host a video file
- **Win98 icons** load from a public CDN with emoji fallbacks if they fail
- **Chaos popups** have varied messages and are dismissible one-by-one or all at once
- **Draggable windows** on the Win98 page with proper z-index stacking
- **Mobile navbar** fixed (original Flutter code had a bug where all mobile nav items scrolled to `aboutKey`)
- **Scroll-triggered fade-in** animations instead of all-at-once
- **Credly badge images** load directly from Credly CDN — no local assets needed
- **About text** lightly polished for professional tone
- **GitHub + Credly** contact links added to the contact section
