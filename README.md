# Meat Lab for iPad

This folder is Meat Lab packaged as an installable web app. Once it's on your iPad's
Home Screen it opens full screen like a normal app, with its own icon, and keeps
working offline after the first launch.

## 1. Put the folder online (free, from Windows)

iPad needs to load the app once from a secure (https) web address. GitHub Pages is
free and everything can be done in your browser:

1. Sign in at https://github.com and click **New repository**. Name it `meatlab`, set it
   to **Public**, and create it.
2. On the new repository page click **uploading an existing file**, then drag in every
   file from this folder: `index.html`, `sw.js`, `manifest.webmanifest`, and the three
   `icon-*.png` files. Click **Commit changes**.
3. Go to **Settings → Pages**. Under *Branch*, choose `main` and `/ (root)`, then **Save**.
4. After a minute the page shows your address, something like
   `https://YOUR-NAME.github.io/meatlab/`.

## 2. Install it on the iPad

1. Open that address in **Safari** (it has to be Safari).
2. Tap the **Share** button, then **Add to Home Screen**, then **Add**.
3. Launch Meat Lab from the new Home Screen icon. Open it once while online so it can
   save itself for offline play.

## Controls on iPad

- Tap an item in the panel, then tap empty space to place it.
- Drag anything to grab and fling it.
- Long-press anything for the options menu (revive, heal, duplicate, freeze, delete…).
- Pinch to zoom, and move two fingers to pan.
- **☰** hides the item panel so you get the whole screen.
- **Use / fire** tool: tap guns to shoot (hold on the rifle for full auto), tap grenades, saws and thrusters to activate them.
- **Vitals** shows the heartbeat and each limb's health for the last person you touched.
- A hardware keyboard still works: S vitals, W wander, Space pause, T slow motion.

## Updating later

If you change `index.html`, also open `sw.js` and bump `meatlab-v1` to `meatlab-v2`
(and so on) before uploading, otherwise the iPad keeps playing the cached old version.
After uploading, open the app twice to pick up the update.
