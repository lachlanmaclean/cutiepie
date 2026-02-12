# Cutiepie – GitHub Page

Simple landing page for the Cutiepie app.

## Setup

**Copy the app icon:**
```
copy ..\playstore.png .\playstore.png
```

**Copy the app screenshots (1–4 in order):**
```
mkdir screenshots 2>nul
copy ..\screenshots\1.png .\screenshots\
copy ..\screenshots\2.png .\screenshots\
copy ..\screenshots\3.png .\screenshots\
copy ..\screenshots\4.png .\screenshots\
```

Or manually copy `playstore.png` and the `screenshots/` folder (1.png, 2.png, 3.png, 4.png) into this folder.

## Local preview

Open `index.html` in a browser, or use a simple server:

```
npx serve .
```

## Deploy to GitHub Pages

1. Push this folder as the root of a GitHub repo, or
2. Use it as a `docs/` or `gh-pages` branch, or
3. In repo Settings → Pages, set source to this folder
