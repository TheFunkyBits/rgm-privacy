# Retro Games Mobile privacy policy

This public repository contains the privacy policy for the Android application
Retro Games Mobile (`dev.thefunkybits.rgm`).

The canonical policy URL is:

<https://thefunkybits.github.io/rgm-privacy/>

The deployable source is deliberately limited to `site/index.html` and
`site/styles.css`. A GitHub Actions workflow validates those files and publishes
them to GitHub Pages. The page contains no JavaScript, analytics, forms, remote
media, or application-operated service.

## Local preview

From the repository root:

```powershell
python -m http.server 8000 --directory site
```

Then open <http://127.0.0.1:8000/>.

## Publishing

Pushes to `main` that change `site/` or the Pages workflow trigger deployment.
GitHub Pages must use **GitHub Actions** as its build source. No repository
secret or custom domain is required.

Before every application release, review this policy together with the app's
Google Play disclosures and verified runtime behavior. Update the policy before
distributing any release that changes data access, retention, networking,
accounts, analytics, advertising, or cloud functionality.

This repository is public by design. Never add legal-address source files,
keystores, passwords, tester identities, private release policy files, selected
software, saves, or generated release packets.

No licence is granted for reuse of this repository's content unless one is
added explicitly in the future.
