# johnviljoen.github.io

My personal website — built with [Jekyll](https://jekyllrb.com) and served by
GitHub Pages at **https://johnviljoen.github.io**.

## Editing content

Most changes don't require touching HTML:

| What you want to change | Where |
| --- | --- |
| Name, tagline, social links, TODO URLs | `_config.yml` |
| Header/footer icon links | `_data/social.yml` |
| Projects (cards) | `_data/projects.yml` — set `featured: true` to show on the home page |
| Publications | `_data/publications.yml` — set `featured: true` to show on the home page |
| About text & hero copy | `index.html` (look for the `<em>…</em>` placeholders) |
| Blog posts | add a Markdown file to `_posts/` named `YYYY-MM-DD-title.md` |
| Colors / fonts | design tokens at the top of `assets/css/style.css` |

### Still to fill in
Search the repo for `TODO` — the LinkedIn handle and Google Scholar URL in
`_config.yml` / `_data/social.yml` are placeholders, and the hero + About copy
in `index.html` uses `<em>italic placeholder</em>` text.

## Running locally

```bash
bundle install       # first time only
bundle exec jekyll serve --livereload
# open http://localhost:4000
```

## Deploying

Push to `main`. GitHub Pages builds and deploys automatically — no action
needed. Check **Settings → Pages** on GitHub if the source branch isn't set to
`main` / root.
