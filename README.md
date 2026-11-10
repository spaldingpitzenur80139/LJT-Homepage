# LJT-Homepage

Personal homepage of **Junteng Liu**, a first-year PhD candidate at the HKUST NLP Group, supervised by Professor Junxian He. His research focuses on natural language processing and machine learning.

The site is forked from the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template, which is itself a fork of the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) Jekyll theme.

## Contents

- `_pages/about.md` — the About page (site homepage) with personal details, research interests, education, research experience, publications, honors and awards, and contact information.
- `_pages/publications.html` and `_publications/` — the Publications page, with one Markdown file per publication.
- `_config.yml` — site-wide settings, including the author sidebar profile (email, GitHub, Google Scholar, X).
- `_data/navigation.yml` — header navigation (About, Publications).

## Deployment

The site is built with Jekyll and deployed to GitHub Pages by the workflow in `.github/workflows/jekyll.yml`, which runs on every push to `master`. The build job validates the site on every push.

**One-time setup:** GitHub Pages must be enabled for this repository by the owner: go to **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**. After that, every push to `master` builds and deploys the site automatically, available at:

https://spaldingpitzenur80139.github.io/LJT-Homepage/

## Local preview

```bash
bundle install
bundle exec jekyll serve
```
