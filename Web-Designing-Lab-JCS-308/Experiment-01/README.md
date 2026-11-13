# Experiment 01 — Git & GitHub

## Run locally
Open `index.html` in a browser.

## Git workflow
```bash
git init
git add .
git commit -m "Initial website"
git branch -M main
git checkout -b feature-home
# make a change, then commit it
git add . && git commit -m "Add home workflow"
git checkout main
git merge feature-home
git remote add origin https://github.com/j25ds167-dotcom/Web-Designing-Lab-JCS-308.git
git push -u origin main
```
Enable GitHub Pages from Settings → Pages → Deploy from branch → `main` / root.
