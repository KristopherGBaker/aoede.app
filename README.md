# aoede.app

The website for [Aoede](https://aoede.app/), a reader for Mac, iPhone and iPad that reads books aloud.

It is an [Inkwell](https://github.com/KristopherGBaker/inkwell) project with a hand-written theme in `themes/aoede/`, in
the app's Paper reading theme (Night in dark mode), with the colours from `AoedeDesignSystem/Theme.swift`.

- `inkwell build` writes the site to `public/`; `inkwell serve` previews it.
- Pushing to `main` deploys to GitHub Pages (`.github/workflows/pages.yml`).
- Until launch the home page is `layouts/holding.html`, a placeholder with its copy in `data/holding.yml`.
- Fraunces and Literata are the app's bundled faces, subset to Latin and converted to WOFF2 in
  `themes/aoede/assets/fonts/` with their OFL licences, so the site loads no third-party fonts.
- `content/pages/privacy.md` is the privacy policy at `/privacy/`. Keep it in step with what the app sends.
