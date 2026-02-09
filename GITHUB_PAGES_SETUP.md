# GitHub Pages Setup Instructions

This repository is configured with GitHub Pages infrastructure. Follow these steps to enable the site:

## Current Status

✅ **Infrastructure Complete**
- Jekyll configuration (`docs/_config.yml`)
- Custom layout (`docs/_layouts/default.html`)
- Homepage content (`docs/index.md`)
- CSS styling (`docs/assets/css/style.css`)
- Video assets included
- README with site link

## Enabling GitHub Pages

To activate the GitHub Pages site at https://sara-abouelwafa.github.io/DocuMenTor/:

1. **Merge this PR** to your main branch
   
2. **Enable GitHub Pages** in repository settings:
   - Go to: https://github.com/sara-abouelwafa/DocuMenTor/settings/pages
   - Under "Source", select:
     - Branch: `main` (or `master`)
     - Folder: `/docs`
   - Click "Save"

3. **Wait for deployment**
   - GitHub Actions will automatically build and deploy the site
   - This typically takes 1-2 minutes
   - Check the "Actions" tab to monitor deployment status

4. **Verify the site**
   - Visit: https://sara-abouelwafa.github.io/DocuMenTor/
   - The site should display with:
     - Project description
     - DocuMenTor Environment details
     - Video demos
     - Authors and publications

## Site Structure

```
docs/
├── _config.yml          # Jekyll configuration
├── _layouts/
│   └── default.html     # Page template
├── assets/
│   ├── css/
│   │   └── style.css    # Custom styles
│   ├── plugin.mov       # Eclipse plugin demo
│   └── website.mov      # Website demo
├── index.md             # Homepage content
└── index.html           # Static fallback
```

## Configuration Details

- **Base URL**: `/DocuMenTor`
- **Site URL**: `https://sara-abouelwafa.github.io`
- **Theme**: Custom (no external theme)
- **Build Engine**: Jekyll (default GitHub Pages)

## Troubleshooting

If the site shows a 404 error:
1. Verify GitHub Pages is enabled with correct settings
2. Check that the branch and `/docs` folder are selected as source
3. Ensure the PR has been merged to the main branch
4. Wait for GitHub Actions to complete deployment

If you see styling issues:
1. Verify `assets/css/style.css` exists
2. Check browser console for loading errors
3. Ensure baseurl is correctly set in `_config.yml`

## Local Development

To test the site locally (optional):

```bash
cd docs
bundle install
bundle exec jekyll serve
# Visit http://localhost:4000/DocuMenTor/
```

## Contact

For issues with the GitHub Pages setup, contact:
- sara.abouelwafa
- pablo.gomeza@uam.es
