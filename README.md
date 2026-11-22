# Sculpt Me — Nourish & Glow MVP v0.9

A static, single-page HTML app. No npm install or build command needed.

## Deploy from a Mac (Vercel web dashboard)

1. Unzip `sculpt-me-vercel.zip`.
2. Go to https://vercel.com/new and sign in.
3. For direct drag-and-drop deployment, use Vercel's deploy/upload interface if available in your account; otherwise create a GitHub repository with the **contents** of this folder (index.html, vercel.json) and import that repository at https://vercel.com/new.
4. Set Framework Preset to **Other**, Root Directory to the repository root, and leave Build Command blank.
5. Click Deploy. Open the resulting HTTPS link on your iPhone in Safari.

## Mac Terminal option (Vercel CLI)

Install Node.js if needed, then in Terminal:

```bash
npm install -g vercel
cd ~/Downloads/sculpt-me-vercel
vercel
```

Follow the prompts. For production deployment, run `vercel --prod`.

## Notes

- Data is stored in the browser on each device. It is **not synced** between devices.
- Hydration and meal records can be lost if browser data is cleared or a different browser is used.
- This is the existing MVP, not a fully tested production app.
- A deployed HTTPS site is not automatically a native iPhone app, nor does it add background notifications.


## Mobile v1.0 fix
Bottom navigation now uses six equal columns for six tabs, larger tap targets and iPhone safe-area spacing. Deploy the updated index.html to replace the previous version.


## App icon
Includes the approved anime + SM app icon and Apple touch icon. Upload ALL files in this directory to the GitHub repository root, replacing index.html and README.md. After Vercel deploys, remove the old iPhone Home Screen shortcut and add the website again from Safari.
