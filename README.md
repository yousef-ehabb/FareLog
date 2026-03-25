# 🚕 InDriver Income Tracker

![Version](https://img.shields.io/badge/version-2.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![PWA Features](https://img.shields.io/badge/PWA-Supported-orange.svg)

A professional, offline-capable Progressive Web Application (PWA) specifically designed to help ride-sharing drivers (like InDriver, Uber, Lyft) track their daily shifts, income, and expenses with precision.

---

## ✨ Features

- **⚡ Offline-First Architecture**: Functions seamlessly without an internet connection using Service Workers.
- **⏱️ Live Shift Tracking**: Start/stop shifts with a persistent floating timer and live net tracking.
- **💰 Smart Fares & Expenses**: 
  - Quick-add fare chips (e.g., +30, +50, +100).
  - Categorized expenses (Fuel, Wash, Maintenance, Other).
- **📊 Advanced Analytics Dashboard**: 
  - Visual earnings breakdowns utilizing Chart.js.
  - Weekly and Monthly trend analysis.
  - Daily goal progress bars.
- **↩️ 5-Second Undo System**: Accidentally logged a fare? Instantly revert it with a non-intrusive toast notification.
- **💾 Auto-Save & Data Export**: Secure `localStorage` persistence. Export histories to universally accepted CSV or PDF formats.
- **🌙 Night-Optimized UI**: High-contrast, dark-mode styling utilizing sleek CSS variables and a "glassmorphism" aesthetic.

## 🛠 Tech Stack

- **Frontend Core**: HTML5, Vanilla JavaScript (ES6+), CSS3.
- **Architecture**: Modular structure (`/css`, `/js`, `/assets`), component-based state mutation.
- **Offline Capabilities**: Service Workers, Web App Manifest.
- **Visualization**: Chart.js (via CDN).
- **Typography & Icons**: Google Fonts (Inter), inline SVG iconography.

## 📂 Project Structure

```text
📦 IncomeApp
 ┣ 📂 assets/              # App icon & preview images
 ┣ 📂 css/
 ┃ ┗ 📜 style.css          # Modular, variable-driven stylesheets
 ┣ 📂 js/
 ┃ ┗ 📜 app.js             # Core logic, state management, UI controllers
 ┣ 📜 index.html           # Main application view & modal shells
 ┣ 📜 manifest.json        # PWA metadata
 ┣ 📜 service-worker.js    # Offline caching logic
 ┗ 📜 README.md
```

## 🚀 Installation & Usage

Because it's a PWA, installation is fast and doesn't require an app store.

### Desktop / Local Testing
1. Clone the repository: `git clone https://github.com/yousef-ehabb/IncomeApp.git`
2. Since modules and service workers require a secure context, serve the directory via a local web server:
   ```bash
   python -m http.server 8000
   # or
   npx serve .
   ```
3. Open `http://localhost:8000` in your browser.

### Mobile Installation (Android/iOS)
1. Host the application on a service like GitHub Pages, Vercel, or Netlify.
2. Navigate to your hosted URL via your mobile browser (Chrome/Safari).
3. **Android**: Tap the 3 dots in the top right -> **"Add to Home Screen"** or **"Install App"**.
4. **iOS**: Tap the Share icon at the bottom -> **"Add to Home Screen"**.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 
If you find a bug or want to suggest an improvement, please open an issue or submit a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
