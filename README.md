# Shimmi

Jednostránkový web pre slovenského rapera Shimmiho. Čisté HTML/CSS/JS, nič netreba buildovať — stačí otvoriť `index.html` v prehliadači alebo nahrať na GitHub Pages / Netlify.

## Ako upraviť obsah

Na konci `index.html` je blok `TU SI UPRAV OBSAH`:

- `KONCERTY` — pridaj termíny, napr.
  `{ datum: "2026-11-14", mesto: "Bratislava", klub: "Majestic", listky: "https://...", vypredane: false }`.
  Staré termíny sa skryjú samé; keď je zoznam prázdny, zobrazí sa „Nové termíny čoskoro“.
- `LINKY` — vlož oficiálne profily (Spotify, YouTube, Apple Music, Instagram, TikTok). Prázdne linky sa nezobrazia.
