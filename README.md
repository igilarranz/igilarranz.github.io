# igilarranz.github.io

Personal site: [igilarranz.github.io](https://igilarranz.github.io)

## Files

- `index.html` — the whole site (CSS + JS inline, no build step)
- `404.html` — custom not-found page
- `resume.pdf` — **you need to add this** (linked from nav, hero, footer)
- `bunny.png` — mascot
- `assets/` — project thumbnails and `og-image.png` (link preview)

## Deploy

1. Put `resume.pdf` in the repo root.
2. In `index.html`, find `YOURCODE` in the GoatCounter line near the bottom and replace it with your code from goatcounter.com, or delete that `<script>` line.
3. `git add -A && git commit -m "site redesign" && git push`
4. Check in a private window: resume link, `/anything` for the 404, and paste the URL in a Slack DM to see the preview.

## Thumbnails (`assets/`)

Square images. Overwrite any file with the same name to swap the picture.

| file | project | status |
|---|---|---|
| `behavior.png` | BEHAVIOR Challenge planner | placeholder, needs a plan/coverage screenshot |
| `motionsense.jpg` | MotionSense-IMU | real (KiCad 3D render) |
| `pomo.gif` | Pomo-01 | real (app recording) |
| `mp3.jpg` | ESP32-S3 MP3 player | real (bench photo) |
| `bhl.jpg` | Berkeley Humanoid Lite | placeholder, needs a photo |
| `eeg.png` | EEG pattern analysis | placeholder, needs a plot |
