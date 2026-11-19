# Caritas Micro-Impact

Prototype of a micro-volunteering platform for young people (Gen Z): small tasks of 5 to 60 minutes for Caritas services in Fulda.
Student project, Corporate Social Responsibility course, International Business and Management, Hochschule Fulda (2026).

## What is in it
- `index.html`: the whole site and app in one file (German and English, light and dark, phones and computers). This is what gets published.
- `src/`: the source parts. Edit these, then run `./build.sh` to rebuild `index.html` (it inlines the Caritas and Hochschule Fulda logos from `../guidelines/`).

## Map
The map uses Leaflet with OpenStreetMap / CARTO tiles. **No API key is needed.** It works as soon as the page is served over http(s), for example on GitHub Pages.

## Demo mode
`index.html?demo` opens the app with a sample profile already in use (minutes, badges, a booking), handy for presentations.

## Publish on GitHub Pages
1. Create an empty public repository, e.g. `caritas-micro-impact`.
2. Push this folder to it.
3. Settings > Pages > Deploy from branch > `main` / root.
The site will be at `https://<user>.github.io/caritas-micro-impact/`.

## Data
No cookies, no tracking, no backend. Everything a visitor does stays in their browser's localStorage and can be deleted in the profile.
Tasks, places and services are examples. Survey figures: n = 124, 2026.
