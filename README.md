# Akreon Website

Static Jekyll site for Akreon's company website hosted on github.

## Structure

- `index.html`: homepage
- `platform.html`: technical infrastructure page kept for URL continuity
- `library.html`: technical library hub
- `_posts/YYYY-MM-DD-title.md`: timestamped Library entries
- `_drafts/library-entry-template.md`: front matter template for internal or external Library entries
- `docs.html`: developer reference landing page
- `about.html`: company mission and philosophy
- `contact.html`: contact page
- `_sass/site.scss`: primary visual system

## Develop

```bash
bundle install
bundle exec jekyll serve
```

## Content patterns

- Keep homepage messaging centered on model-based decision systems for constrained, uncertain environments
- Keep visible top-level navigation limited to Home, Library, About, and Contact
- Keep public notes, videos, notebooks, external references, and papers in the timestamped Library stream
- Use `external_url` in post front matter when a Library entry should link to YouTube, Substack, arXiv, or another external artifact
