# SATM Engineering Website

This repository now contains a lightweight [Jekyll](https://jekyllrb.com/) site
configured for the SATM Engineering brand. The goal is to keep things simple: a
few marketing pages, an initial blog post, and collections that can grow over
 time.

## Requirements

- Ruby 3.0 or later
- [Bundler](https://bundler.io/) (`gem install bundler`)

## Local development

```bash
bundle install
bundle exec jekyll serve
```

The development server will be available at `http://127.0.0.1:4000`. Saved
changes trigger an automatic rebuild and live refresh.

## Project structure

- `_config.yml` – global site settings, collection definitions, and theme
  selection.
- `_posts/` – dated Markdown files that power the blog.
- `_services/`, `_projects/`, `_team/` – collections for future expansion.
- `about.md`, `services.md`, `projects.md`, `contact.md` – core marketing pages.
- `CNAME` – custom domain mapping for `satm.engineering` when published with
  GitHub Pages or another static host.
