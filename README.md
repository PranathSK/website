# Pranath S. Karanth — personal website

A responsive, static academic profile site based on the structure and content of the existing Google Site. It uses plain HTML, CSS, and JavaScript, so there is no build step or package installation.

## Preview locally

Open `index.html` in a browser, or run a simple local server from this folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a GitHub repository for the website. If you want the address `https://YOUR-USERNAME.github.io`, name the repository `YOUR-USERNAME.github.io`; otherwise GitHub will use `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.
2. Add the files in this folder to the repository and push them to the `main` branch.
3. In the repository, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**.
4. The included workflow at `.github/workflows/deploy.yml` will deploy the site. Check the **Actions** tab for the first run; the deployed address appears in **Settings → Pages**.
5. Afterward, every push to `main` publishes the new version.

## Update your details

Edit `index.html` to update text, email, and links. Change appearance in `styles.css`; interactions are in `script.js`. The Google Drive links currently point to the same public documents as the reference site. Confirm they are still the intended files and have visitor access before launch. Review year-specific details such as the expected graduation date and teaching roles so they reflect your current status.

## Included files

- `index.html` — content and page structure
- `styles.css` — responsive layout and visual design
- `script.js` — mobile navigation and current-year footer
- `assets/favicon.svg` — small site icon
- `.github/workflows/deploy.yml` — deploys the static site to GitHub Pages
