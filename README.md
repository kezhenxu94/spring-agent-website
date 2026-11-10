# Spring Agent website

The landing page, privacy policy and terms of use for the Spring Agent iPhone app, served by GitHub
Pages at <https://springagent.kezhenxu94.me> (`CNAME`). Plain HTML and one stylesheet; no build step.

The App Store listing links `/privacy` and `/terms`, and so does the app's paywall: keep those paths.

The landing page is in eight languages: English at the root, the others in `zh-Hans/`, `ja/`,
`ko/`, `de/`, `fr/`, `es/` and `pt-BR/`, linked by `hreflang` and the header's language menu; the
privacy policy and terms stay English. Screenshots are the app's own, light and dark, per language
(`assets/` for English, `assets/<lang>/` for the rest), taken by `scripts/website-screenshots.sh` in
the app repository. A change to the English page goes to every translation.
