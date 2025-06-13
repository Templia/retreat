# Retreat

This repository contains the static website for **A Journey Through Time: Inner Anxiety Healing Aligned with the Mayan Calendar** held in Templia, Tulum, Mexico.

See [index.md](index.md) for full retreat details.

## Serving Locally

Open `index.html` directly in a browser or start a simple web server from the repository root:

```bash
python3 -m http.server
```

Then visit `http://localhost:8000`.

### Editing Sass

Styles are authored in `assets/sass`. Rebuild `assets/css/main.css` after making changes with the [Sass](https://sass-lang.com/) CLI:

```bash
sass assets/sass/main.scss assets/css/main.css
```
Install the Sass CLI with `npm install -g sass` if needed.

## Deployment

Commit the generated files and push to a branch configured for GitHub Pages (e.g. `main` or `gh-pages`). GitHub will serve the contents at your chosen domain. You can also deploy the site to any static host such as Netlify or Vercel.

## License and Credits

This project is distributed under the [Creative Commons Attribution 3.0](LICENSE.txt) license.
