# Friscora — Support page

Static support site for the Friscora iOS app. Deploy as GitHub Pages (or any static host).

## Contents

- `index.html` — FAQ, contact, and links to Privacy and Landing.

## Deploy (GitHub Pages)

1. Create a repository named `friscora-support` (or your chosen name).
2. Put `index.html` at the **repository root** (not inside a subfolder), or enable Pages from `/docs` and place the file there per GitHub’s docs.
3. In **Settings → Pages**, choose the branch/folder that serves the site.
4. Update any hardcoded URLs in `index.html` if your repo name or username differs from `niyazovdaulet.github.io/friscora-support`.

## Before you publish

- Replace the support email (`mailto:…`) if you use a different address.
- Confirm links to Privacy and Landing match your live URLs.

## Local preview

Open `index.html` in a browser, or run a static server from this directory:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.
