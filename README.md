# Pixel Bus Journey

A pixel-art intercity bus ride from Dhaka to Bagerhat (over the Padma Bridge) on a Dola bus, drawn entirely in code on a canvas.

- Stops: Dhaka, Bhanga Jn, Bagerhat. Scenery changes with the route; oncoming trucks, CNGs, cars and rickshaws pass by.
- Controls: Pause, speed (1x / 2x / 3x), Next (skip to next stop), music on/off. Keyboard: Space, Right arrow, M.
- Music: `assets/bus-sohokari.mp3` starts at 0:39 and loops back to 0:39. Edit `MUSIC_START` / `MUSIC_SRC` at the top of `game.js`.
- Debug: add `?at=5200&paused=1` to the URL to jump to a world position.

No build step: deploy the folder as a static site (Vercel preset: Other).
