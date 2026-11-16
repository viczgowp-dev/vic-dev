# Viczen C. — Portfolio

A responsive, single-page portfolio for Viczen C., a web and software developer. Built with plain HTML and CSS; no build step required.

## Preview

Run `python3 -m http.server 8080` from this directory and open http://localhost:8080.

## Publish

Push these files to the repository's `main` branch. In GitHub, select **Settings → Pages → Build and deployment → Source → GitHub Actions**. The included workflow deploys the site when changes reach `main`, or when run manually from the Actions tab.

The expected Pages address is https://viczgowp-dev.github.io/vic-dev/ when Pages is enabled and deployment succeeds.

## Edit

- Content and links: `index.html`
- Layout, colors, and responsive styles: `assets/css/styles.css`
- Browser icon: `favicon.svg`

Featured project images are real screenshots. CASA was captured from dccasaks.org; Mr. Exchange and Prop MD Finder use screenshots from the supplied project portfolio. Each image links to its project website. Contact options include email, phone, and LinkedIn. Google Fonts is optional: the page falls back to system fonts when unavailable.

## Project structure

```text
vic-dev/
├── index.html
├── favicon.svg
├── assets/
│   ├── css/styles.css
│   └── images/
│       ├── arts-of-life-screenshot.webp
│       ├── holman-screenshot.webp
│       ├── serenity-parlor-screenshot.webp
│       ├── casa-screenshot.jpg
│       ├── mr-exchange-screenshot.webp
│       └── prop-md-screenshot.webp
├── .github/workflows/deploy.yml
├── .nojekyll
└── README.md
```

Keep styles in `assets/css` and project screenshots in `assets/images`. No JavaScript bundle or dependency installation is needed for this static site.
