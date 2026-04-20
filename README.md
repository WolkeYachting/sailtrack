# sailtrack

Public frontend + data repo for SailTrack. Served via GitHub Pages.

## Enable GitHub Pages

1. Push this repo (`wolkeyachting/sailtrack`)
2. On GitHub: Settings → Pages → Source: `Deploy from a branch`, branch `main`, `/ (root)`
3. URL: `https://wolkeyachting.github.io/sailtrack/`

## Structure

- `index.html` – code entry page
- `track.html` – map view (code in URL hash: `track.html#ABC123...`)
- `tracks/<sha256>.geojson` – tracks (committed by backend)

## Privacy model

The `tracks/` directory contains files named by SHA-256 hash of the track code.
Without the code, you cannot figure out which file belongs to which track.
