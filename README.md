# Fade In — Guess the Landmark

A browser game where a famous landmark slowly fades into view and you try to guess it as fast as you can.

## Play online

**Game Room (landing page):** https://egertonk.github.io/fade-in/

- **Fade In — Guess the Landmark** → https://egertonk.github.io/fade-in/fade/
- **Where Am I? — Street View Guesser** → https://egertonk.github.io/fade-in/geo/
- **Don't Laugh, Don't Speak** → https://egertonk.github.io/fade-in/laugh/
- **Bounce Count** → https://egertonk.github.io/fade-in/bounce/
- **Emoji Guess** → https://egertonk.github.io/fade-in/emoji/
- **Guess How Many** → https://egertonk.github.io/fade-in/jar/
- **Higher or Lower** → https://egertonk.github.io/fade-in/higher/
- **Stop the Clock** → https://egertonk.github.io/fade-in/clock/
- **Guess the Gibberish** → https://egertonk.github.io/fade-in/gibberish/
- **Fact or Cap** → https://egertonk.github.io/fade-in/factcap/
- **Guess the Brand** → https://egertonk.github.io/fade-in/brand/
- **Odd One Out** → https://egertonk.github.io/fade-in/oddoneout/
- **Connections** → https://egertonk.github.io/fade-in/connections/
- **Musical Chairs** → https://egertonk.github.io/fade-in/chairs/
- **Guess the Year** → https://egertonk.github.io/fade-in/year/
- **Would You Rather** → https://egertonk.github.io/fade-in/wyr/
- **What Changed?** → https://egertonk.github.io/fade-in/whatchanged/
- **Guess the Flag** → https://egertonk.github.io/fade-in/flags/
- **Trivia Game Show** → https://egertonk.github.io/fade-in/gameshow/
- **Escape Room** → https://egertonk.github.io/fade-in/escape/
- **Wavelength** → https://egertonk.github.io/fade-in/wavelength/
- **Guess the Cocktail** → https://egertonk.github.io/fade-in/cocktail/
- **Bad Plot Summaries** → https://egertonk.github.io/fade-in/plots/
- **Guess the Classic Car** → https://egertonk.github.io/fade-in/cars/
- **Retro Tech** → https://egertonk.github.io/fade-in/retrotech/
- **Who Wants to Be a Millionaire** → https://egertonk.github.io/fade-in/millionaire/
- **Guess the Price** → https://egertonk.github.io/fade-in/price/
- **Guess the Salary** → https://egertonk.github.io/fade-in/salary/
- **Guess the Net Worth** → https://egertonk.github.io/fade-in/networth/

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
