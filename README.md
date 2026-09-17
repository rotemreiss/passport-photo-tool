# Passport Photo Booth

A single-page, zero-dependency web tool for taking passport/visa-style photos with your webcam.

**Live:** https://rotemreiss.github.io/passport-photo-tool/

## Features

- Webcam capture with positioning guides (face oval, eye line, shoulder marks) and a 5-second timer
- Or centre-crop an existing photo
- Exports a portrait 4:5 JPEG at 1200 × 1500 px (above the common 600 × 750 minimum)
- Heuristic checks: resolution, brightness, plain light background, even lighting
- 100% client-side — photos never leave your browser

## Usage

Open `index.html` (or the GitHub Pages link), allow camera access, line up with the guides, capture, download.

## Disclaimer

The auto-checks are heuristics only. Always verify your photo against the official requirements of the service you are applying to.
