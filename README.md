# Aadhya Gupta — Textile Design Portfolio 2026

A single-page portfolio site for Aadhya Gupta, textile design student at NIFT.
The page opens with an animated hero, introduces Aadhya through an About /
Skills / Experience layout, and presents nine project pieces in a grid. Clicking
any project opens a full-screen modal viewer with scrollable pages and
prev / next navigation.

## Running it

Everything is static — no build step. Just open `index.html` in a browser, or
serve the folder:

```
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Structure

```
index.html              single-file site (HTML + CSS + JS inline)
images_web/
  cover-portrait.png    hero portrait
  page-01..49.jpg       PDF pages that feed the project viewer
  slide-about/          About slide portrait + contact icons
```

## Projects

The grid covers nine pieces — Florilegium, Noor-e-Mahal, Between Tides,
Hibiscus Heat, Maisonette, Sugarpie, Velvet Hour, Neel Nagri, and Inkthread —
each mapped to a slice of the PDF page range inside the modal viewer.

## Contact

- Email — aadhya.gupta@nift.ac.in
- LinkedIn — https://www.linkedin.com/in/aadhya-gupta-015bb6363/
- GitHub — https://github.com/aadhyagupta185-jpg
