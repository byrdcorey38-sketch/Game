# Zombie Gun Sandbox

A browser-based 3D zombie shooting sandbox with desktop controls and experimental WebXR VR support.

## Play locally
Open `index.html` in a modern browser with internet access. Three.js is loaded from jsDelivr, so it must be able to reach the CDN. For immersive VR, a secure HTTPS website is recommended; opening the file directly may not allow WebXR.

## Publish with GitHub Pages
1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **GitHub Actions**.
3. Open **Actions** and check the workflow named **Deploy Zombie Gun Sandbox to GitHub Pages**.
4. After the workflow succeeds, the site should be available at:
   https://byrdcorey38-sketch.github.io/Game/

## Controls
- Desktop: click the arena to lock the mouse; WASD to move; mouse to aim; hold left-click to fire; R to reload; 1–4 to change weapons; Esc to release the mouse.
- VR (compatible browser/headset): press **Enter VR**, point the right controller and press its trigger to fire; use the left stick to move. Controller buttons support spawning zombies, spawning a horde, changing weapons, and reloading.
- Buttons on the game panel can spawn zombies, clear them, and choose weapons.

This is a stylized sandbox prototype. The WebXR experience depends on headset/browser support and may need further tuning for a specific headset.
