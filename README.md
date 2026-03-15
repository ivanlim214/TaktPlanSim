# Takt Planning Tool

A browser-based **Takt Planning** tool for Lean Construction scheduling.  
No build step, no server — just open `index.html`.

## Live Demo

Click the link to start the Demo

## Features

- **6-step workflow** — Project setup → Zones & Sub-zones → Trade sequence → Balance → Visualise → Sign-off  
- **Sub-zone scheduling** — Trades flow through each sub-zone individually (e.g. Floor 1 → Apt 1A, 1B, 1C)  
- **5 visualisation views** — Trade Flow · Zone Wagon · Line of Balance · Date Status · Gantt  
- **Scrum Board** — Sticky-note Kanban with drag-and-drop between Backlog / In Progress / At Risk / Done; switch between By Trade and By Zone layouts  
- **Plan Recommendations** — Lean optimisation suggestions with Little's Law interactive diagram  
- **Trade library** — 30+ pre-built trades across Structure, Envelope, MEP, Interior, External  
- **Auto-generate sub-zones** — Numeric, alphabetic, or AA-style naming  
- **Bulk sub-zone entry** — Paste comma- or newline-separated lists  

## Deploying to GitHub Pages

1. Create a new repository on GitHub  
2. Upload `index.html` (and optionally this `README.md`) to the root  
3. Go to **Settings → Pages → Source** → set branch to `main`, folder to `/ (root)`  
4. Click **Save** — your site will be live at `https://<username>.github.io/<repo>/`

## Local Use

Just open `index.html` in any modern browser — no server needed.

```bash
# Or serve locally with Python
python3 -m http.server 8080
# Then open http://localhost:8080
```

## Technology

| Library | Version | Purpose |
|---------|---------|---------|
| React | 18 | UI framework |
| ReactDOM | 18 | DOM rendering |
| Recharts | 2.12.7 | Line-of-Balance & charts |
| Babel Standalone | latest | In-browser JSX transpilation |

All loaded from CDN — no `npm install` required.

## Browser Support

Chrome 90+, Firefox 88+, Edge 90+, Safari 14+
