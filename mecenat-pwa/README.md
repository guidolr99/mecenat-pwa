# Mecenat PWA

## Folder structure
```
mecenat-pwa/
├── index.html        ← Main app (edit this)
├── manifest.json     ← PWA config
├── sw.js             ← Service worker (offline support)
├── icons/            ← App icons (auto-generated)
│   ├── icon-16.png
│   ├── icon-32.png
│   ├── icon-180.png  ← Apple Touch Icon
│   ├── icon-192.png
│   └── icon-512.png
└── video.mp4         ← ADD YOUR VIDEO HERE
```

## ➕ Adding your video

1. Drop your video file (e.g. `video.mp4`) into the `mecenat-pwa/` folder
2. Open `index.html`, find this line:
   ```html
   <!-- Add your video source here: <source src="video.mp4" type="video/mp4"> -->
   ```
3. Uncomment/change it to:
   ```html
   <source src="video.mp4" type="video/mp4">
   ```

## 🚀 Deploy to Vercel (free, takes 2 min)

1. Go to https://vercel.com and sign up (free)
2. Install Vercel CLI: `npm i -g vercel`
3. In your terminal, navigate to this folder:
   ```
   cd mecenat-pwa
   vercel
   ```
4. Follow the prompts — it will give you a live URL like `https://mecenat-pwa.vercel.app`

### OR drag & drop (even easier):
1. Go to https://vercel.com/new
2. Drag the entire `mecenat-pwa` folder onto the page
3. Done! You get a URL instantly.

## 📱 Adding to Home Screen

### iPhone (Safari):
1. Open your Vercel URL in Safari
2. Tap the Share button (box with arrow)
3. Scroll down → tap "Add to Home Screen"
4. Tap "Add"

### Android (Chrome):
1. Open your Vercel URL in Chrome
2. Tap the 3-dot menu
3. Tap "Add to Home screen"
4. OR tap the install banner that appears automatically

The app will open with the Mecenat splash screen, just like a native app!
