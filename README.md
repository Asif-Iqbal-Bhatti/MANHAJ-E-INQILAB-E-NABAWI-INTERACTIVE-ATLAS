# Manhaj-e-Inqilab-e-Nabawi ﷺ · Interactive Atlas

An interactive companion to Dr. Israr Ahmed's book *Manhaj-e-Inqilab-e-Nabawi* (the Prophetic method of revolution), read alongside the works of Maulana Abul A'la Mawdudi, the Quran and the authentic hadith.

**Live site:** https://asif-iqbal-bhatti.github.io/MANHAJ-E-INQILAB-E-NABAWI-INTERACTIVE-ATLAS/

## What it contains

- **Overview:** the book's argument in brief. Islam is a Deen, a just system (Nizam-e-Adl), not a private religion.
- **Atlas:** 28 events from Cave Hira (610) to the frontier of 750 CE on one map. Each event has its date, stage, sources, and any Quranic verse quoted in full. Map layers show the Hijrah route, the Quraysh caravan route, the 8 expeditions before Badr, the letters to 8 rulers, and frontiers from c. 610 to 750.
- **The Method:** the six stages (Da'wah, Tanzeem, Tarbiyah, Sabr-e-Mahz, Iqdam, Musallah Tasadum), plus the extension beyond Arabia, a seventh phase added by this atlas. Maulana Mawdudi's Four Point Programme (1951) is set beside the stages as our comparison.
- **Two Scholars:** Maulana Abul A'la Mawdudi and Dr. Israr Ahmed side by side, with classical fiqh and Maulana Abul Hasan Ali Nadwi's critique.
- **Sources & Credits:** the books, the Quran text, the hadith cited, and the map data.

## Using it

Click an event or a numbered marker. Use the ◀ ▶ buttons or the arrow keys to move through events, and the space bar to play the Seerah in order. Every event has its own link, for example `#atlas/badr`.

The page is one self-contained `index.html` with no external requests. To view it offline, open `index.html` in a browser or run `python3 -m http.server` in this folder.

## Sources

- **Quran:** Arabic is the Tanzil Uthmani text via api.alquran.cloud, with pause signs omitted. English is Sahih International; verses with light edits are labelled "adapted".
- **Hadith:** given with collection and number (Sahih al-Bukhari, Sahih Muslim). Reports from Ibn Ishaq's Sirah are labelled as such.
- **Maps:** coastlines, rivers and lakes are from Natural Earth (public domain). Frontiers, routes and some historical sites are approximate reconstructions.
- **Fonts:** Amiri, Inter and Cinzel, under the SIL Open Font License 1.1 (see `fonts/`).

## Credits

Credits and production: **AIB_EM2R**.
Claude Opus 5.5 model was used to fine tune the animation and this atlas.
