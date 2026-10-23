# Dewy Bank Workshop Setup

An interactive, single-page setup guide for the **Dewy Bank** hands-on workshop
(a Workato workshop on securing AI agents).

The page walks you through deploying the workshop's three stations to your own
Workato workspace and wiring the bank app's chat to its six MCP servers. You can
follow it manually or hand the generated prompt to a coding agent.

## Hosting

This is a static site — a single self-contained `index.html` with inline CSS and
JavaScript. It is published with GitHub Pages.

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```
