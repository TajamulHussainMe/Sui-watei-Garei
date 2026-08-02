# BreadBiz — Installable Web App (PWA)

This folder turns your BreadBiz app into something that **installs on Android like a real app** —
home screen icon, full screen, works offline — with **no Play Store and no APK build needed**.

## Files in this folder
- `index.html` — the whole app (Owner / Delivery Boy / Customer views)
- `manifest.json` — tells Android it's an installable app
- `service-worker.js` — makes it work offline after first load
- `icons/icon-192.png`, `icons/icon-512.png` — app icons

## Step 1 — Put it online (pick ONE, both are free, no signup needed for the first)

### Option A: Netlify Drop (fastest — 30 seconds)
1. Go to **https://app.netlify.com/drop** on your computer
2. Drag this whole `breadbiz-pwa` folder onto the page
3. You'll instantly get a live link like `https://random-name-123.netlify.app`
4. Done — that link is your live app

### Option B: GitHub Pages (if you already use GitHub)
1. Create a new repository, upload these files
2. Go to Settings → Pages → set source to your main branch
3. Your app will be live at `https://yourusername.github.io/reponame`

## Step 2 — Install it on your Android phone
1. Open the live link in **Chrome** on your Android phone
2. Tap the **⋮ menu** (top right) → **"Add to Home screen"** / **"Install app"**
3. Confirm — the BreadBiz icon now appears on your home screen like any other app
4. Open it from the home screen — it runs full screen, no browser bar, works offline

## Step 3 — Share with your delivery boys / customers
Just send them the same link (e.g. via WhatsApp) — they tap it, install it the same way,
and pick their role (Owner / Delivery Boy / Customer) from the first screen.

---

## If you specifically want a `.apk` file later
Once this is live and working, hand the link to any Android developer (or use
**median.co** or **appmysite.com**, ~₹800–2,000) and ask them to "wrap this PWA URL into an APK."
This takes them minutes since all the hard work (the actual app) is already done.
