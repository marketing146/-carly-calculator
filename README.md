# Carly — Auto Finance Calculator

## Deploy to GitHub Pages / Netlify
Upload ALL of these together — do not skip any, and keep the folder structure:
- index.html
- 404.html
- config.js
- version.json
- .nojekyll
- assets/ (folder — all images live here now, loaded separately so the app starts instantly)

⚠️ The `assets/` folder must stay a folder named exactly "assets" alongside index.html — 
the app references images as `assets/img_xxxx.jpg`.

## Every future deploy
version.json's "version" value must be bumped to match the new build, or open tabs won't
force-refresh to the new version. (Handled automatically by Claude each build.)

## Supabase
Connected to Supabase project "carly-Calculator". config.js holds the URL + anon key.
