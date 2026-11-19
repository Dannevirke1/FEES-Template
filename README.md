# FEES Documentation Tool

A self-contained, browser-based FEES documentation aid that converts clinician-selected findings into chart-ready narrative text and displays DIGEST-FEES safety, efficiency, and overall severity fields.

## Repository contents

- `index.html` - complete application (HTML, CSS, and JavaScript; no external runtime dependencies)
- `.nojekyll` - tells GitHub Pages to serve the repository as static files without Jekyll processing
- `404.html` - simple fallback page with a link back to the application
- `docs/SOURCES.md` - clinical source and implementation notes
- `SECURITY.md` - privacy/security cautions for clinical use
- `NOTICE.md` - use and attribution notice
- `.gitignore` - common local/editor exclusions

## Publish with GitHub Pages

1. Create a GitHub repository.
2. Upload all files and folders from this package to the repository root.
3. In GitHub, open **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will display the published Pages URL after deployment.

No build step, package manager, framework, or server is required.

## Local use

Open `index.html` directly in a modern browser. The application does not require internet access after the file has been downloaded.

## Clinical use

This is a documentation aid, not an autonomous diagnostic or medical-record system. The clinician remains responsible for verifying observations, DIGEST-FEES grades, generated narrative, recommendations, and final documentation before entry into the medical record.

Do not use GitHub Pages as a place to store patient data. The application is designed to process entries in the browser and does not intentionally send them to a server, but use with PHI must comply with organizational privacy, security, device, and browser requirements.
