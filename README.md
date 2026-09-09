# Agentic STAR: project page

Static HTML/CSS/ES modules, no build step. GitHub Pages serves the repo root.

## Checking the page

```
python -m http.server 8765 --protocol HTTP/1.1   # in this directory, then open http://127.0.0.1:8765/
python scripts/smoke_test.py          # headless check of every carousel; needs: pip install playwright && playwright install chromium
```
