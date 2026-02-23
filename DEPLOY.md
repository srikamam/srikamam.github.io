# GitHub Pages Deployment Guide

## Step-by-Step Instructions

### Step 1: Create a GitHub Account (if you don't have one)
- Go to [github.com](https://github.com)
- Sign up with your email
- Verify your email address

### Step 2: Create Your Repository

**For a `username.github.io` site (recommended):**
1. Go to [github.com/new](https://github.com/new)
2. Repository name: **`username.github.io`** (replace `username` with your GitHub username)
   - Example: `john-doe.github.io`
3. Description: "My Personal Portfolio"
4. Make it **Public**
5. Don't initialize with README (you already have one)
6. Click **Create repository**

### Step 3: Upload Your Files

#### Using Git (Recommended):
```bash
# Navigate to your project folder
cd path/to/personal_website

# Initialize git repository
git init

# Add GitHub as remote
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit - Portfolio website"

# Push to GitHub
git push -u origin main
```

#### Using GitHub Desktop:
1. Download [GitHub Desktop](https://desktop.github.com)
2. Sign in with your GitHub account
3. Click "+ Create New Repository"
4. Choose your personal_website folder
5. Publish to GitHub
6. Make it Public

#### Using GitHub Web Interface:
1. Go to your repository
2. Click "Add file" → "Upload files"
3. Drag and drop your files or select them
4. Click "Commit changes"

### Step 4: Enable GitHub Pages

Usually enabled automatically for `username.github.io` repositories.

**If deploying to a different repository:**
1. Go to your repository
2. Click **Settings**
3. Scroll to **Pages** section
4. Under "Source", select `main` branch
5. Click Save

### Step 5: Access Your Website

Your portfolio will be live at:
- **`https://username.github.io`** (if using `username.github.io` repo)
- **`https://username.github.io/repository-name`** (if using a different repo name)

⏱️ **Note:** It may take 1-2 minutes for your site to appear. If it doesn't show up:
1. Wait a few more minutes
2. Clear your browser cache
3. Check the GitHub Actions tab in your repository for build status

## Updating Your Website

After making changes:

```bash
git add .
git commit -m "Update portfolio content"
git push origin main
```

Your changes will be live within 1-2 minutes!

## Troubleshooting

### Site not showing up?
- Check that your repository is **public**
- Wait 2-5 minutes for GitHub to build
- Check repository Settings → Pages to verify deployment

### Links not working?
- Make sure all file names match exactly (case-sensitive)
- Use relative paths: `./styles.css` not `/styles.css`

### Want to use a custom domain?
- In Settings → Pages, add your custom domain
- Update your domain DNS settings to point to GitHub Pages
- See [GitHub's custom domain guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

## Need Help?

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Help Community](https://github.community)
- Check your repository's Actions tab for deployment logs

---

Happy deploying! 🚀
