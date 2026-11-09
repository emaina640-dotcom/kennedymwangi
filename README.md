# Kennedy Mwangi Portfolio Website

A responsive static portfolio website built with HTML, CSS and vanilla JavaScript.

## Files
- `index.html`: website content and structure
- `styles.css`: layout, colours, typography and responsive styles
- `script.js`: mobile navigation and current year
- `assets/kennedy-mwangi.jpg`: profile photograph
- `assets/kennedy-mwangi-cv.pdf`: downloadable CV
- `assets/favicon.svg`: browser icon

## Preview locally
Open `index.html` in a modern browser. For a local server, run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Deploy free with Cloudflare Pages
1. Create or sign in to a GitHub account.
2. Create a new public repository, for example `kennedy-mwangi-portfolio`.
3. Upload the contents of this folder to the repository root.
4. In Cloudflare, open Workers & Pages, choose Create application, then Pages, then Connect to Git.
5. Select the repository. For this plain HTML site, choose no framework preset. Leave the build command blank and set the build output directory to `/`.
6. Deploy. Cloudflare will provide a `*.pages.dev` address and HTTPS.

## Updating the website
Edit `index.html` for text and links. Replace the photograph at `assets/kennedy-mwangi.jpg` using the same filename, and replace the CV at `assets/kennedy-mwangi-cv.pdf` using the same filename. Commit and push changes to GitHub to trigger a new deployment.

## Before publishing
Review the CV file and all dates, figures and employer descriptions. Confirm that you are happy to publish the email address and LinkedIn profile. The contact section intentionally uses email and LinkedIn only; there is no public telephone number or contact form.
