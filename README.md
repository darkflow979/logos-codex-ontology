
# Logos Codex — Interactive Ontology

A minimal static site that renders your ontology as a clickable graph using [vis-network](https://visjs.org/).

## Files
- `index.html` — the app (loads `data.json` and renders the graph)
- `data.json` — your ontology (nodes + edges)

## Local Preview
Just open `index.html` in a browser, or use any static server:

```bash
# Python 3
python -m http.server 8080
# then open http://localhost:8080
```

## Update the Graph
Replace `data.json` with an updated export and refresh.

## Deploy to GitHub Pages
1. Create a repo (e.g., `logos-codex-ontology`).
2. Upload `index.html` and `data.json` to the repo root.
3. In GitHub: Settings → Pages → "Deploy from a branch" → select `main` / root.
4. Your site will be live at `https://<your-username>.github.io/logos-codex-ontology/`.
5. Embed that URL into Notion with `/embed`.
