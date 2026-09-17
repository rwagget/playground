# Playground

Small experiments, all in one repo. Live at https://rwagget.github.io/playground/

## Adding an experiment

1. Create a folder `experiments/<slug>/` with an `index.html` inside.
2. Add an entry to `experiments.json` (slug, title, description, date).
3. Commit and push — the hub updates automatically.

Plain HTML/CSS/JS, no build step. To preview locally: `python3 -m http.server` in this folder, then open http://localhost:8000.
