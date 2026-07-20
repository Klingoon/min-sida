# Libertarian freedoom fighters

A standalone WebGL arcade game in a single HTML file.

The first boss arrives after three alien waves. Defeating it starts act 2 with three new lives, a shield pulse, sine-wave formations, and a second space hunter boss. The finale features the Toblerone victory screen.

## Contents

- `index.html` - the complete game: HTML, CSS, WebGL rendering, game logic, and Web Audio sound.
- `package.json` - simple local launch commands.

## Run locally

With Python:

```bash
python3 -m http.server 4173
```

Then open:

```text
http://127.0.0.1:4173/
```

With npm:

```bash
npm run serve
```

## Controls

- Move: `←` / `→` or `A` / `D`
- Fire: `Space`, `W`, or `↑`
- Shield: `X`, unlimited
- iPhone steering: hold your thumb on the ship and drag
- iPhone fire: tap the playfield with your index finger
- iPhone shield: hold the lower-left corner of the screen
- Continue from intro: any key or touch
- Start the game: `Enter`
- Toggle sound: `M`

## Note

The game has no external dependencies and can be deployed as static HTML on a website.
