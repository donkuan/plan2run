# Workout Pace Library

Enter a race result or a VDOT and every sub-threshold, threshold, VO2max and race-specific session updates to your paces and heart-rate targets. Works offline after the first visit and can be installed on your phone's home screen.

## Publish on GitHub Pages

1. Create a new public repository on GitHub, for example `workout-pace-library`.
2. Upload all files in this folder (keep the `icons` folder and the `.nojekyll` file).
3. In the repository: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/workout-pace-library/`.

## Use it offline

Open the site once while online. On Android in Chrome, tap **⋮ → Add to Home screen** (or **Install app**). On iPhone in Safari, tap **Share → Add to Home Screen**. It then opens full screen and works without a connection; your inputs are remembered on that device.

## Updating

After changing `index.html`, raise `VERSION` in `sw.js` (for example `wpl-v2`) so phones pick up the new version.
