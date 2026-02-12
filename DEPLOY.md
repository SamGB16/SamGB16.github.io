Deployment notes (scaffold):

## Quick Deploy Options

- Netlify Drop: drag the `site` folder to Netlify for an instant deploy (no repo needed).

- Netlify (recommended):
	1. Push the `site` folder to a GitHub repo (root contains `index.html`).
	2. Connect the GitHub repo to Netlify and set the publish directory to the repo root.
	3. Netlify will auto-deploy on pushes to the connected branch.

- GitHub Pages (alternative):
	1. Push `site` contents to the `gh-pages` branch or the repository root and enable Pages in repo settings.
	2. No build step required for this static site.

## Notes
- For the single-file MVP there is no build step. If we adopt 11ty later, add a build command in Netlify.
- Add simple analytics later (Plausible or Google Analytics) and a Netlify form or mailto for contact.
