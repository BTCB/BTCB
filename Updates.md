# Updates

## 2026-04-18 00:00 UTC+8

- Reworked `README.md` profile layout for stronger visual hierarchy and better personal branding.
- Upgraded GitHub chart stack: stats, streak, top languages, activity graph, productive-time card, and trophy wall.
- Fixed chart reliability issues by replacing unstable/incorrect endpoints and invalid query parameters.
- Improved snake workflow stability in `.github/workflows/snake.yml` with modern action versions, explicit permissions, and concurrency control.

## 2026-04-18 (follow-up) UTC+8

- Applied unified **Aurora Midnight** theme across `README.md`: capsule header, badges, GitHub stats, streak, languages, activity graph, productive-time card (Tokyo Night), and trophies (One Dark).
- Aligned Platane `snk` snake colors with the same palette for light SVG, dark SVG, and GIF output.

## 2026-04-18 (capsule-render fix) UTC+8

- Fixed capsule-render header: removed `&` from `desc` (API forbids `&`/`#`/`/` in text fields; `%26` still breaks parsing). Switched to `Full-stack and Web3`, used explicit `color=0:…,100:…` gradient, and HTML `<img width="100%">` for reliable GitHub rendering.
