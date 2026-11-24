# Zachariah Luna — Portfolio

Plain HTML + CSS. No build step, no frameworks. Edit a file, upload it, done.

## Folder layout

```
index.html              Home
projects.html           Project cards
experience.html         Jobs + education
audio.html              Event audio (optional — delete it and its nav link if unused)
404.html                "Page not found"
projects/
  _template.html        Copy this for every new project
  residential-electrification.html
  dc-microgrid.html
  event-power-box.html
css/style.css           All styling (colors are at the top in :root)
assets/
  resume.pdf            ← replace with your real résumé (same name)
  favicon.svg
  img/                  Photos, charts, diagrams
.nojekyll               Tells GitHub Pages to serve files as-is
```

## First edits before publishing

1. **Email + GitHub links.** Find and replace `your.email@example.com` and `YOUR-GITHUB-USERNAME` in every `.html` file (VS Code: Ctrl/Cmd+Shift+H replaces across all files).
2. **Résumé.** Save your résumé as `assets/resume.pdf`, overwriting the placeholder.
3. **Photo.** Already in place (`assets/img/profile.jpg`). To change it, replace that file with another square photo, about 600×600 px and under 150 KB.
4. **Dashed "TO DO" boxes** mark spots to fill in. Delete each one once you've written that part.

## Adding a project

1. Copy `projects/_template.html` → `projects/my-project.html`.
2. Fill in Problem → Design → Build → Results → Lessons learned.
3. Put images in `assets/img/` and reference them as `../assets/img/name.jpg`.
4. Add a card to `projects.html` (copy an existing `<a class="card">` block).

**Image tips for a fast site:** photos as JPG, ~1600 px wide max, under 300 KB. Charts as SVG or PNG (matplotlib: `plt.savefig("chart.svg")`).

## Preview locally

Double-click `index.html` to open it in a browser. (Only `404.html` needs the live site to look right.)
