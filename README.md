# NutriScan legal pages

Privacy policy and terms of use for NutriScan, served by GitHub Pages.

- Privacy policy: https://crypt1cmirag3.github.io/nutriscan-legal/privacy.html
- Terms of use: https://crypt1cmirag3.github.io/nutriscan-legal/terms.html
- Account deletion (for Play): https://crypt1cmirag3.github.io/nutriscan-legal/privacy.html#delete-account

## One-time setup

1. github.com → New repository → name `nutriscan-legal`, **Public**, no
   README. (Your app repo stays private.)
2. Copy this folder's files (`index.html`, `privacy.html`, `terms.html`,
   `.nojekyll`, `README.md`) into a new local folder, then:
   ```
   git init -b main
   git add -A
   git commit -m "Privacy policy and terms"
   git remote add origin https://github.com/crypt1cmirag3/nutriscan-legal.git
   git push -u origin main
   ```
3. Repo → Settings → Pages → Source: **Deploy from a branch**, branch
   `main`, folder `/ (root)` → Save. After a minute the URLs above work.


