# Murad Khan — Developer Portfolio

A responsive, dark-premium personal portfolio built with plain HTML, CSS, and JavaScript. No framework, build step, or package installation is required.

## Included
- `index.html` — page structure and portfolio content
- `styles.css` — responsive dark navy/blue styling
- `script.js` — mobile navigation and current year
- `assets/` — portfolio photo asset

## Run locally
1. Extract the ZIP file.
2. Open the `murad_portfolio` folder.
3. Double-click `index.html` to open it in a browser.

For a more realistic local server, open the folder in VS Code and use the **Live Server** extension, then choose **Open with Live Server**.

## Publish online for free
### GitHub Pages
1. Sign in to GitHub and create a new repository (for example, `murad-portfolio`).
2. Upload all files and folders from this project. Keep `index.html` at the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. After GitHub publishes the site, it will show the public website URL in the Pages settings.

### Netlify
1. Sign in to Netlify.
2. Choose **Add new site / Deploy manually**.
3. Drag the extracted `murad_portfolio` folder into the deploy area.
4. Netlify will provide a public URL.

## Personalize before publishing
- Confirm the exact printed names of both certificates; the current wording follows the details supplied.
- Replace the AI College Assistant project description with its final features, repository, and demo link when ready.
- The contact section currently shows the email, GitHub, LinkedIn, and phone number supplied.
- The profile image generated for the portfolio is used in the hero section. If it does not appear, check the file inside `assets/` and ensure the filename matches the image `src` in `index.html`.
- Update text in `index.html` and design tokens at the top of `styles.css` as your profile grows.

## Notes
- Google Fonts are loaded from Google Fonts, so typography falls back to system fonts if offline.
- No contact form is included; the email button opens the visitor's default email application.
- This is a static website. It does not collect or store visitor information.
