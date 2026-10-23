# Material Muse — Portfolio Website

A responsive editorial-style portfolio for Monika Starczowski, built with plain HTML, CSS and JavaScript.

## Files
- `index.html` — page content and metadata
- `styles.css` — layout, responsive styles, typography and motion
- `script.js` — mobile navigation, image lightbox and current year
- `assets/` — the five artwork photographs supplied for this portfolio

## Run locally
1. Unzip the project.
2. Open `index.html` in a browser.
3. For the most reliable local preview, run a small static server from this folder:
   - Python: `python -m http.server 8000`
   - Then open `http://localhost:8000`

The site has no build step and no JavaScript dependencies. Google Fonts are loaded from the web; system fonts remain as fallbacks if offline.

## Before publishing
1. Replace `hello@materialmuse.example` with Monika's real email address.
2. Replace the generic Instagram link with her real profile URL.
3. Confirm the biography and artwork descriptions reflect her own preferred wording.
4. Check that she is happy for these photos and name to be published.
5. Optional: add a favicon, social preview image, and a custom domain.

## Free deployment with GitHub Pages
1. Create a GitHub repository and upload the contents of this folder (not the ZIP file).
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site. It will provide the public URL in Settings → Pages.

You can also deploy this folder to Vercel as a static site. No framework preset or build command is required; use the project root as the output directory.
