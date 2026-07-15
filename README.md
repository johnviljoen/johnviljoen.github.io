# johnviljoen.github.io

My personal website — a minimal single dark page built with
[Jekyll](https://jekyllrb.com) and served by GitHub Pages at
**https://johnviljoen.github.io**.

Sections: **about**, **research**, **software**, **blog**.

## Editing content

| What to change | Where |
| --- | --- |
| Name, tagline, social URLs | `_config.yml` |
| Footer links | `_data/social.yml` |
| Software list | `_data/software.yml` |
| Research list | `_data/research.yml` |
| About text | `index.html` (the `<span class="dim">…</span>` placeholder) |
| Blog posts | add a Markdown file to `_posts/` named `YYYY-MM-DD-title.md` |
| Colors / spacing | the `:root` variables at the top of `assets/css/style.css` |

Search the repo for `TODO` — the LinkedIn handle and Google Scholar URL in
`_config.yml` / `_data/social.yml` are placeholders.

## Deploying

Push to `main`; GitHub Pages builds and deploys automatically. (Local preview
needs a Ruby toolchain — easiest is to just push and let GitHub build it.)
