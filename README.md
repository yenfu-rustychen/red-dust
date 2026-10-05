# RED DUST — Crash Landing on Mars

A browser game based on *The Martian* by Andy Weir. You are the one they left behind: land the lander, cross the canyon, grow potatoes in the hab, race the rover to the comms tower, build a rocket in Houston, and get off Mars.

## Play

Open `index.html` (or `mars-crash.html`) in a desktop browser. The page is the game's website; press **Play** at the top or the bottom to start. If GitHub Pages is turned on for this repo, the game runs straight from the Pages address.

On a phone or tablet the website works, but the game needs a keyboard and mouse: Play explains that first, and the game's models are only downloaded if you go on anyway.

Keyboard and mouse: WASD to move, mouse to look, Space to jump, Shift to sprint, E to interact, Esc to pause. Every key can be rebound in Settings.

## What's here

- `mars-crash.html` — the whole game and its website, in one file (Three.js r128, loaded from a CDN)
- `mars-crash-*.js` — the baked 3D models (the astronaut, the hab, the crew, the props, the MAV's cabin parts), loaded by the page
- `mars-crash-music.js`, `mars-crash-sfx.js` — the music, ambience and sound effects, loaded once the game starts
- `mars-crash-clip-01..12.mp4` and `.jpg` — the gameplay clips and their posters on the Gameplay page
- `mars-crash-logo.png`, `mars-crash-cover.jpg`, `mars-crash-editors.jpg`, `mars-crash-weir.jpg` — the images the website shows (Andy Weir's photo: Gage Skidmore, CC BY-SA 3.0)

All of these files must stay together in one folder.

## Credits

Picture and code: Marc · Trailer and story: Mike

Based on *The Martian* by Andy Weir. Made with Claude Code, Meshy AI (3D models) and Higgsfield (music and sound).
