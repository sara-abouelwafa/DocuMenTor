# Quick Start: Enable GitHub Pages

This repository is ready for GitHub Pages deployment with automated GitHub Actions workflow.

## ⚡ Quick Enable (2 Steps)

### Step 1: Enable GitHub Pages
1. Go to repository **Settings** → **Pages**
   - Direct link: https://github.com/sara-abouelwafa/DocuMenTor/settings/pages
2. Under **"Build and deployment"**:
   - Set **Source** to: `GitHub Actions`
3. Click **Save**

### Step 2: Deploy
- Merge this PR to `main` branch
- The site will automatically deploy via GitHub Actions
- Visit: https://sara-abouelwafa.github.io/DocuMenTor/

## ✨ What Happens Next

1. **Automatic Build**: GitHub Actions workflow runs automatically
2. **Jekyll Build**: Compiles the site from `docs/` folder
3. **Deployment**: Publishes to GitHub Pages
4. **Live Site**: Available at https://sara-abouelwafa.github.io/DocuMenTor/

## 📋 Manual Trigger (Optional)

If you want to manually deploy:
1. Go to **Actions** tab
2. Select **"Deploy Jekyll site to Pages"**
3. Click **"Run workflow"**
4. Select branch and click **"Run workflow"**

## 🔍 Monitor Deployment

- **Actions Tab**: See build progress and logs
- **Deployments**: Check under repository "Environments"
- **Status**: Green checkmark = successful deployment

## 📚 More Information

See [GITHUB_PAGES_SETUP.md](./GITHUB_PAGES_SETUP.md) for detailed documentation.

---

**Note**: You must have admin access to the repository to enable GitHub Pages.
