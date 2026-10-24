# Shimmi

Jednostránkový web o slovenskom raperovi Shimmim (Oliver Šimák, ConspiracyFlat). Čisté HTML/CSS/JS, nič netreba buildovať. Stačí otvoriť `index.html` v prehliadači alebo ho nahrať na GitHub Pages / Netlify.

## Sekcie

- **Kto je Shimmi**: bio a fakty
- **Doteraz**: časová os 2018 → 2026
- **Albumy**: YOLO, BENIHANA, YO s vinylom, hosťami, trackami a prehrávačom (Spotify / Apple Music sa načíta po kliknutí)
- **Tracky na štart**, **S kým robil**
- **Koncerty**: nadchádzajúce termíny a odohrané turné
- **Fotky**: galéria, fotky sa dávajú do `img/` (pozri `img/README.md`)
- **Počúvaj**: linky na streamovacie služby a merch

## Ako upraviť obsah

Na konci `index.html` je blok `TU SI UPRAV OBSAH`:

- `KONCERTY`: nadchádzajúce termíny, napr.
  `{ datum: "2026-11-14", mesto: "Bratislava", klub: "Majestic", listky: "https://...", vypredane: false }`.
  Staré termíny sa skryjú samé. Keď je zoznam prázdny, zobrazí sa „Nové termíny čoskoro“.
- `TURNE`: odohrané turné a mestá (`vypredane: true` mesto prečiarkne).
- `TRACKY`, `FEATY`: odporúčané tracky a hostia.
- `LINKY`: oficiálne profily. Instagram a TikTok sú zatiaľ prázdne, doplň ich.

Info na stránke je z verejných zdrojov (Discogs, Spotify, Apple Music, Deezer, GoOut, Refresher, AOTY).
