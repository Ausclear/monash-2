# The General — Monash 2

A cinematic development site for **The General**, a biographical drama inspired by the life of Sir John Monash.

**Live:** https://monash-2-smithmk.vercel.app (Vercel)

## About this repo

This is the second iteration of the Monash film site — a fresh design centred on the AIF Rising Sun key art, the Battle of Le Hamel, a full timeline of Monash's life, the production team, and a poppy field remembrance closing.

The predecessor site remains at [Ausclear/monash-film](https://github.com/Ausclear/monash-film) — this is a distinct project ("Monash 2") kept separate so both can be worked on independently.

## Structure

```
/
├── index.html          Single-file HTML build with inline CSS + JS
├── audio/
│   ├── gnossienne.mp3   Satie, Gnossienne No. 1 — performed by La Pianista, 56 kbps mono
│   └── gnossienne.ogg   OGG Vorbis fallback
├── vercel.json         Deployment config (public, cache headers, CORS on audio)
└── README.md
```

Audio is served via jsDelivr CDN:
- `https://cdn.jsdelivr.net/gh/Ausclear/monash-2@main/audio/gnossienne.mp3`

## Design

Cinematic dark aesthetic with restrained red accent (`#a2251c`), Cormorant Garamond display serif over DM Sans utility, and film grain overlay. Selective-colour photography treatment (greyscale with only poppies in red) at the remembrance close.

## Attribution

- Historical imagery: public domain (Australian War Memorial, Wikimedia Commons)
- Score: Beethoven, Piano Sonata No. 14 (Moonlight), Op. 27 No. 2 — I. Adagio sostenuto. Public domain recording via Wikimedia Commons
- Key art: original artwork for the project

© 2026 Mark Smith · Trigger Creative™
