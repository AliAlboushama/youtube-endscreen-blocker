# 🛑 YouTube Endscreen Blocker with uBlock Origin

Tired of YouTube pushing **"Next Video" overlays** even when annotations are turned off? This simple solution uses **uBlock Origin** to block those annoying end screen elements once and for all.

---

## 🔍 Why Use This?

Even after disabling annotations in YouTube settings, the platform still forces:

- Endscreen video tiles  
- "Watch next" pop-ups  
- Floating cards and teasers  
- Distracting overlays that hurt the viewing experience

This repo provides a clean way to block them using uBlock Origin.

---

## ✅ What It Blocks

- `ytp-ce-element` – suggested video cards  
- `ytp-endscreen-content` – end screen overlays  
- `ytp-show-tiles` – YouTube tiles shown after video  
- `ytp-cards-teaser` – teaser boxes that float up mid-video

---

## 📋 How to Use

1. Make sure you have [uBlock Origin](https://github.com/gorhill/uBlock) installed.
2. Click the **uBlock Origin** icon in your browser toolbar.
3. Open the **Dashboard** (⚙️ gear icon).
4. Go to the **“My filters”** tab.
5. Open the [`filters.txt`](https://github.com/AliAlboushama/youtube-endscreen-blocker/blob/main/filters.txt) file from this repository.
6. Copy all the filters inside it.
7. Paste them into your **“My filters”** section in uBlock.
8. Click **“Apply changes.”**

Done! YouTube’s endscreen clutter should now be gone.

---

## 📁 File Overview

- [`filters.txt`](https://github.com/AliAlboushama/youtube-endscreen-blocker/blob/main/filters.txt) – Contains all the necessary uBlock filters.
- `README.md` – This guide.

---

## 🛠️ Troubleshooting

- If filters stop working, YouTube may have updated class names.
- Check this repo for updates or submit a fix via Pull Request.

---

> ✨ Cleaner videos. No interruptions. Enjoy YouTube the way it should be!