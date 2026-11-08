# Experiment 002 — Gravity Cube

## Purpose
Preserve Experiment 001 unchanged. Build a new screen-locked transparent cube with adjustable viewing angle and a gravity-responsive water surface.

## Intended behavior
1. Drag to choose the cube's viewing angle (including corner views).
2. Lock the chosen view to the phone screen; the cube should not counter-rotate when the phone tilts.
3. Use the device orientation / gravity estimate to tilt the water plane inside the cube, while keeping the cube itself visually fixed.
4. Provide reset, sensor permission, diagnostics, and manual fallback.
5. Initially keep water contained; later investigate sloshing, volume conservation, and spill thresholds.

## Technical notes
- Browser DeviceOrientation events provide orientation, not position tracking.
- The screen-locked model rotation and gravity vector are independent.
- A first prototype may approximate the water as a clipped plane; this is not a fluid simulation.
- Keep each working version, document sensor quirks, and test on Android HTTPS.

## Baseline
Experiment 001: `../001-fixed-space-cube/index.html` (do not overwrite).
