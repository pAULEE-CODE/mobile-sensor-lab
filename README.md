# Mobile Sensor Lab

A collection of standalone HTML experiments for Android, iPad, and desktop browsers, exploring motion sensors, orientation, WebGL-style 3D graphics, and interaction.

## Experiments
- **001 — Fixed-Space Cube:** An orientation-compensated 3D cube with calibration, live sensor diagnostics, and a fallback manual rotation mode.

## Run
Open `index.html` to browse experiments. For real motion sensors, serve the site over HTTPS (GitHub Pages recommended). The HTML experiments have no external dependencies.

## GitHub Pages
Repository **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.

Expected URL after deployment: https://pAULEE-CODE.github.io/mobile-sensor-lab/

## Notes
DeviceOrientation support depends on the browser and permissions. The cube is orientation-stabilized, not position-tracked; translating the phone will not produce real-world AR parallax.
