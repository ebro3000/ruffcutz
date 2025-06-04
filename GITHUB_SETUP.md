# GitHub Pages Setup Instructions

Follow these steps to host your Ruff Cutz website on GitHub Pages:

## 1. Create GitHub Account (if needed)
- Go to https://github.com
- Sign up for a free account

## 2. Create New Repository
1. Click the "+" icon in top right corner
2. Select "New repository"
3. Name it: `ruffcutz` (or any name you prefer)
4. Make it PUBLIC (required for free GitHub Pages)
5. Don't initialize with README
6. Click "Create repository"

## 3. Push Your Code
Copy and run these commands in your terminal:

```bash
cd "/Users/evanstoudt/Documents/File Cabinet/Coding/RuffCutzDotOrg"
git add .
git commit -m "Initial commit - Ruff Cutz website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/ruffcutz.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.

## 4. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll to "Pages" section (left sidebar)
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

## 5. Your Site Will Be Live At:
`https://YOUR_USERNAME.github.io/ruffcutz/`

(Takes 5-10 minutes to go live initially)

## 6. Connect Your Squarespace Domain
1. In GitHub repo settings > Pages, look for "Custom domain"
2. Enter your domain (e.g., ruffcutz.org)
3. In Squarespace:
   - Go to Settings > Domains > DNS Settings
   - Add a CNAME record pointing to `YOUR_USERNAME.github.io`
   - Or add A records pointing to GitHub's IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153

## Need Help?
- GitHub Pages docs: https://pages.github.com
- Squarespace DNS help: https://support.squarespace.com/hc/en-us/articles/360002101888