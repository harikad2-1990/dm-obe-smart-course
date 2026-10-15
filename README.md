# U23CS706 Data Mining — OBE Smart Course Website

Project title: **An AI-Enabled Framework for Outcome-Based Smart Course Design, Automated CO-PO Mapping & Adaptive Content Generation**

## Publish on GitHub Pages
1. Sign in at https://github.com and create a **public** repository named `dm-obe-smart-course`.
2. Upload the contents of this folder (make sure `index.html` is in the repository root).
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
5. Wait for the deployment and check the repository's **Actions** tab if it fails.
6. The expected URL format is `https://YOUR-USERNAME.github.io/dm-obe-smart-course/`. This is a template, not a verified live link; a repository must be created and deployment must succeed first.

## Files
- `index.html` — course portal and syllabus map
- `styles.css` — responsive visual design
- `script.js` — search, support/confidence calculator, method selector, quiz
- `README.md` — deployment guide

## Syllabus fidelity notes
Built from the supplied one-page U23CS706 Data Mining syllabus. The classification section is printed as “UNIT - I” in the scan; verify the official numbering. The contact-hour/credit row is unclear in the scan. CO–PO mapping and the semester calendar are proposed, not official. Research citations and institutional details should be verified/filled in before submission.

## Technical note
This is a static site and works on GitHub Pages. It does not collect or transmit student data. External Google Fonts are optional; if offline use is required, remove the `@import` in `styles.css`.
