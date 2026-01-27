# DocuMenTor (site)

This folder contains the GitHub Pages site for the DocuMenTor project. I replaced the packaged theme with a small custom layout and stylesheet so the site can be styled similarly to the example you provided.

How to preview locally:

1. Install Ruby and Jekyll (macOS with Homebrew):

```bash
brew install ruby
gem install bundler jekyll
```

2. From the project root run:

```bash
cd docs
bundle exec jekyll serve --watch --baseurl="/DocuMenTor"
```

Files changed/added:
- `_layouts/default.html` — custom page layout
- `assets/css/style.css` — custom styles
- `index.md` — updated homepage using the custom layout
- `_config.yml` — disabled packaged theme (set to null)

Next steps / customization ideas:
- Tweak colors and typography in `assets/css/style.css`.
- Add an `about.md` page and a `docs/` section for documentation pages.
- Replace static links with a simple collection-based index if you want automatic nav.
