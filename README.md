# Pizza Lab: From Dough to Oven

A free, independently developed home-pizzeria tool with a pizza dough calculator and baking workshop. Inspired by [Dough Guy](https://doughguy.co).

## Features
- Diameter and quantity sliders; thin, classic and thick dough weights
- Fermentation presets, baker's percentages, live ingredient weights, and recipe printing
- Decorative pizza-base themes, selectable toppings and randomize button (visual only)
- Independent warm-up, preheat and baking timers with pause/reset
- Pizza journal: ratings, dough behavior, baking results, oven details, optional elevation, free-form notes
- Recipe history: save, reload, review and delete attempts
- Export/import journal JSON to back up records or move between devices
- Contextual troubleshooting tips for dough and oven behavior, including high-elevation context
- Direct credits and verified links to Dough Guy's video tutorials and learning library

## Repository structure
```
index.html
README.md
UPLOAD_INSTRUCTIONS.txt
```
No bundler, hosting backend, API key or account is required. All code and styles are in `index.html`.

## Deploy on GitHub Pages
Create a **public** repository called `pizza-dough-lab` under `jkramer-cloud`, or update that existing repository.
Upload **the contents** of this ZIP at repository root, not the ZIP itself.
Enable **Settings → Pages → Deploy from a branch → main → /(root)**.

Public URL: https://jkramer-cloud.github.io/pizza-dough-lab/

## Important notes
- Pizza Lab is not affiliated with Dough Guy. His content is linked as an external resource, not copied.
- Dough recipes and baking guidance are educational starting points, not guaranteed or professionally validated formulas. The gluten-free option is explicitly experimental.
- Pizza appearance/topping settings are cosmetic; they do **not** alter ingredient calculations.
- Timers use elapsed wall-clock time and can restore after a reload, but audible alarms require the page to remain active and cannot replace supervision.
- Journal records are stored in the **browser's localStorage**, not a cloud account. Different browsers, profiles or devices do not automatically share history. Export JSON backups before clearing browser data.
- On shared school computers, journal entries are visible to people using the same browser profile. Avoid personal/sensitive notes.
- At high altitude, fermentation and moisture needs vary; suggestions are conditional and intended for testing one variable at a time.
