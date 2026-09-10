# Orákulum Života — Web — ROADMAP

> ⏳ **Dáta v tomto súbore sú k 21.05.2026** (96 dní). Novšie udalosti nemusia byť zachytené — pri rozhodovaní podľa čísel nižšie over aktuálnosť.

**Repo:** `C:\1-Projekty\SlnkovSrdci\Orakulum-Web` · **Beží:** áno · **Aktualizované:** 25.8.2026
**Live:** https://orakulum-zivota.inspiruj.online
**Materský projekt:** [Slnko v Srdci](../ROADMAP.md) · **Appka:** [Orákulum Života](../Orakulum/ROADMAP.md)
## Stav

| Stav | Popis |
|------|-------|
| ✅ LIVE | Static HTML hosting na Verceli — landing + privacy policy |

**Účel:** hostí **Privacy Policy**, ktorú vyžaduje Google Play (a App Store) pre mobilnú appku Orákulum Života. Bez nej sa appka nedá publikovať.
| URL | Účel |
|-----|------|
| `/` | Landing page (odkaz na privacy) |
| `/orakulum-privacy.html` | Privacy Policy — **requirement Google Play / App Store** |
| `/kody-zivota` | 🧪 **Testovacia web verzia appky Kódy života v0.6.6** (od 11.9.2026) — pre testerov zo seminára 12.9.; `noindex`; zdroj = `KodyZivota` repo, `scripts/export_web.py` sem kopíruje export (`experiments.baseUrl`). Dočasné — po spustení strešnej appky odstrániť. |

**Stack:** static HTML (žiadny build) · Vercel auto-deploy z `public/` pri pushi na `main` · `vercel.json` = clean URLs + security headers

## Aktívne (P0)

— žiadne

## Ďalší krok

— žiadny. Web plní svoju funkciu; zmena bude potrebná až pri **L1 monetizácii** (podmienky nákupu / refund policy môžu vyžadovať doplnenie Terms).

## Pending plány

— žiadne

## Ideas / backlog

- Doplniť **Terms of Service** — pravdepodobne potrebné pred spustením platenej L1 verzie appky
- Landing page je dnes minimálna (len odkaz na privacy) — kandidát na marketingovú stránku pri launchi

## História verzií

- **2026-09-11** — `feat: testovacia web verzia Kody zivota v0.6.6 pod /kody-zivota` (`d759297`) — 53 súborov, 5,0 MB, Vercel auto-deploy overený (titulok + JS bundle 200)
- **2026-05-21** — `docs: update live URL to orakulum-zivota.inspiruj.online` (`7b5ce2c`) — prechod na vlastnú doménu
- **2026-05-21** — `docs: update live URL to orakulum-zivota.vercel.app` (`f52be6b`)
- **2026-05-21** — `feat: initial orakulum-zivota-web` (`713c46a`) — založenie

---

**Autorka obsahu:** Janka Sofia Thomková · **Distribútor:** Slnko v Srdci, s.r.o.
*Privacy policy text je verejný (právny dokument). Branding © 2026 Janka Sofia Thomková.*
