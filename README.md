# Accretion

A browser game: steer a rogue planet, absorb smaller bodies, avoid larger ones, grow until you ignite.

## Tech
- Single `index.html`, vanilla JavaScript, 2D canvas, no libraries or build step
- N-body gravity with softening, fixed 1/120 s timestep (symplectic Euler)
- Mass-transfer absorption with momentum conservation
- Procedural planet sprites from seeded 3D value noise (fbm), generated at load
- Parallax star and nebula backdrop, additive particles
- Web Audio synthesis, no audio files
- Responsive: ResizeObserver, DPR handling, touch joystick and buttons
- PWA: web manifest and service worker (offline after first load)

## Run
Open the deployed Pages URL, or serve the folder with any static server.
