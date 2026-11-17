# Nitesh Cyber — website

One-page website for **Nitesh Cyber**, a CSC e-Governance centre at Lalbag, Darbhanga (Bihar).

- Live site: https://shresthaxcoder.github.io/niteshcyberwork/
- Phone / WhatsApp: +91 78703 00293
- Email: nitdbg@gmail.com
- Address: C/o Naveen Electronics, opposite Nerolac Paints, near C.M. Science College, Lalbag, Darbhanga, Bihar 846004

## Editing the site

Everything lives in `index.html` — a single self-contained file (styles, script, logo and photos are inline).
Search for `78703 00293`, `nitdbg@gmail.com` or the address block to change contact details.

### Posting an update / announcement

Find `id="updates"` in `index.html`. Each announcement is one `<article class="upd rv">` block.
Copy an existing block, change the tag, the date and the text. Add class `upd--new` and a
`<span class="badge-new">New</span>` for the newest item, and remove them from older ones.
Then update the "Last checked" date under the section heading.

### Swapping photos and logo

Replace the `data:image/jpeg;base64,...` values to change the shop photos, and the
`data:image/png;base64,...` values for the logo. Standalone assets: `logo.png` (white background),
`logo-transparent.png` (for dark backgrounds), `favicon-32.png`, `apple-touch-icon.png`.

## Publishing

GitHub Pages serves the `main` branch root. Push to `main` and the site updates in about a minute.
