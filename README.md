# Libertarian freedoom fighters

A standalone WebGL arcade game in a single HTML file.

Each act contains three alien waves followed by a boss. The four acts are Iceworld Alpha Centauri, Vulcan Orion, Pulsar Andromeda, and Obsidian Event Horizon. After the second boss, Selene Canyon Run adds a lunar flight stage with wall collisions before act 3 begins. The finale features the Toblerone victory screen.

## Contents

- `index.html` - the complete game: HTML, CSS, WebGL rendering, game logic, and Web Audio sound.
- `package.json` - simple local launch commands.
- `varldsrymden-anfaller/assets/backdrops/` - sixteen cinematic wave and boss backgrounds plus the long generated Selene Canyon Run environment.

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
- Continue from intro: any key or touch
- Start the game: `Enter`
- Toggle sound: `M`

## Note

The game has no external dependencies and can be deployed as static HTML on a website.
