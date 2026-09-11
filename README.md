# Derrick Automotive

A single-page website for Derrick Automotive, a premium car care and repair
garage in Kampala, Uganda.

## What's inside

- `index.html` — the entire site (HTML, CSS, and images all in one file, no
  build step required).

## Running it locally

No build tools needed. Just open `index.html` in a browser, or serve it with
any static file server, e.g.:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying with GitHub Pages

1. Push this repo to GitHub (see below).
2. On GitHub, go to **Settings → Pages**.
3. Under "Build and deployment", set **Source** to `Deploy from a branch`,
   branch `main`, folder `/ (root)`.
4. Save — GitHub will publish the site at
   `https://<your-username>.github.io/<repo-name>/`.

## Editing

- Colors and typography are set as CSS custom properties near the top of the
  `<style>` block in `index.html`.
- Contact details (phone, email, address) live in the booking and footer
  sections — search for `+256 700 000 000` to find and replace the
  placeholder number.
- Photos are embedded directly as base64 data so the file has no external
  image dependencies.
