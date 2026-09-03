# PostAgentAshbyAsh

Static marketing site + privacy policy for the **PostAgentAshbyAsh** Meta Platform app.
Served from the repo root via GitHub Pages at <https://postagentforashbyash.itsash.in>.

## Structure
- `index.html` — landing page
- `privacy.html` — Facebook app privacy policy
- `public/` — favicon (`icon.svg`) and `styles.css`
- `Makefile` — `run` (local server), `build` (no-op), `deploy` (commit + push)

## Local
```bash
make run    # http://localhost:8000
```

## Deploy
GitHub Pages serves from `main` root. `make deploy` commits and pushes to `main`.