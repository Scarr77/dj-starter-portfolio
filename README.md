# DJ Starter Portfolio

A clean starter repo for your brand(s): music, projects, and a simple static website you can deploy to **GitHub Pages**.

## What’s inside
- **/website** — static landing page (baby blue & black vibe) you can deploy with GitHub Pages.
- **/music** — release checklist & README scaffold.
- **/brands** — brand notes & assets folder placeholder.
- **.github/** — issue templates, PR template, and a GitHub Pages workflow.

## Quick start
```bash
# 1) Rename the folder to whatever repo name you want
# 2) Initialize and push
git init
git add .
git commit -m "Initial commit: starter portfolio"
# If you created an empty repo on GitHub (replace with your URL)
git remote add origin https://github.com/USERNAME/REPO.git
git branch -M main
git push -u origin main
```

### Enable GitHub Pages
- Go to **Settings → Pages** on your repo and set:
  - **Source**: GitHub Actions
- The included workflow `.github/workflows/pages.yml` will publish the `website` folder to Pages.

## Customize
- Edit **website/index.html** (hero text, links, socials).
- Drop logos and images in **website/assets**.
- Update **music/README.md** with your release plan.
- Add your brand strategy in **brands/README.md**.
