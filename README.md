# The Marvel Journey

**Every Marvel Studios film and series, in story order — the whole MCU journey.**

Live site: https://saeedjamalhussains.github.io/marvelguide/

A curated viewing guide to the whole Marvel Cinematic Universe, from *Captain
America: The First Avenger* to *The Fantastic Four: First Steps*, grouped into
saga chapters, with runtime estimates, progress tracking and a countdown to the
next stop, *Avengers: Doomsday*.

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?logo=githubpages&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![No build step](https://img.shields.io/badge/build-none-brightgreen)

## Features

- **Tracked progress** — tick things off as you watch; your place is remembered
  between visits.
- **Runtime estimates** so you can budget the catch-up realistically.
- **Routes**: the whole journey, films only, the Infinity Saga, the Multiverse
  Saga, the focused Road to Doomsday, or Essentials only.
- **Importance levels** (Essential to Optional), so the optional stuff is clearly
  optional.
- **Export and import your progress** as JSON — no account, nothing leaves your
  browser.
- **One file, no build step.** Open it and it works.

## Running it

Open `index.html` in any browser. That's the whole setup.

To publish: GitHub Pages is set to **Settings → Pages → Source: GitHub
Actions**. The included workflow in `.github/workflows/` deploys on every push to
`main`.

## How it's built

Everything — HTML, CSS, JavaScript, and the data — lives in the single
`index.html`. No backend, no framework, no bundler. Progress and settings are
stored in the visitor's browser via `localStorage`, and can be exported or
imported as JSON.

## Maintaining the data

Runtimes and links are curated by hand, and series runtimes are estimates. The
News tab is static: when you edit it, update both its dated entries and the
"last verified" date in `index.html`.

## Contributing

Corrections to runtimes, ordering, or links are welcome — open an issue or a PR.
