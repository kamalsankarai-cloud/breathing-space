# 🌿 Serene — Mindful Breathing Space

**Serene** is a modern, responsive Progressive Web Application (PWA) designed for deep physiological breathing exercises, stress regulation, and sleep aid. Built with pure HTML5, Tailwind CSS, WebGL/SVG animations, and the Web Audio API.

---

## ✨ Features

- 🫁 **Anatomical Lungs Visualizer**: Interactive 3D/SVG lung model with 5 lobes, bronchial tree, alveolar clusters, and dynamic oxygen flow streams.
- 🫧 **Minimal Zen Orb**: Liquid fill visualizer with percentage capacity readout and surface meniscus motion.
- 🎵 **Web Audio Sound & Music Studio**: Continuous procedural soundscapes (Zen 432Hz Om, Ocean Waves, Gentle Rain, Alpha Binaural Beats, Forest Breeze) and singing bowl / crystal bell / woodblock chimes.
- 🧘 **Science-Backed Rhythm Techniques**:
  - **Box Breathing (4-4-4-4)**: Focus & adrenaline regulation
  - **4-7-8 Sleep**: Vagus nerve activation & deep relaxation
  - **Coherent / Resonance (5.5-5.5)**: Heart Rate Variability (HRV) optimization
- 📊 **Day-Wise Session Log & Streak Tracking**: Track daily total practice time, cycle counts, mood check-ins, and active day streaks (stored locally with optional Firebase Firestore cloud sync).
- 📲 **PWA & Offline Ready**: Service worker caching and web manifest for installation on iOS, Android, macOS, and Windows.

---

## 🚀 How to Host on GitHub (GitHub Pages)

### Step 1: Initialize Git and Push to GitHub

Open your terminal or command prompt inside the project folder:

```bash
# 1. Initialize git repository
git init

# 2. Add all files and commit
git add .
git commit -m "Initial commit of Serene Mindful Breathing Space"

# 3. Rename branch to main
git branch -M main

# 4. Add your GitHub remote repository (replace with your repo URL)
git remote add origin https://github.com/YOUR_USERNAME/breathing-space.git

# 5. Push to GitHub
git push -u origin main
```

### Step 2: Enable GitHub Pages (Free Hosting)

1. Go to your repository page on GitHub: `https://github.com/YOUR_USERNAME/breathing-space`.
2. Click on **Settings** (top navigation tab).
3. Scroll down to the **Pages** section in the left sidebar menu under **Code and automation**.
4. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Select `main` branch and `/ (root)` folder.
5. Click **Save**.
6. GitHub will automatically build and publish your app in under a minute at:
   `https://YOUR_USERNAME.github.io/breathing-space/`

---

## 📂 File Structure

```text
├── index.html       # Single-page application UI, styles & Web Audio engine
├── manifest.json    # Web App Manifest for PWA installation
├── sw.js            # Service Worker for offline asset caching
├── favicon.svg      # Vector app icon for browsers & PWA launcher
├── .gitignore       # Git ignore configuration
└── README.md        # Documentation and deployment guide
```

---

## 🛠️ Local Development

Simply open `index.html` in any web browser, or serve it via a local HTTP server:

```bash
# Using Python:
python -m http.server 8000

# Using Node.js:
npx serve .
```

Then visit `http://localhost:8000`.

---

## 📄 License

MIT License — feel free to customize and share!
