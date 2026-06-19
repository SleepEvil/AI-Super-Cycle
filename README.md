# AI Capex Dashboard

Static dashboard for tracking AI capex, hyperscaler demand, ecosystem companies, and portfolio exposure.

## Publish Options

### Fastest: Netlify Drop

1. Go to https://app.netlify.com/drop
2. Drag this whole folder onto the page.
3. Netlify gives you a public URL.

This is the quickest way to share the dashboard, but future updates are manual unless you connect a Git repo.

### Best Free Git Workflow: GitHub Pages

1. Create a public GitHub repository.
2. Upload/push these files:
   - `index.html`
   - `ai-ecosystem-map.svg`
   - `ai-ecosystem-map.png`
   - `.nojekyll`
3. In GitHub: `Settings` -> `Pages`.
4. Set source to deploy from the `main` branch and root folder.
5. Open the published URL GitHub provides.

### Also Good: Vercel or Cloudflare Pages

Use this as a static site with:

- Build command: leave blank
- Output directory: `.`
- Install command: leave blank

## Privacy Note

Anything in this folder becomes public once deployed. Remove screenshots or sensitive portfolio details before publishing if you do not want others to see them.
