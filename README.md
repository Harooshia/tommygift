# tommygift

A static birthday gift website that presents the existing HTML pages in one hosted viewer with Back and Forward navigation.

## Pages included

- `tommy_birthday_site_v2 (1).html`
- `100_things_mei_loves_about_you (1).html`
- `HAAPYY BIRTHDAYYY I LOVE UUUU SOO MUCHHHH.html`
- `TOMMYYYYYY.html`
- `strelitzia (1).html`
- `tommy baby.html`
- `tommy is the besttt.html`

## Run locally

Open `index.html` directly in a browser, or run a tiny static server:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Host on Render

This repository includes `render.yaml`, so Render can deploy it as a Static Site with a no-op build command.

1. Push the repository to GitHub.
2. In Render, choose **New +** → **Blueprint** and select this repo.
3. Render will read `render.yaml`, set the publish path to `.`, and deploy `index.html` plus the linked HTML pages.

If creating the Render site manually, choose **Static Site**, set the build command to `true`, and set the publish directory to `.`.
