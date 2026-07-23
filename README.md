# Carly — Auto Finance Calculator

## Deploy to Netlify / GitHub Pages
Upload ALL of these files together — do not skip any:
- index.html
- 404.html
- config.js  (Supabase connection — app falls back to local mode if missing)
- version.json  (force-update — app falls back to no-auto-update if missing, still works fine)
- .nojekyll  (GitHub Pages only)

## ⚠️ IMPORTANT — every future deploy
Every open tab on every device checks version.json and force-refreshes when it changes.
This means: **every time you deploy a new version, version.json's "version" value MUST be
bumped to match the new build**, or open tabs won't detect the update and won't refresh.
(This is handled automatically by Claude in each new build going forward.)

## Supabase
Connected to Supabase project "carly-Calculator". config.js holds the URL + anon key.
Row Level Security policies control access — the key itself is not a secret.
