# Creative Africa Rise 2026

**Youth Creative Arts Entrepreneurship Programme — Pan-African**

A comprehensive programme turning African youth into creative entrepreneurs across 8 art disciplines, delivered in partnership with Azerbaijan's leading creative institutions.

## 🌍 Live site

Once published via GitHub Pages, the site will be available at:
```
https://<your-username>.github.io/<your-repo-name>/
```

---

## 📋 Programme Overview

- **8 Creative Tracks** — Digital Art, DJ & Electronic Music, AI Tools, Video & Film, Game Design, Photography, Music Production, Fashion & Textiles
- **3 Formats** — 3-Month Sprint, 6-Month Ascent, Online Forever (permanent platform)
- **Azerbaijan Partners** — DJ Academy Baku · Baku Fashion Week · StockIn AZ (community, networks & expert teaching)
- **Prizes** — Equipment, international experiences and funds for Gold, Silver and Bronze winners in every track

---

## 🚀 Deploy to GitHub Pages

### Option A — Simplest (no build step required)

1. Create a new GitHub repository
2. Upload `index.html` to the root of the repository
3. Go to **Settings → Pages**
4. Under **Source**, select **Deploy from a branch**
5. Choose branch: `main` (or `master`) · folder: `/ (root)`
6. Click **Save**
7. Your site will be live at `https://<username>.github.io/<repo>/` within a few minutes

### Option B — GitHub CLI

```bash
git init
git add index.html README.md
git commit -m "Initial publish: Creative Africa Rise 2026"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```
Then enable Pages in repository Settings as described above.

---

## 📁 File Structure

```
/
├── index.html      ← Single-file site, fully self-contained
└── README.md       ← This file
```

The entire programme document is a **single self-contained HTML file** with:
- All CSS embedded in `<style>` tags
- All JavaScript embedded in `<script>` tags
- No external dependencies except Google Fonts (loaded via CDN)
- No build tools, frameworks or npm required

---

## ✏️ Updating Content

All content is in `index.html`. Key sections by ID:

| Section | Element ID |
|---|---|
| Hero | `s-hero` |
| Programme Overview | `s-overview` |
| AZ Partners | `s-partners` |
| 8 Creative Tracks | `s-tracks` |
| Programme Formats & Timelines | `s-formats` |
| Prizes | `s-prizes` |
| Budget | `s-budget` |

---

## 🤝 Partners

| Partner | Country | Role |
|---|---|---|
| DJ Academy Baku | 🇦🇿 Azerbaijan | DJ & Electronic Music curriculum, expert instructors, professional network |
| Baku Fashion Week | 🇦🇿 Azerbaijan | Fashion expertise, industry network, community connection |
| StockIn Fashion Community | 🇦🇿 Azerbaijan | Designer mentors, textile knowledge, alumni community |

---

*2026–2030 · Pan-African Creative Economy*
