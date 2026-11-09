# Frank Condes — Power Platform Portfolio

A free, responsive, static portfolio for GitHub Pages. No paid hosting, build tools, or third-party dependencies.

## Preview locally
Open `index.html` in your browser. Open `cv.html` for the draft printable CV.

## Publish to GitHub Pages
1. Create a GitHub account at https://github.com if needed.
2. Create a **public** repository named `YOURUSERNAME.github.io` (replace YOURUSERNAME with your exact GitHub username).
3. Choose **Add file → Upload files** and upload `index.html`, `styles.css`, `site.js`, `cv.html`, and the `assets` folder. Commit the files to the `main` branch.
4. Open **Settings → Pages → Build and deployment**. Set **Source** to **Deploy from a branch**, choose **main** and **/(root)**, and Save.
5. Visit `https://YOURUSERNAME.github.io/` after deployment finishes (it can take a few minutes).
6. Add that URL to your CV and LinkedIn.

## Customize your site
- **Contact links:** In `site.js`, fill in `CONTACT.email` and `CONTACT.linkedin`. Both buttons are intentionally placeholders until edited.
- **Project descriptions:** Edit the `projects` array in `site.js` to adjust details, remove projects, or add more.
- **Screenshots:** Put safe, redacted screenshots under `assets/screenshots/`. For a project, change `screenshots:[]` to e.g. `screenshots:['assets/screenshots/progress-1.png','assets/screenshots/progress-2.png']`. The first image appears on its project card; all images appear in the case-study gallery.
- **CV:** `cv.html` is a **draft**, not a verified or final resume. Edit it and use **Print / Save as PDF** in your browser. If you prefer a real downloadable PDF, place your final `cv.pdf` at the site root and change both `href="cv.html"` references in `index.html` to `href="cv.pdf"` (optionally add `download`).
- **Design:** Colors and layout are in `styles.css`.

## Privacy checklist before publishing
- Remove names, email addresses, phone numbers, financial details, account identifiers, and member records from screenshots.
- Avoid posting internal URLs, access tokens, tenant IDs, confidential architecture, or proprietary code.
- Ensure you have permission to publish any employer-owned screenshots or materials; use synthetic data and recreated UI when in doubt.
- Verify all claims and project completion statuses before sharing publicly.

## Note
GitHub Pages hosting is free for public repositories on GitHub Free, subject to GitHub's current service limits and terms. Your public repository files and screenshots are visible to anyone.
