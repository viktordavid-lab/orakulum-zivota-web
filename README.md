# Orákulum Života — Web (privacy + landing)

Static HTML hosting pre mobilnú aplikáciu **Orákulum Života**.

**Live:** https://orakulum-zivota.inspiruj.online

## Stránky

| URL | Účel |
|-----|------|
| `/` | Landing page (link na privacy) |
| `/orakulum-privacy.html` | Privacy Policy (Google Play / App Store requirement) |

## Stack

- Static HTML (žiadny build)
- Vercel deploy z `public/` directory
- `vercel.json` — clean URLs + security headers

## Súvisiace projekty

- **Mobilná appka:** [orakulum-zivota](https://github.com/viktordavid-lab/orakulum-zivota) (private repo, React Native + Expo)
- **Distribútor:** [Slnko v Srdci, s.r.o.](https://slnkovsrdci.sk)

## Autorka

Janka Sofia Thomková — autorka kariet a knihy Orákulum Života.

## Deploy

Auto-deploy cez Vercel pri push na `main`. Žiadny manual build krok.

## Licencia

Privacy policy text — verejný (právny dokument). Branding (logo, farby) © 2026 Janka Sofia Thomková.
