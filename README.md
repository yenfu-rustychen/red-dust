# RED DUST — Crash Landing on Mars

A browser game based on *The Martian* by Andy Weir. You are the one they left behind: land the lander, cross the canyon, grow potatoes in the hab, race the rover to the comms tower, build a rocket in Houston, and get off Mars.

## Play

Open `index.html` (or `mars-crash.html`) in a desktop browser. The page is the game's website; press **Play** at the top or the bottom to start. If GitHub Pages is turned on for this repo, the game runs straight from the Pages address.

On a phone or tablet the game has touch controls: the left thumb moves, the right thumb looks, and each phase shows its own buttons. Hold the device sideways. The game's models are only downloaded once you press Play.

Keyboard and mouse: WASD to move, mouse to look, Space to jump, Shift to sprint, E to interact, Esc to pause. Every key can be rebound in Settings.

## What's here

- `mars-crash.html` — the whole game and its website, in one file (Three.js r128, loaded from a CDN)
- `mars-crash-*.js` — the baked 3D models (the astronaut, the hab, the crew, the props, the MAV's cabin parts), loaded by the page
- `mars-crash-music.js`, `mars-crash-sfx.js` — the music, ambience and sound effects, loaded once the game starts
- `mars-crash-vo.js`, `mars-crash-trailer-music.js`, `mars-crash-strip.js`, `mars-crash-ascent.js`, `mars-crash-radio.js`, `mars-crash-finale.js` — the generated voices, score cues, sounds and window views for the trailer, the strip-down, the launch, the spacewalk, the two Houston launches and the ending
- `mars-crash-admin.js`, `mars-crash-appeal.js` — the Administrator's rigged figure, and her office's window view, TV footage, voices, score and room sounds for the appeal scene
- `mars-crash-clip-01..12.mp4` and `.jpg` — the gameplay clips and their posters on the Gameplay page
- `mars-crash-logo.png`, `mars-crash-cover.jpg`, `mars-crash-editors.jpg`, `mars-crash-weir.jpg` — the images the website shows (Andy Weir's photo: Gage Skidmore, CC BY-SA 3.0)

All of these files must stay together in one folder.

## Credits

Picture and code: Marc · Trailer and story: Mike

Based on *The Martian* by Andy Weir. Made with Claude Code, Meshy AI (3D models) and Higgsfield (music, sound and voices).
