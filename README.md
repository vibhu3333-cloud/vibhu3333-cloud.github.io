# Vibhu Vikramaditya — GitHub Pages Website

A clean static personal academic website for GitHub Pages.

## Files

- `index.html` — homepage
- `research.html` — research program and working papers
- `writing.html` — public writing and essay themes
- `cv.html` — web CV
- `contact.html` — contact page
- `404.html` — custom not-found page
- `styles.css` — all styling
- `site.js` — mobile menu and small UI behavior
- `CNAME` — custom domain file for `vibhuvikramaditya.com`
- `.nojekyll` — tells GitHub Pages to serve the files directly

## How to publish on GitHub Pages

1. Create a GitHub repository named `vibhu3333.github.io`.
2. Upload all these files to the repository root, not inside an extra folder.
3. Go to repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/root`, then save.
6. Your site should appear at `https://vibhu3333.github.io/`.
7. For the custom domain, keep the included `CNAME` file and add DNS records in Cloudflare for `vibhuvikramaditya.com` according to GitHub Pages custom domain instructions.

## Editing notes

- Replace placeholder working-paper status labels when PDFs or SSRN links are ready.
- Optional: put your CV PDF at `Vibhu-Vikramaditya-CV.pdf` and uncomment/add the download button in `cv.html`.
- Replace or add links to your author pages in `writing.html`.
- Add a real portrait later by replacing the `VV` placeholder in `index.html` with an image.
