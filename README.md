# Minecraft Server Info — Single-file page

This repository contains a single-file, responsive HTML page used to share Minecraft server addresses with quick copy buttons.

Files
- `stuff.html` — main page (self-contained: markup, styles, and inline JavaScript). Open this file directly in a browser or serve it from a static host.

Quick start
1. Open locally:

```bash
open "$(pwd)/stuff.html"
```

2. Or serve with a simple static server (recommended for clipboard behavior):

```bash
# from the repo root
python3 -m http.server 8000
# then open http://localhost:8000/stuff.html
```

Notes
- The page stores values in `localStorage` (if used) and provides copy-to-clipboard buttons for Java and Bedrock addresses.
- JavaScript is inline in `stuff.html` to keep the page highly portable.

License
This project is provided as-is.