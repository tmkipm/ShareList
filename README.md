# MusicApp Legal Documents - GitHub Pages

This folder contains the Privacy Policy and Terms of Service for MusicApp, ready to be hosted on GitHub Pages.

## Files Included

- `index.html` - Landing page with links to both documents
- `privacy.html` - Privacy Policy
- `terms.html` - Terms of Service
- `style.css` - Shared styling for all pages
- `README.md` - This file

## How to Set Up GitHub Pages

### Option 1: Using Your Existing Repository (https://github.com/tmkipm/ShareList.git)

1. **Copy these files to your repository**:
   ```bash
   cd /path/to/ShareList
   cp -r /Users/tmk/Documents/Development2026/MusicApp/docs/* .
   ```

2. **Commit and push**:
   ```bash
   git add .
   git commit -m "Add MusicApp legal documents"
   git push origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Select **main** branch and **/ (root)** folder
   - Click **Save**

4. **Access your pages** (after 1-2 minutes):
   - Privacy Policy: `https://tmkipm.github.io/ShareList/privacy.html`
   - Terms of Service: `https://tmkipm.github.io/ShareList/terms.html`
   - Landing Page: `https://tmkipm.github.io/ShareList/`

### Option 2: Create a New Repository

1. **Create a new repository** on GitHub (e.g., `musicapp-legal`)

2. **Initialize and push these files**:
   ```bash
   cd /Users/tmk/Documents/Development2026/MusicApp/docs
   git init
   git add .
   git commit -m "Initial commit: MusicApp legal documents"
   git branch -M main
   git remote add origin https://github.com/tmkipm/musicapp-legal.git
   git push -u origin main
   ```

3. **Enable GitHub Pages** (same as above)

4. **Access your pages**:
   - Privacy Policy: `https://tmkipm.github.io/musicapp-legal/privacy.html`
   - Terms of Service: `https://tmkipm.github.io/musicapp-legal/terms.html`

## URLs for App Store Connect

Once GitHub Pages is live, use these URLs in App Store Connect:

- **Privacy Policy URL**: `https://tmkipm.github.io/[repo-name]/privacy.html`
- **Terms of Service URL**: `https://tmkipm.github.io/[repo-name]/terms.html`

Replace `[repo-name]` with your actual repository name.

## Customization

### Update Colors/Styling

Edit `style.css` to customize the appearance. Current gradient uses:
- Primary: `#667eea` (purple-blue)
- Secondary: `#764ba2` (purple)

### Update Content

If you need to update the legal documents:
1. Edit the HTML files directly, or
2. Update the markdown files and regenerate the HTML

---

**Contact**: ramp.39mussels@cloud.com
**Developer**: Tyler Knibbs
