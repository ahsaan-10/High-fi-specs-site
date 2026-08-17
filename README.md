# Editorial Punk — portfolio site

Static site. No build step: `index.html` + `support.js` + `assets/`.

## Push to GitHub
```bash
cd deploy-folder
git init
git add .
git commit -m "Portfolio site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```
(Or on github.com: New repository -> "uploading an existing file" -> drag this folder's contents in.)

## Go live with GitHub Pages
Repo -> Settings -> Pages -> Source: "Deploy from a branch" -> Branch: `main`, folder `/ (root)` -> Save.
Site appears at `https://YOUR-USERNAME.github.io/YOUR-REPO/` in ~1 minute.

## Custom domain
Settings -> Pages -> Custom domain -> enter your domain, then add a CNAME record at your DNS pointing to `YOUR-USERNAME.github.io`.

## Before going live
- Replace the `#` hrefs on the two "book a call" buttons with your booking link (Calendly etc).
- Update the og:image URL in `index.html` to your live URL if sharing previews look wrong.
