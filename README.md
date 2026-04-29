# 🌌 Muse Studio: Pro Edition
> **The world's first 100% serverless, local-first professional DAW.**

![Status](https://img.shields.io/badge/Status-Live-emerald?style=for-the-badge)
![Tech](https://img.shields.io/badge/Engine-Tone.js-cyan?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-violet?style=for-the-badge)

Muse Studio is a high-performance Progressive Web App (PWA) designed for music and video production entirely within the browser. No servers, no subscriptions, and zero latency.

---

## 🚀 Key Features

| Feature | Description | Tech Stack |
| :--- | :--- | :--- |
| **Voice Lab Pro** | Studio-grade vocal DSP with Noise Gate, Compressor, and Air EQ. | Web Audio API / Tone.js |
| **Multitrack Mixer** | Hardware-accelerated 60FPS UI with real-time dBFS metering. | GPU / Tailwind CSS |
| **Local Rendering** | High-bitrate MP4 export with -14 LUFS normalization. | FFmpeg.wasm |
| **PWA V2** | Install as a native app on iOS, Android, or Desktop. | Service Workers |

---

## 🛠️ Installation & Setup

### Option 1: One-Click Launch
Simply open `index.html` in any modern browser (Chrome/Brave recommended).

### Option 2: PWA Installation (Mobile & Desktop)
1. Navigate to the live URL.
2. Click the **Install** icon in the address bar.
3. Muse Studio will now live in your app drawer and work **100% offline**.

---

## 🎨 Visual Architecture
The UI is built on a **Glassmorphism** design language, utilizing GPU-accelerated backdrop filters to maintain high performance during intensive audio processing.

### Performance Benchmarks
* **UI Refresh Rate:** 60 FPS (Locked)
* **Audio Latency:** ~2.1ms (Interactive Hint)
* **Render Speed:** Local RAM-based stitching via Virtual Disk.

---

## 🤝 Open Source Beats & Credits
Muse Studio supports importing CC0 and Public Domain assets.
- **SoundSafari CC0** (7k+ tracks)
- **Cymatics Free Packs**
- **YouTube Audio Library**

---

## 📜 License
This project is licensed under the MIT License - free for commercial use forever.

---
*Created by Brandon • Built for the future of serverless creativity.*
Since you've built this as a serverless, local-first app, you have three prime spots to host it for free. These platforms are built for PWAs and will give you a "native" feel once installed on a phone or desktop.
### 1. Netlify (The "Drag-and-Drop" King)
This is the fastest way if you don't want to mess with code repositories.
 * **How:** Go to Netlify Drop.
 * **The Move:** Drag your entire folder (containing index.html, service-worker.js, manifest.json, and all your cover_*.jpg images) into the box.
 * **Why:** It gives you a live URL in 5 seconds. You can even point a custom domain to it later.
### 2. GitHub Pages (The "Creator's" Choice)
If you want to keep your source code public and show off your dev skills, use GitHub.
 * **How:** Create a new repository (e.g., muse-studio), upload your files, and go to **Settings > Pages**.
 * **The Move:** Set the source to the "main" branch.
 * **Why:** It’s the industry standard for open-source projects. Your URL will look like username.github.io/muse-studio.
### 3. Vercel (The High-Performance Pro)
Vercel is optimized for speed, which is great for a heavy audio/video app like yours.
 * **How:** Connect your GitHub account to Vercel.
 * **The Move:** Select your repository and hit "Deploy."
 * **Why:** It has a global CDN, meaning the app will load fast whether someone is in Michigan or Tokyo.
### ⚠️ Crucial Step for the PWA
Once you post the code to any of these sites, **HTTPS is mandatory**. Luckily, all three of these platforms provide an SSL certificate (the little padlock icon) for free. Without HTTPS, your service-worker.js won't register, and the "Install App" feature won't work on phones.
**Which one are you leaning towards?** If you pick GitHub, I can walk you through the command-line steps to push it like a pro.

