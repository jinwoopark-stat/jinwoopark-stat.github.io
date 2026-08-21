# jinwoopark-stat.github.io

Personal academic homepage of Jinwoo Park — https://jinwoopark-stat.github.io

Built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme.

## Where the content lives

| What | File |
| --- | --- |
| Bio on the front page | `_pages/about.md` |
| Publications | `_bibliography/papers.bib` |
| CV | `_data/cv.yml` (page) and `assets/pdf/Jinwoo_Park_CV.pdf` (download) |
| Teaching | `_pages/teaching.md` |
| News items | `_news/*.md` — one file per item, filename date is cosmetic, the `date:` field is what sorts |
| Social links | `_data/socials.yml` |
| Site title, URL, theme options | `_config.yml` |
| Profile photo | `assets/img/prof_pic.jpg` |

`_includes/cv/render.liquid` is a local override of the theme's CV template; the only
change from upstream is that Education renders before Experience. Re-apply it if the
theme is upgraded.

## Running it locally

Ruby 3+ is required (macOS system Ruby is too old). With Homebrew:

```bash
brew install ruby imagemagick   # once
bin/serve
```

Then open http://127.0.0.1:4000. `bin/serve` sets the Homebrew Ruby on PATH and runs
`jekyll serve --livereload`; Ctrl-C stops it.

## Deploying

Pushing to `main` runs `.github/workflows/deploy.yml`, which builds the site and pushes
the result to the `gh-pages` branch. GitHub Pages serves that branch. Nothing to do by hand.
