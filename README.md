# Recipe Box

A recipe and grocery-list web app for iPhone, made to run on GitHub Pages.

- Recipes sorted by your own categories, with sections (dough, filling, …) and a jump bar on the side
- Metric by default, switch to cups on any recipe
- Paste a recipe in cups and it is converted to metric (°F → °C, inches → cm too)
- Several grocery lists that open and close
- Profile and settings, backup and restore

## Put it online
1. Create a new repository on GitHub (e.g. `recipe-box`).
2. Upload these files to it: `index.html`, `manifest.webmanifest`, `icon-180.png`, `icon-512.png` (and this README if you like).
3. Settings ▸ Pages ▸ *Build and deployment* ▸ Source: **Deploy from a branch**, Branch: **main**, folder **/(root)** ▸ Save.
4. After a minute the app is at `https://<your-username>.github.io/recipe-box/`.

## Put it on your iPhone home screen
Open the link in Safari ▸ Share button ▸ **Add to Home Screen**. It then opens full-screen like a normal app.

## Where your recipes are saved
On the device, in the browser's storage. The home-screen app and Safari keep separate copies, so pick one and stick with it.
Use **Profile ▸ Save a backup file** now and then; **Restore from backup** loads it again on any phone or computer.
