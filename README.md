Sleeper Trade Assistant – GitHub Pages
=====================================

How to deploy
-------------

1. Create a new GitHub repository.
2. Upload the contents of this `github/` folder to the repo root (so that `index.html` sits at the repository root).
3. In the repository: Settings → Pages → set Source to “Deploy from a branch”, choose your default branch and `/ (root)`.
4. Wait for the Pages build to finish. Your site will be available at `https://<your-username>.github.io/<repo-name>/`.

Notes
-----

- This `index.html` uses CDN scripts (React, ReactDOM, Babel, Tailwind), so no extra files or build steps are required.
- Use the “Upload FantasyPros CSV” button to load your rankings file at runtime.
- If the page stays blank, check the red error box on the page and the browser developer console.


