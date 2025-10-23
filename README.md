# SATM Engineering Blog

This repository contains the source for the SATM Engineering blog built with [Jekyll](https://jekyllrb.com/).

## Getting started

1. Install Ruby (version 3.0 or later is recommended) and [Bundler](https://bundler.io/).
2. Install dependencies:

   ```bash
   bundle install
   ```

3. Run the development server:

   ```bash
   bundle exec jekyll serve
   ```

   The site will be available at <http://127.0.0.1:4000/>.

## Project structure

- `_config.yml` – Site configuration and metadata.
- `_layouts/` – HTML templates for pages and posts.
- `_posts/` – Blog posts written in Markdown with filenames like `YYYY-MM-DD-title.md`.
- `assets/css/` – Site styling.
- `index.md` – Homepage with the latest posts.
- `about.md` – About page for SATM Engineering.

## Deployment

Build the production site with:

```bash
bundle exec jekyll build
```

The generated site will be output to the `_site/` directory.
