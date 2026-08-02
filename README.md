# BMHS Band & Guard — Sponsorship Site

A single-page sponsorship proposal for the Bradshaw Mountain Marching Bears
Band & Guard, built for handing to local businesses or linking directly.

## Files

- `bmhs-sponsorship.html` — the page
- `bmhs-sponsorship.css` — all styling
- `bmhs-sponsorship.js` — small scroll-reveal effect

All three files use unique, prefixed names on purpose, so they won't collide
with `index.html`, `style.css`, or `script.js` from any other project already
sitting in the same repo.

## Deploying with GitHub Pages

**If this is going in its own repo:**

1. Create a new repo, e.g. `bmhs-sponsorship`.
2. Upload all three files to the repo root.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
5. Choose the `main` branch and `/ (root)` folder, then **Save**.
6. Your live URL will be `https://<your-username>.github.io/bmhs-sponsorship/bmhs-sponsorship.html`.

**If this is going into a repo you already use for other projects:**

1. Upload all three files into that repo (a subfolder is fine, root is fine too).
2. Because the filenames are unique, they won't overwrite or get renamed by
   any other project's files.
3. Your live URL will be whatever path you placed the files at, followed by
   `/bmhs-sponsorship.html`, e.g.
   `https://itsmeashweeeee.github.io/<repo-name>/bmhs-sponsorship.html`.
4. Send that exact URL to sponsors, since there's no `index.html` here to
   load automatically at the folder root.

## Editing content later

- Dollar amounts, tier benefits, and the payment link are in
  `bmhs-sponsorship.html` under `<section id="tiers">`.
- The payment link (Zeffy) appears seven times across the page: header
  button, hero button, all four tier cards, the championship callout, and
  the contact section. Update all seven if the link ever changes.
- The September 1st trailer deadline appears twice: once in the tiers
  section note, once in the contact card.
