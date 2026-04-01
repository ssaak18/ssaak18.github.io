# Personal Website

Static personal portfolio site designed for GitHub Pages.

## Files

- `index.html`: redirects the root URL to the home page
- `home/index.html`: home page with headshot, bio, and social links
- `portfolio/index.html`: portfolio page with project cards
- `resume/index.html`: resume page with embedded PDF and download button
- `styles.css`: black-and-white retro UI styling with sky-blue accents
- `images/`: your headshot and project PNG files
- `assets/`: placeholder images, favicon, and resume PDF
- `.nojekyll`: tells GitHub Pages to serve the site as plain static files

## Deploy on GitHub Pages

1. Push this repository to GitHub.
2. In the GitHub repository, open `Settings` -> `Pages`.
3. Under `Build and deployment`, choose `Deploy from a branch`.
4. Select the branch you want to publish, usually `main`.
5. Set the folder to `/ (root)`.
6. Save, then wait for GitHub Pages to publish the site.

## Customize

- Add your headshot as `images/headshot.png`.
- Add project images as `images/tactic.png`, `images/wamp.png`, `images/nerc.png`, `images/autopilot.png`, `images/critters.png`, `images/frc.png`, `images/website.png`, and `images/dog.png`.
- Update the bio and external links in `home/index.html`.
- Update the project cards in `portfolio/index.html`.
- Update the resume page in `resume/index.html` if you change filenames.
- Replace `assets/resume-placeholder.pdf` with your real resume PDF.
