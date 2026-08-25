# Orákulum Života — Web — ROADMAP

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

- **2026-05-21** — `docs: update live URL to orakulum-zivota.inspiruj.online` (`7b5ce2c`) — prechod na vlastnú doménu
- **2026-05-21** — `docs: update live URL to orakulum-zivota.vercel.app` (`f52be6b`)
- **2026-05-21** — `feat: initial orakulum-zivota-web` (`713c46a`) — založenie

---

**Autorka obsahu:** Janka Sofia Thomková · **Distribútor:** Slnko v Srdci, s.r.o.
*Privacy policy text je verejný (právny dokument). Branding © 2026 Janka Sofia Thomková.*
