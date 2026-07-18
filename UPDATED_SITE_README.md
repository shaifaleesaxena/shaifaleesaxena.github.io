# Updated website

This version adds a custom one-page homepage modeled on the Mahindra S. Rautela GitHub Pages repository while preserving Shaifalee Saxena's content and Academic Pages/Jekyll structure.

## Main content files

- `_pages/about.md`: homepage sections and text
- `_data/news.yml`: news timeline
- `_data/publications.yml`: homepage and publications-page entries
- `_pages/projects.md`: full research page
- `_pages/cv.md`: CV page

## Design files

- `_layouts/home.html`: custom homepage shell and navigation
- `_sass/_modern.scss`: modern responsive styling
- `assets/js/site.js`: mobile navigation and publication filters
- `_includes/head/custom.html`: Google Fonts

## Publish

Replace the files in the `shaifaleesaxena.github.io` GitHub repository with this folder's contents, commit, and push to the repository's publishing branch. GitHub Pages will build the Jekyll site automatically.
