# Deployment Guide - GitHub Pages

This guide will help you deploy your portfolio to GitHub Pages in just a few steps.

## Prerequisites
- A GitHub account (free at https://github.com)
- Git installed on your computer
- Your portfolio project with Git initialized

## Step-by-Step Deployment

### 1. Create a GitHub Repository

1. Go to [GitHub](https://github.com) and log in to your account
2. Click the **+** icon in the top right corner
3. Select **New repository**
4. Fill in the repository details:
   - **Repository name:** `portfolio` (or any name you prefer)
   - **Description:** "My professional portfolio website"
   - **Public** - Make sure this is selected
   - Check **Add a README file** (optional, we already have one)
5. Click **Create repository**

### 2. Connect Local Repository to GitHub

In your terminal/PowerShell, run these commands:

```bash
cd "c:\Users\SAMARA SIMHAREDDY\OneDrive\Desktop\New folder (14)\portfolio"

# Add GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git

# Rename branch to main (if needed)
git branch -M main

# Push your code to GitHub
git push -u origin main
```

**Replace `YOUR_USERNAME` with your actual GitHub username**

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (gear icon)
3. Scroll down to **Pages** section on the left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Select **main** branch as the source
6. Click **Save**

### 4. Access Your Live Portfolio

Your portfolio will be available at:
```
https://YOUR_USERNAME.github.io/portfolio
```

**Wait 1-2 minutes for GitHub to deploy your site.**

## Updating Your Portfolio

To make changes and deploy them:

```bash
# Make your changes to files

# Stage changes
git add .

# Commit with a meaningful message
git commit -m "Update skills and add new project"

# Push to GitHub
git push origin main
```

GitHub Pages will automatically update your site within 1-2 minutes.

## Common Deployment Issues

### Issue: Changes not showing up
- **Solution:** 
  - Wait 1-2 minutes for deployment
  - Clear browser cache (Ctrl+Shift+Delete)
  - Check GitHub Actions tab for build errors

### Issue: Can't push to GitHub
- **Solution:**
  ```bash
  # Verify remote is set correctly
  git remote -v
  
  # If not set, add it:
  git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
  ```

### Issue: 404 error on portfolio
- **Solution:**
  - Verify GitHub Pages is enabled in Settings > Pages
  - Check that main branch is selected as source
  - Ensure index.html is in the root directory

## Using Custom Domain (Optional)

1. Buy a domain from a registrar (GoDaddy, Namecheap, etc.)
2. Go to repository Settings > Pages
3. Under **Custom domain**, enter your domain name
4. Configure DNS records with your registrar to point to GitHub Pages

See [GitHub Documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site) for detailed instructions.

## Committing Best Practices

Write clear, descriptive commit messages:

```bash
# Feature additions
git commit -m "Add dark mode toggle to navigation"

# Bug fixes
git commit -m "Fix mobile menu not closing on link click"

# Content updates
git commit -m "Update project descriptions and tech stack"

# Style improvements
git commit -m "Improve responsive design for tablet devices"

# Performance
git commit -m "Optimize images and reduce bundle size"
```

## Monitoring Your Site

1. **Check Status**
   - Go to your repository
   - Click **Deployments** tab
   - View deployment history

2. **View Logs**
   - Click on a deployment
   - Check for any errors in the logs

3. **Test Performance**
   - Use Google Lighthouse (built into Chrome DevTools)
   - PageSpeed Insights: https://pagespeed.web.dev
   - GTmetrix: https://gtmetrix.com

## Security & Best Practices

- ✅ Never commit sensitive information (API keys, passwords)
- ✅ Use .gitignore to exclude unnecessary files
- ✅ Keep your README updated
- ✅ Make meaningful commits
- ✅ Review changes before pushing
- ✅ Use consistent naming conventions

## Next Steps

After deployment:

1. **Share Your Portfolio**
   - LinkedIn profile
   - Resume/CV
   - Job applications
   - GitHub profile

2. **Continuous Improvement**
   - Add new projects regularly
   - Update skills section
   - Improve design based on feedback
   - Monitor analytics

3. **Backup & Maintenance**
   - Keep local repository updated
   - Back up important files
   - Review and update content periodically

## Useful Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Git Tutorial](https://git-scm.com/doc)
- [GitHub Desktop App](https://desktop.github.com/) - Visual Git client

## Support

If you encounter issues:
1. Check the error message carefully
2. Search GitHub documentation
3. Check your GitHub Actions logs
4. Try clearing cache and redeploying

---

**Your portfolio is now ready to be deployed!** 🚀
