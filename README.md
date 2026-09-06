# Money Hero 理財小英雄

GitHub-ready static website + PWA prototype.

## Files

- `index.html` — main website
- `manifest.json` — PWA configuration
- `sw.js` — offline cache/service worker
- `assets/icons/` — app icons
- `.github/workflows/deploy-pages.yml` — GitHub Pages deployment
- `.nojekyll` — keeps GitHub Pages from processing the site with Jekyll

## Publish on GitHub Pages

1. Create a new GitHub repository, e.g. `money-hero`.
2. Upload **all files and folders** from this project.
3. Commit to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **GitHub Actions**.
6. Open the **Actions** tab and let the deployment workflow run.

Your site will normally be available at:

`https://YOUR-USERNAME.github.io/money-hero/`

## Install as an app

Once published over HTTPS:

- Android / Chrome: choose **Install app** or **Add to Home screen**
- iPhone / Safari: Share → **Add to Home Screen**

## Local PWA testing

Run:

```bash
python -m http.server 8080
```

Then open:

`http://localhost:8080`

## Next MVP stage

The current project is still a front-end prototype. A real MVP should add:

- Parent registration/login
- Child profiles and PIN
- Supabase/PostgreSQL
- Wallet transactions
- Savings goals
- Lessons and quiz progress
- XP and badges
- Parent tasks / allowance
- Virtual investment data
