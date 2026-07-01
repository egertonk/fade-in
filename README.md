# Fade In — Guess the Landmark

A browser game where a famous landmark slowly fades into view and you try to guess it as fast as you can.

## Play online

**Game Room (landing page):** https://egertonk.github.io/fade-in/

- **Fade In — Guess the Landmark** → https://egertonk.github.io/fade-in/fade/
- **Where Am I? — Street View Guesser** → https://egertonk.github.io/fade-in/geo/
- **Don't Laugh, Don't Speak** → https://egertonk.github.io/fade-in/laugh/
- **Bounce Count** → https://egertonk.github.io/fade-in/bounce/

> The Street View game uses the Google Maps JavaScript API. The key is stored as the
> `GOOGLE_MAPS_API_KEY` GitHub Actions secret and injected at deploy time — it is **not**
> committed to source. Note that a browser Maps key is always visible on the live page, so
> the key must be restricted by HTTP referrer (`https://egertonk.github.io/*`) in Google Cloud.

## Run locally

It's a single, self-contained HTML file — just open it:

```
index.html
```

Or double-click `index.html` in your file browser. No build step, no dependencies to install.

## Tech

Plain HTML, CSS, and JavaScript. Fonts are loaded from Google Fonts.
