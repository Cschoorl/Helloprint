# Back to Being × Helloprint — Samenwerkingsvoorstel

Een interactief, schermvullend voorstel (slide-deck in de browser) van **back to being** voor **Helloprint**.

## 🔗 Bekijk de pagina

Zodra GitHub Pages aanstaat (zie hieronder):

- **Helloprint-versie (NL):** https://cschoorl.github.io/Helloprint/
- **Wispr-versie (EN):** https://cschoorl.github.io/Helloprint/wispr.html

## ▶️ GitHub Pages aanzetten (eenmalig)

1. Ga naar de repo → **Settings**
2. In het menu links: **Pages**
3. Bij **Build and deployment → Source** kies je **Deploy from a branch**
4. Selecteer branch **`main`** en map **`/ (root)`**, klik **Save**
5. Wacht ~1 minuut en ververs. De pagina staat dan op de link hierboven.

## 💻 Lokaal bekijken

Geen build nodig — het is gewone HTML/CSS/JS.

```bash
# In de projectmap:
python3 -m http.server 8000
```

Open daarna http://localhost:8000/ in je browser.

Of open `index.html` direct in je browser (de intro-animatie en fonts werken het best via de server hierboven).

## 📁 Bestanden

| Bestand | Omschrijving |
| --- | --- |
| `index.html` | Helloprint-versie (Nederlands) — de hoofdpagina |
| `wispr.html` | Originele Wispr-versie (Engels) |
| `favicon.svg` | Favicon |
| `logo-animation.json` | Lottie intro-animatie |

## ⌨️ Bediening

- **Volgende slide:** pijl rechts, spatie, enter of de knop rechtsonder
- **Vorige slide:** pijl links of de knop
- **Mobiel:** swipe naar links/rechts
- **Begin / eind:** `Home` / `End`

## 🛠️ Techniek

- Pure HTML, CSS en vanilla JavaScript — geen framework, geen build-stap
- Fonts via Google Fonts (Instrument Serif + Inter)
- Intro-animatie via [lottie-web](https://github.com/airbnb/lottie-web)
