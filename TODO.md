# TODO — The Zebras Paralegal LLP Website

## Awaiting Client

- [ ] **Testimonials** — 3 lorem ipsum placeholder cards on `index.html` (lines ~314–330). Need real quotes + client name/city. Client approval required before publishing.

---

## Needs Building

- [ ] **Privacy Policy page** — `tzplegal.com/privacy-policy` — footer links to it on all 4 pages but the page doesn't exist yet.
- [ ] **Terms & Conditions page** — `tzplegal.com/terms-and-conditions` — same situation.
- [ ] **Form success banner** — `contact.html` redirects to `?success=1` after submission but no confirmation message is shown to the user. Need to add a visible success banner triggered by that query param.

---

## Goes Live With Domain

- [ ] **Contact form redirect URL** — currently points to `mikemaer1990.github.io/tzplegal/contact.html?success=1`. Update to `https://tzplegal.com/contact.html?success=1` once domain is live. Located in `contact.html` hidden input (line ~157).

---

## Low Priority / Polish

- [ ] **WebP image fallbacks** — all images use `.webp` with no `<picture>` fallback for older browsers. Add `<picture><source>` with `.jpg` fallbacks if browser support becomes a concern.
