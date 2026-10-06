# RoJev

**A Real-Time Pixels-to-Buttons Action Model for Roblox Games**

Project page: https://assettool-labs.github.io/rojev/

RoJev is a vision-language-action (VLA) model that follows natural-language instructions to play 3D multiplayer Roblox games directly from screen pixels. At every step it sees one frame and one instruction, and picks one of 16 key combinations to hold for the next 50 ms — about 37 ms per decision, fast enough to play at 20 FPS without privileged game state or high-level tool calls.

## Repository contents

This repo hosts the static project page, served with GitHub Pages from the `main` branch.

- `index.html` — the project page
- `media/` — demo videos and their poster images
