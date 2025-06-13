# Retreat

This repository contains the static website for the Anxiety Reduction Retreat held in Templia, Mexico.

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

## Deployment

Commit the generated files and push to a branch configured for GitHub Pages (e.g. `main` or `gh-pages`). GitHub will serve the contents at your chosen domain.

## License and Credits

This project is distributed under the [Creative Commons Attribution 3.0](LICENSE.txt) license.
