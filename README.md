## Sai Karthik Kocherlakota – React Portfolio

This repository contains a modernised, single‑page portfolio built with **React** and vanilla CSS. It retains the colourful anime‑inspired aesthetic from the original site, but uses React components to organise the content and provide an interactive user experience.

### Running locally

Because this project is written as a standalone HTML file using React via CDN, you don't need Node.js or a build tool. Simply open `index.html` in your browser and everything will load:

```bash
git clone <this‑repo>
cd <this‑repo>/anime_react
open index.html  # or double‑click the file in your file explorer
```

The page will render using React and Babel loaded from CDNs.

### Deploying to GitHub Pages

1. Create a new repository on GitHub (e.g. `my‑portfolio`).
2. Copy the contents of the `anime_react` folder (including `index.html`, `Image 1.jpg`, and this `README.md`) into the root of your repo.
3. Commit and push to the `main` branch.
4. Go to **Settings** → **Pages**. Under **Source**, select the `main` branch and the root `/` directory. Save your changes.
5. After a few minutes, your portfolio will be live at `https://<username>.github.io/<repo‑name>/`.

### Deploying to Netlify

1. Sign in to [Netlify](https://www.netlify.com) and choose **Add new site** → **Deploy manually**.
2. Drag the contents of the `anime_react` folder into the upload area.
3. Netlify will deploy your site and give you a public URL instantly. You can optionally add a custom domain.

### Tech stack

The portfolio is built using:

- **React 18** – loaded from unpkg CDN and compiled in the browser using Babel.
- **Vanilla CSS** – no external frameworks, with CSS variables, grids and flexbox for layout.
- **Babel** – transpiles JSX in the browser. For production, consider pre‑compiling.

### Customisation

All content is driven by simple arrays in `index.html` under the `<script type="text/babel">` section. To add new experiences, internships, projects or highlights, edit the corresponding arrays. You can also tweak the CSS variables at the top of the `<style>` block to adjust colours or spacing.

### License

This project is shared for personal portfolio use. Feel free to fork and adapt it for your own showcase.