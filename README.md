# BMHS Band & Guard — Sponsorship Site

A single-page sponsorship proposal for the Bradshaw Mountain Marching Bears
Band & Guard, built for handing to local businesses or linking directly.

## Files

- `index.html` — the page
- `style.css` — all styling
- `script.js` — small scroll-reveal effect
- `assets/qr-code.png` — QR code linking to the program site

## Deploying with GitHub Pages

1. Create a new repo (or add this as a folder in an existing one), e.g. `bmhs-sponsorship`.
2. Upload all files in this folder, keeping the `assets` folder intact.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
5. Choose the `main` branch and `/ (root)` folder, then **Save**.
6. GitHub will give you a live URL, usually `https://<your-username>.github.io/<repo-name>/`.
   It can take a minute or two to go live the first time.

## Editing content later

- Dollar amounts and tier benefits are in `index.html` under `<section id="tiers">`.
- The September 1st trailer deadline appears twice: once in the tiers section note,
  once in the contact card. Update both if the date changes.
- Swap `assets/qr-code.png` for a new QR image any time — just keep the same filename,
  or update the `src` in `index.html` if you rename it.
