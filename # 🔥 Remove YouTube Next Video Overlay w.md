# 🔥 Remove YouTube Next Video Overlay with uBlock Origin

YouTube shows annoying **"Next Video" end screen overlays** even when annotations are disabled. This repo provides a simple uBlock Origin filter to completely remove them.

## ❓ Why This Exists

Even if you disable **annotations** in YouTube settings, you'll still see:

- Suggested video tiles at the end of videos
- Floating cards
- "Watch next" pop-ups
- Overlay distractions that hurt the viewing experience

## ✅ Solution: Use uBlock Origin Filters

If you're using [uBlock Origin](https://github.com/gorhill/uBlock), you can block these elements directly.

### 📋 Instructions

1. Click the **uBlock Origin** icon in your browser.
2. Open the **Dashboard** (⚙️ gear icon).
3. Go to the **"My filters"** tab.
4. Paste the following custom filters:

   ```plaintext
   www.youtube.com##.ytp-ce-element
   www.youtube.com##.ytp-endscreen-content
   www.youtube.com##.ytp-show-tiles
   www.youtube.com##.ytp-cards-teaser