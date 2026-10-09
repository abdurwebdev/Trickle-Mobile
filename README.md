# 🚰 Trickle - Garden Pipe Puzzle Game

**Trickle** is a clean, minimal, and responsive HTML5 canvas puzzle game. The goal of the game is simple: rotate the pipe tiles to connect every branch to the central water source and water the entire garden!

---

## 📸 Features

- 🧩 **Procedurally Generated Puzzles:** Unlimited levels generated dynamically with increasing grid sizes and complexity.
- 📱 **Fully Responsive Layout:** Designed with a mobile-first approach, featuring smooth scaling, notch support (`safe-area-inset`), and viewport adaptation for portrait and landscape modes.
- 🎨 **Adaptive Styling:** Automatic Light/Dark mode support based on system settings.
- ♿ **Accessibility Support:** High-contrast grid highlights, touch and tap controls, keyboard navigation support (`Arrow keys`, `Space`, `Enter`), and reduced-motion mode compatibility.
- 💾 **Local Progress Saving:** Tracks your best level achieved automatically in `localStorage`.
- 💡 **Helpful Features:** In-game Hint system, Level Reset, and Fresh Layout generation.

---

## 🎮 How to Play

1. **Tap / Click:** Rotate any pipe tile 90 degrees clockwise.
2. **Right Click / Shift + Tap:** Rotate a tile counter-clockwise.
3. **Keyboard Controls:**
   - **Arrow Keys:** Navigate through tiles.
   - **Space / Enter:** Rotate the selected tile.
4. **Goal:** Connect all pipes starting from the yellow water source tap so that all end nodes (flowers) bloom with water.

---

## 📂 File Structure

```text
trickle/
├── index.html        # Main single-file game code (HTML + CSS + JavaScript)
├── manifest.json     # Web App Manifest for PWA and Play Store conversion
├── README.md         # Project documentation
└── icons/            # App icons (e.g., 192x192, 512x512 PNGs)
```

---

## 🚀 How to Run Locally

Since **Trickle** is built as a single, self-contained HTML file, running it is easy:

1. Clone or download this repository.
2. Open `index.html` directly in any modern web browser (Chrome, Safari, Firefox, Edge).

---

## 🌐 Deploying & Publishing to Google Play Store

### 1. Web Deployment
Deploy your repository to any static web hosting service:
- **Vercel:** Drag and drop your folder or import via Github.
- **GitHub Pages:** Enable Pages under Repository Settings > Pages.
- **Netlify:** Drag and drop the build folder.

### 2. Converting to Android App Bundle (`.aab`)
1. Ensure your site is live over `HTTPS`.
2. Visit [PWABuilder.com](https://www.pwabuilder.com/).
3. Paste your deployed web application URL.
4. Click **Package for Stores** and choose **Android**.
5. Download your generated Android App Bundle (`.aab`) and source files.
6. Upload the `.well-known/assetlinks.json` file from the package to your web server root.

### 3. Google Play Store Submission
1. Register for a [Google Play Console](https://play.google.com/console) account.
2. Create a new App listing and fill out the store details (Icons, Screenshots, Privacy Policy).
3. Upload the `.aab` file under **Production** or **Internal Testing**.
4. Submit for review!

---

## 🛠️ Built With

- **HTML5 Canvas API** for graphics and animations.
- **Vanilla JavaScript (ES6)** with zero external dependencies.
- **CSS3 Grid / Flexbox** with modern viewport features (`clamp()`, `dvh`, CSS custom properties).

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).