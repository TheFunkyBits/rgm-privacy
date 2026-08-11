# Retro Games Mobile privacy policy

This public repository preserves the original privacy-policy URL for the Android application
Retro Games Mobile (`dev.thefunkybits.rgm`). Its static page redirects to the unified RGM site.

The canonical policy URL is:

<https://thefunkybits.github.io/rgm/privacy/>

The compatibility URL remains <https://thefunkybits.github.io/rgm-privacy/>. The deployable
source is limited to a static redirect and styles. A GitHub Actions workflow validates those
files and publishes them to GitHub Pages.

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
