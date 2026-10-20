# projectN

An earlier version of a personal portfolio website (page title "Portfolio | Naresh Adhikari"), written in plain HTML, CSS and JavaScript.

> **Status: not maintained, kept for history.** The later iteration of the same codebase, which became a business website, lives in [WebsiteN](https://github.com/iamnarace/WebsiteN).

## What it contains

- `index.html` (home), `experience/` and `projects/` pages (the projects page reads `projects/projects.json`), and `404.html`.
- Styles in `assets/css/`, scripts in `assets/js/`, images in `assets/images/`, and `skills.json`.
- Built with HTML5, CSS3, JavaScript and jQuery.

## Run it

It is a static site with no build step:

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Deployment

`.github/workflows/static.yml` deploys the repository root to GitHub Pages on every push to `main`. Any change merged to `main` therefore redeploys the site.

## Known limitations

- No tests, no CI checks other than the Pages deployment, no dependency manifest.
- The pages are static and contain contact details exactly as published; review them before reusing the site.
- About 40 MB, mostly images.

## Licence

No licence has been selected, so default copyright applies.
