
[README-parallax.md](https://github.com/user-attachments/files/29629755/README-parallax.md)
# Techfest 2026 · Welcome to the Simulated Paradigm — Parallax Scroll Edition

A full scroll-driven experience for Techfest, IIT Bombay itself, built around the festival's own tagline: "Welcome to the Simulated Paradigm."

> ⚠️ **Disclaimer:** This is an unofficial concept/portfolio design, not affiliated with or endorsed by Techfest or IIT Bombay. For official information and registration, visit [techfest.org](https://techfest.org/).

---

## 🔗 Live Demo

`https://<your-username>.github.io/<repo-name>/techfest-parallax.html`

*(Update this once GitHub Pages is enabled — see [Deployment](#-deployment) below.)*

---

## ✨ Features

- Six full-height scenes — Hero, Exhibition, Arena, Stage, Network, and a closing call to action
- Background, midground, and foreground layers moving at independent speeds as the page scrolls, powered by a single throttled scroll listener (no animation library)
- A glitch-styled hero headline over a starfield and a receding violet grid floor
- Nebula blobs drifting behind floating robotics icons for the International Exhibitions section
- Circuit-grid spotlights for the Arena's competitions
- A slow-orbiting ring system for the Network section, linking directly to the Campus Ambassador program
- Content written in the festival's real numbers — footfall, exhibitor counts, lecture history, network reach
- Scroll-triggered fade/rise reveals via `IntersectionObserver`, with full support for reduced-motion preferences

---

## 🛠️ Tech Stack

- **HTML5 / CSS3** — no build step, no framework
- **Vanilla JavaScript** — parallax engine (`requestAnimationFrame`-throttled scroll handler), scroll reveals
- **Google Fonts** — [Rajdhani](https://fonts.google.com/specimen/Rajdhani), [Inter](https://fonts.google.com/specimen/Inter), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)

---

## 📁 File Structure

```
.
├── techfest-parallax.html   # This page — parallax scroll festival experience
└── README.md
```

Fully self-contained — HTML, CSS, and JS in one file, nothing to build or bundle.

---

## 🖥️ Running Locally

No installation or dependencies required.

**Option 1 — just open it:**
Double-click `techfest-parallax.html`, or drag it into your browser.

**Option 2 — serve it (recommended, avoids some browser file-access restrictions):**
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
python3 -m http.server 8000
```
Then visit `http://localhost:8000/techfest-parallax.html`.

> Note: this page loads fonts from a CDN, so an internet connection is needed even when running locally.

---

## 🚀 Deployment

To publish this on GitHub Pages:

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under "Branch," select `main` and `/ (root)`, then **Save**
4. Your page will be live at `https://<your-username>.github.io/<repo-name>/techfest-parallax.html`

*(Optional: rename the file to `index.html` if you want it at the repo root.)*

---

## 📝 Notes on Content

Program figures (footfall, exhibitor counts, lecture history, network size, etc.) are drawn from Techfest's publicly published materials at the time of writing and may change with each edition — check `techfest.org` for current figures before using this content anywhere official.

---

## 🙏 Credits

- Techfest branding, name, and program facts — [Techfest, IIT Bombay](https://techfest.org/)
- Typefaces — [Google Fonts](https://fonts.google.com/)

---

## 📄 License

Concept/portfolio project — free to reference or fork for learning purposes. Not for use as an official Techfest property.

---

## 👤 Author

**Gaurav Shrikant Khole**
[GitHub](https://github.com/Gaurav-08-07) · [LinkedIn](https://linkedin.com/in/gaurav-shrikant-khole-616b8b334)
