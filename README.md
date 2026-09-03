# Nourish & Rest Co. — site files for GitHub Pages

This folder has everything needed to publish the site with GitHub Pages, a free static-site host from GitHub with no bandwidth/credit metering.

## Files
- `index.html` — homepage
- `lactation.html` — lactation counseling page
- `potty.html` — potty training page
- `sleep.html` — sleep consulting page

All internal links are relative filenames (e.g. `href="lactation.html"`), so they work as-is once the files sit together at the root of a repo — no editing needed.

## How to publish (a few minutes, no command line needed)
1. Go to https://github.com/new and create a new repository (any name, e.g. `nourish-rest-site`). Public repos get free Pages hosting; private repos need a paid plan for Pages.
2. On the new repo's page, click **Add file → Upload files**, then drag in `index.html`, `lactation.html`, `potty.html`, and `sleep.html` (skip this README, or include it — it won't affect the site). Commit the upload.
3. Go to the repo's **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**. Under **Branch**, pick `main` and folder `/ (root)`, then **Save**.
5. GitHub gives you a URL like `https://<your-username>.github.io/<repo-name>/` — it takes a minute or two to go live after the first save.

Optional: add a custom domain later under the same Settings → Pages page.
