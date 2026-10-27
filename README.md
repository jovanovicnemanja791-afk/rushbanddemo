# Rush Band sajt

Statički sajt, spreman za GitHub Pages. Nema build koraka.

## Objava
1. Napravite repozitorijum i otpremite **sadržaj** ovog foldera u koren: `index.html`, `galerija.html`, `support.js`, `.nojekyll`, `assets/`.
2. Settings → Pages → Source: Deploy from a branch → `main` / `(root)`.
3. Sajt je na `https://KORISNIK.github.io/REPO/`.

## Stranice
- `index.html` – glavna stranica (link „Galerija“ i „Cela galerija“ vode na `galerija.html`)
- `galerija.html` – cela galerija (dugme „Nazad na sajt“ vodi na `index.html`)

Putanje su relativne, pa radi i u podfolderu repozitorijuma.

## Izmene
Fotografije i video menjate u `assets/` (isti nazivi fajlova). Fontovi i React se učitavaju sa interneta (Google Fonts, unpkg).
