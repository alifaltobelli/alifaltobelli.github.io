# Alif Altobelli Portfolio — Default English Version

## Main changes
- Default homepage is now English: `/`
- Indonesian version is now at `/id/`
- Small circular profile photo is used in the navbar brand area
- Light / Dark mode remains available

## Upload structure
Upload the contents of this folder directly to the root of the `alifaltobelli.github.io` repository:

- `index.html`  → English homepage
- `id/index.html` → Indonesian version
- `en/index.html` → optional English compatibility path
- `assets/profile.jpg`
- `assets/profile.jpeg`
- `assets/CV-Alif-Altobelli.pdf`
- `assets/favicon.svg`
- `robots.txt`
- `sitemap.xml`
- `.nojekyll`
- `README.md`

## Final URLs
- English: https://alifaltobelli.github.io/
- Indonesian: https://alifaltobelli.github.io/id/

Education correction: Institut Teknologi Adhi Tama Surabaya updated to 2021–2025.

Hero portrait updated: smaller size with a circular presentation.

## CV files
- English/default site downloads: `assets/CV-Alif-Altobelli-EN.pdf`
- Indonesian site downloads: `assets/CV-Alif-Altobelli-ID.pdf`

Portrait image CSS updated with `height: 100%` for consistent circular sizing.

Photo path fix: nested `/id/` and `/en/` pages now correctly use `../assets/profile.jpg`. Hero portrait is fixed at 220x220px desktop and remains circular/responsive.


## 2026-10 responsive + academic update
- Added complete responsive layout refinements for desktop, laptop, tablet, mobile, and 320px+ screens.
- Added accessible hamburger navigation below 940px.
- Added Academic Portfolio / Portfolio Akademik section with research, web-system project, and SINTA IPR references.
- Added `alumniOf` ITATS structured data.

## Mobile hero portrait refinement
- On screens up to 620px, the profile portrait now appears at the top of the hero.
- Portrait, experience badge, eyebrow, headline, copy, and CTA area are centered for a cleaner mobile composition.
- Desktop and tablet layouts remain unchanged.

## Mobile header theme toggle
- On mobile/tablet navigation, the light/dark theme control is now placed directly beside the hamburger menu.
- The theme control is no longer shown inside the dropdown menu.

## Theme toggle fix
- Light/dark toggle is visible again on desktop.
- On tablet/mobile it remains beside the hamburger menu.
- It is not shown inside the dropdown navigation.

## Motion / 3D enhancement
- Added subtle animated hero particles and ambient motion.
- Added desktop-only 3D parallax on the portrait and hover tilt on portfolio/skill/experience cards.
- Added scroll reveal transitions.
- Added a restrained headline shimmer and button light sweep.
- Heavy motion is disabled on small mobile screens and all motion respects `prefers-reduced-motion`.
- No framework or external 3D library is required; the effect is lightweight vanilla CSS/JavaScript.
