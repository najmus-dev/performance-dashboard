# Majlis Jamiyaat AlBurhan - Performance Dashboard

Performance Dashboard for Majlis Jamiyaat AlBurhan Peshawar, displaying course statistics and analytics from March 2024 to July 2025.

## 🚀 Deployment to GitHub Pages

This dashboard is deployed on GitHub Pages and can be accessed at:
**https://[your-username].github.io/[repository-name]/**

### Quick Setup Instructions

1. **Create a GitHub Repository**
   - Go to [GitHub](https://github.com) and create a new repository
   - Name it something like `jamiat-dashboard` or `alburhan-performance`

2. **Initialize Git and Push (if Git is installed)**
   ```bash
   git init
   git add index.html README.md .gitignore
   git commit -m "Initial commit: Performance Dashboard"
   git branch -M main
   git remote add origin https://github.com/[your-username]/[repository-name].git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click on **Settings** tab
   - Scroll down to **Pages** section (in the left sidebar)
   - Under **Source**, select **Deploy from a branch**
   - Choose **main** branch and **/ (root)** folder
   - Click **Save**

4. **Access Your Site**
   - Your site will be available at: `https://[your-username].github.io/[repository-name]/`
   - It may take a few minutes for the site to be published initially

### Alternative: Using GitHub Desktop

If you don't have Git installed, you can use [GitHub Desktop](https://desktop.github.com/):

1. Install GitHub Desktop
2. Open GitHub Desktop
3. Click **File** → **Add Local Repository**
4. Select the `S:\Al Burhan` folder
5. Click **Publish repository** to create it on GitHub
6. Follow step 3 above to enable GitHub Pages

### Updating the Dashboard

Whenever you update `index.html` or `jamiat.md`:

1. Copy the content from `jamiat.md` to `index.html` (or update `index.html` directly)
2. Commit and push the changes:
   ```bash
   git add index.html
   git commit -m "Update dashboard data"
   git push
   ```
3. GitHub Pages will automatically update (may take a few minutes)

## 📊 Features

- Interactive charts using Chart.js
- Responsive design for mobile and desktop
- Performance metrics and KPIs
- Course timeline visualization
- Strategic insights and analytics

## 📝 Notes

- The main file is `index.html` - this is what GitHub Pages will serve
- `jamiat.md` contains the original source (it's actually HTML despite the .md extension)
- Charts load from CDN, so internet connection is required for full functionality

