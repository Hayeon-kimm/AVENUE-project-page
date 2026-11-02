# AVENUE: Audio-Video EditiNg Understanding and Evaluation — Project Page

Static project page for the AVENUE paper (NeurIPS 2026, Evaluations and Datasets track).

## Structure

```
index.html          # main page (title, authors, abstract, Figure 1, empty Results, BibTeX)
style.css           # styling
static/images/      # figures
```

## Publish with GitHub Pages

```bash
cd /home/claude/avenue-project-page
git init -b main
git add .
git commit -m "Initial project page"
gh repo create Hayeon-kimm/AVENUE-project-page --public --source=. --push
```

Then on GitHub: **Settings → Pages → Source: Deploy from a branch → `main` / `(root)`**.
The page will be available at `https://hayeon-kimm.github.io/AVENUE-project-page/`.

## TODO
- Fill in the Results section.
- Replace the `#` placeholder links (
- Update the BibTeX entry after the camera-ready version.
