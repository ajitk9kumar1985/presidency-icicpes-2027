# ICICPES 2027 — Proposed Conference Website

A static, responsive website draft for the proposed International Conference on Intelligent Communication, Photonics and Embedded Systems, to be hosted by Presidency University, Bengaluru.

## Website files
- `index.html` — homepage and conference sections
- `styles.css` — layout, colours and responsive styles
- `script.js` — mobile navigation
- `.github/workflows/pages.yml` — deployment to GitHub Pages

## Publish with GitHub Pages
1. Open this repository on GitHub.
2. Select **Settings** → **Pages**.
3. Under **Build and deployment**, choose **GitHub Actions** as the source (not “Deploy from a branch”).
4. Open the **Actions** tab and inspect the “Deploy conference website to GitHub Pages” workflow. It runs on pushes to `main`; you can also run it manually using **Run workflow** if available.
5. After a successful deployment, open **Settings** → **Pages** to find the published URL. For this repository, the expected URL is `https://ajitk9kumar1985.github.io/presidency-icicpes-2027/`.

A new deployment may take a few minutes. If it fails, open the failed run in **Actions** and read the first error step.

## Editing the website
Edit a file from the repository by opening it and selecting the pencil icon, or upload replacement files. Commit changes to `main`; the deployment workflow will publish the update automatically.

## Before public use
- Confirm the conference title and acronym, dates, venue and technical tracks.
- Replace provisional committee/contact details with approved information.
- Add university logos only with permission.
- Keep all publisher / proceedings language accurate. The current draft says the publication proposal is subject to publisher approval; do not imply Springer has accepted the proposal unless formal approval has been received.
