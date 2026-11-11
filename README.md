# Lograr website

The landing page for [Lograr](https://lograr.live), the crew app for lifters.

It is one static page with no build step: `index.html` plus the icons in `icons/`. Fonts load from Google Fonts. The Kilo drawings are inlined as SVG and come from the app repo (`icons/kilo/`).

## Run it locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy

Any static host works. On Vercel, import this repo with the framework preset set to "Other" and no build command.
