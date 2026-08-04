# BMHS Band & Guard — Sponsorship Site

Two pages: the main sponsorship pitch, and a sponsors showcase page.

## Files

- `bmhs-sponsorship.html` — the main sponsorship pitch page
- `bmhs-sponsors.html` — "T-Shirt Sponsors" showcase page, linked from the main page's nav and contact card
- `bmhs-sponsorship.css` — shared styling for both pages
- `bmhs-sponsorship.js` — small scroll-reveal effect
- `assets/sponsors/` — all sponsor logo images, referenced by `bmhs-sponsors.html`

All filenames are unique and prefixed on purpose, so they won't collide with `index.html`, `style.css`, or `script.js` from any other project already sitting in the same repo.

## Deploying with GitHub Pages

Upload everything, including the full `assets/sponsors/` folder, keeping the same folder structure. If any sponsor logos are missing on the live page, it's almost always because the `assets/sponsors` folder didn't get uploaded, or got flattened during upload.

Your live URLs will be:
- `https://<your-username>.github.io/<repo-name>/bmhs-sponsorship.html`
- `https://<your-username>.github.io/<repo-name>/bmhs-sponsors.html`

## Sponsors currently on the page (14)

Commercial Glass Company, Soundroom, Tropical Smoothie Cafe, S&A Excavation, Chris' Plumbing, High Desert Tattoo Studio, Prescott Family Chiropractic, Fit Club Prescott Valley, T Baxter Enterprises LLC, RBS Fabrication (Rolling Big Steel), Dutton Construction Co, The Hill Collective (Luxury Real Estate), Elks Theatre & Performing Arts Center, AZ RV Outfitters.

The Hill Collective and Elks Theatre logos are white artwork, so their tiles use a dark background (`dark-tile` class) instead of white so the logo stays visible. Keep that class on those two if you ever reorder the grid.

All 14 logos link out to the sponsor's own website, Instagram, or Facebook page (opens in a new tab).

## Editing content later

- Dollar amounts, tier names, and the payment link are in `bmhs-sponsorship.html` under `<section id="tiers">`.
- The payment link (Zeffy) appears seven times across the main page: header button, hero button, all four tier cards, the competition callout, and the contact section. Update all seven if the link ever changes.
- The September 1st trailer deadline appears twice on the main page: once in the tiers section note, once in the contact card.
- The sponsors page has no tier grouping yet since sponsor tiers weren't provided. All logos currently display equally. Ask Claude to regroup by tier once that information is available.
