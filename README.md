# Changyue Jiang's Homepage

This repository hosts the personal academic homepage for Changyue Jiang:

https://jiangchangyue.github.io/

The site is built with Jekyll on GitHub Pages and is adapted from the AcademicPages theme.

## Editing Content

- Homepage: `_pages/about.md`
- Publications: `_publications/`
- Publication cards: `_includes/publication-card.html`
- Publication ordering: `_includes/publication-list.html`
- Open-source projects: `_data/projects.yml`
- Project cards: `_includes/project-card.html`
- Site-wide settings and SEO metadata: `_config.yml`
- Avatar and project images: `images/my_pic/`

## Previewing Locally

If Ruby and Bundler are available:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open:

```text
http://localhost:4000/
```

## Deployment

GitHub Pages deploys the site from the `master` branch after pushing:

```bash
git add .
git commit -m "update homepage"
git push origin master
```
