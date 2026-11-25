# Lograr website

The landing page for [Lograr](https://lograr.live), the crew app for lifters.

It is one static page with no build step: `index.html` plus the icons in `icons/`. Fonts load from Google Fonts. The Kilo drawings are SVG files in `icons/kilo/`, copied from the app repo.

## Run it locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy

Any static host works. On Vercel, import this repo with the framework preset set to "Other" and no build command.

## Store links

Paste the TestFlight public link and the Play testing opt-in link into `window.LOGRAR_LINKS` at the top of `index.html`. iPhones and Android phones then get their beta as the main button, with lograr.live as the smaller option. While they're empty, lograr.live stays the main button.

## Media

`media/screens/` holds WebP copies of the store screenshots and `media/lograr-trailer.webm` is the 30 s trailer, both from the app repo's `appstore/` folder. `icons/kilo/` is copied from the app repo's `icons/kilo/`.
