# SkyRise Future - Launch Countdown Landing Page

This folder contains the standalone launch countdown landing page for **SkyRise Future**. It is built as a single, ultra-lightweight static page (`index.html`) to make hosting it on Vercel simple and instant with zero configurations.

---

## ⚡ How to Deploy on Vercel (Zero Configuration)
Aap is folder ko Vercel pr 2 tareeqon se live kar sakte hain:

### Option 1: Vercel Dashboard Drag & Drop (Easiest & Fastest)
1. Go to the [Vercel Dashboard](https://vercel.com/dashboard) and log in.
2. Click on **Add New** -> **Project**.
3. Scroll down to the bottom where it says **"Drag and drop a folder to deploy it"**.
4. Drag and drop the `skyrise-countdown` folder directly into the box.
5. Vercel will instantly upload it and give you a live link in under 10 seconds!

### Option 2: GitHub Repository (Recommended for custom domains)
1. Create a new repository on your GitHub account (e.g. named `skyrise-launch`).
2. Initialize git inside this `skyrise-countdown` folder:
   ```bash
   git init
   git add .
   git commit -m "initial release"
   git branch -M main
   git remote add origin YOUR_GITHUB_REPO_URL
   git push -u origin main
   ```
3. Go to [Vercel Dashboard](https://vercel.com/dashboard), click **Add New** -> **Project**, select your GitHub repository, and click **Deploy**.
4. Any future edits you make to `index.html` will automatically update live on Vercel when you push to GitHub!

---

## 🚀 Features Included:
- **Client-side 24h timer**: Each user visiting the site will get their own 24-hour countdown initialized upon their first open (persisted in browser's local storage).
- **Web Audio ticking**: A realistic mechanical sound plays every second with a premium mute/unmute button.
- **Dynamic Transition**: When the timer finishes, it instantly shifts layout to show "SkyRise Future is Live Now" with direct CTA buttons to your main platform.
- **CSS Animations**: Floating bubbles drifting upwards, morphing backgrounds, glowing rings, and pulsing colons.
- **Auto Dark/Light Theme**: Adapts to user's system preferences automatically.
