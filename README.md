# Parth Gurav — Portfolio

Single-page responsive portfolio for **Parth Gurav** (2nd-year Computer Engineering student at Dr. D. Y. Patil College of Engineering and Innovation, SPPU, Pune).

## Included Files
- `index.html` — Complete portfolio (HTML, CSS, and vanilla JavaScript)
- `public/assets/aistudio/` — Profile photo and SmartBridge / NASSCOM certificate PDF
- `netlify.toml` — Ready-to-use Netlify build and security headers configuration
- `.github/workflows/deploy.yml` — Automatic GitHub Pages deployment workflow
- `vercel.json` — Ready-to-use Vercel static build configuration

## Build Locally
```bash
npm install
npm run build
```
The production static site is generated inside the `dist/` folder (containing `index.html` and `assets/`).

## Deploy for Free

### Option 1: GitHub Pages (Automatic via GitHub Actions)
1. Push this project to a GitHub repository on the `main` branch.
2. Open your repository on GitHub and go to **Settings → Pages**.
3. Under **Build and deployment → Source**, select **GitHub Actions**.
4. Every push to `main` automatically builds and publishes the site via `.github/workflows/deploy.yml`.

### Option 2: Netlify (Drag & Drop or Git)
- **Fastest (No Git needed):** Run `npm run build`, open [app.netlify.com/drop](https://app.netlify.com/drop), and drag the `dist/` folder onto the page.
- **Git-connected:** Connect your GitHub repo in Netlify; `netlify.toml` automatically sets `npm run build` and publishes `dist/`.

### Option 3: Vercel
- Import the GitHub repository on [vercel.com](https://vercel.com); `vercel.json` automatically configures the build and `dist/` output.
