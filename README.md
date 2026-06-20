# Världsrymden Anfaller Rambodal

Ett fristående WebGL-arkadspel i en enda HTML-fil.

Efter tre alienvågor kommer första bossen. När den besegras startar akt 2 med tre nya liv, skyddspuls, sinusformationer och en andra rymdjägarboss. Finalen visar Toblerone-vinstskärmen.

## Innehåll

- `index.html` - hela spelet: HTML, CSS, WebGL-rendering, spellogik och Web Audio-ljud.
- `package.json` - enkla lokala startkommandon.

## Starta lokalt

Med Python:

```bash
python3 -m http.server 4173
```

Öppna sedan:

```text
http://127.0.0.1:4173/
```

Med npm:

```bash
npm run serve
```

## Kontroller

- Flytta: `←` / `→` eller `A` / `D`
- Skjut: `Space`, `W` eller `↑`
- Sköld: `X`, obegränsat
- Starta/hoppa över intro: `Enter` / `Space`
- Ljud av/på: `M`

## Notering

Spelet är byggt utan externa dependencies och kan laddas upp som statisk HTML på en hemsida.
