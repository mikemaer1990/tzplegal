# The Zebras Paralegal LLP — Website

## Project Status: LIVE

**Live URL:** https://mikemaer1990.github.io/tzplegal/
**Repo:** https://github.com/mikemaer1990/tzplegal
**Branch:** master → auto-deploys to GitHub Pages

---

## What's Built

### All 4 Pages — Complete
- `index.html` — Home
- `services.html` — All 10 services with full descriptions
- `about.html` — Story, credentials, values
- `contact.html` — Contact form + info

### Shared Files
- `styles.css` — All styles (dark luxury theme)
- `script.js` — Nav, hamburger, smooth scroll, fade-up animations, FAQ accordion, scroll progress bar, animated stat counters
- `images/z_new_2.svg` — Logo (used as favicon too)

### Features Implemented
- Fixed navbar with backdrop blur on scroll
- Hamburger mobile menu with full-screen overlay
- Active nav state detection by current page
- Smooth scroll on anchor links
- Fade-up intersection observer animations
- Gold scroll progress bar (top of page)
- Marquee strip (scrolling services ticker below hero)
- Animated stat counters (500+ clients, 10+ years, 2 locations)
- FAQ accordion (script.js handles `.faq-question`)
- Sticky mobile CTA bar (Call Now + Book Online)
- Schema.org JSON-LD structured data (index.html)
- SEO meta titles and descriptions on all pages
- SVG favicon on all pages
- Zebra stripe CSS background pattern on hero + stats sections

### Contact Form
- Handler: **Web3Forms** (https://api.web3forms.com/submit)
- Access key: `afa6b400-519c-4ef4-a2ac-209997fd6307`
- Delivers to: `info@tzplegal.com`
- Subject line: "New Consultation Request — The Zebras Paralegal LLP"
- Redirect after submit: `https://mikemaer1990.github.io/tzplegal/contact.html?success=1`
- Bot protection: honeypot `botcheck` checkbox (hidden)

---

## Brand & Visual Identity

### Colours
- **Primary background**: `#0a0a0a`
- **Secondary background**: `#111111`
- **Gold primary**: `#C9A84C`
- **Gold light**: `#E8C86A` (hover)
- **Gold dark**: `#8B6914`
- **White text**: `#F5F5F5`
- **Muted text**: `#9A9A9A`
- **Border**: `rgba(201, 168, 76, 0.2)`

### Typography
- **Headings**: Cormorant Garamond (400, 600, 700) — Google Fonts
- **Body/UI**: Jost (300, 400, 500) — Google Fonts

### Key Design Rules
1. Never use white or light backgrounds
2. Gold is the accent — not the background
3. Generous spacing — premium feel
4. No stock photo grids — icons, patterns, typography
5. Every page has a "Book a Free Consultation" CTA
6. Mobile nav must work — hamburger + overlay

---

## Pending — Awaiting From Client

- [x] **Paralegal photo** — `images/johnson-luyiga.webp` in place
- [x] **Real bio** — `about.html` bio written and in place
- [ ] **Client testimonials** — `index.html` (3 lorem ipsum placeholders)
- [x] **LSO licence number** — `about.html` credentials panel (P19861)
- [x] **Office hours** — `contact.html` contact info column (Mon–Fri 9–5, Sat 10–3)
- [x] **Stat numbers confirmed** — 100+ clients, 3+ years experience, 2 Ontario locations
- [ ] **Form success message** — `contact.html` currently redirects back to same page with `?success=1` but no banner is shown yet

---

## Technical Notes

- Pure HTML/CSS/JS — no frameworks, no build tools
- Mobile breakpoint: 768px
- No external dependencies except Google Fonts and Web3Forms
- All placeholder content marked with `<!-- TODO: Replace -->` comments
- Footer links to `tzplegal.com/privacy-policy` and `tzplegal.com/terms-and-conditions` (not yet live)

---

## File Structure

```
/
├── index.html
├── services.html
├── about.html
├── contact.html
├── styles.css
├── script.js
├── CLAUDE.md
└── images/
    └── z_new_2.svg
```
