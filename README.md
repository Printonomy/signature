# Printonomy — Email Signature

Exchange / Outlook email signature template with image assets hosted via **GitHub Pages**.

## Live preview

👉 [https://printonomy.github.io/signature/](https://printonomy.github.io/signature/)

## Repository structure

```
signature/
├── index.html                          # GitHub Pages preview & instructions
├── signature.html                      # Exchange / Outlook HTML template
├── .nojekyll                           # Disables Jekyll so all files are served as-is
└── assets/
    └── images/
        ├── logo.svg                    # Printonomy logo
        ├── social-facebook.svg         # Facebook icon
        ├── social-instagram.svg        # Instagram icon
        └── social-linkedin.svg         # LinkedIn icon
```

## Quick start

1. Open `signature.html` and copy the `<table>…</table>` block.
2. In **Outlook**: *File → Options → Mail → Signatures → New*, paste the HTML.
3. Replace the `[YOUR NAME]`, `[YOUR TITLE]`, `[YOUR PHONE]` and `[YOUR EMAIL]` placeholders.
4. Save and assign the signature to your account.

## Image assets via GitHub Pages

All images are served from:

```
https://printonomy.github.io/signature/assets/images/
```

Updating an asset is as simple as replacing the file in `assets/images/` and pushing to `main` — all signatures pick up the new version automatically on next load.

## Customizing

| Placeholder | Replace with |
|---|---|
| `[YOUR NAME]` | Full name |
| `[YOUR TITLE]` | Job title |
| `[YOUR_PHONE]` | Phone number (also update `href="tel:…"`) |
| `[YOUR EMAIL]` | Email address (also update `href="mailto:…"`) |
| `[YOUR ADDRESS]` | Office address |

To replace the logo, swap `assets/images/logo.svg` (or add a `logo.png`) and update the `src` attribute in `signature.html`.