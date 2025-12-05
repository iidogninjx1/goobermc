# Minecraft Server Info — Single-file page

This repository contains a single-file, responsive HTML page used to share Minecraft server addresses with quick copy buttons.

Files
- `index.html` — main page (self-contained: markup, styles, and inline JavaScript). Open this file directly in a browser or serve it from a static host.

Quick start
1. Open locally:

```bash
open "$(pwd)/index.html"
```

2. Or serve with a simple static server (recommended for clipboard behavior):

```bash
# from the repo root
python3 -m http.server 8000
# then open http://localhost:8000/index.html
```

GitHub Pages
- If this repository is published with GitHub Pages from the `main` branch (root), the site will be available at:

	https://iidogninjx1.github.io/goobermc/

Notes
- The page stores values in `localStorage` (if used) and provides copy-to-clipboard buttons for Java and Bedrock addresses.
- JavaScript is inline in `index.html` to keep the page highly portable.

License
This project is dedicated to the public domain under the CC0 1.0 Universal (CC0 1.0) Public Domain Dedication.

You can copy, modify, distribute, and perform the work, even for commercial purposes, all without asking permission.

See the full license in `LICENSE`.
