# Quick Start Guide

Get your portfolio up and running in minutes!

## 🚀 Quick Commands

### Test Locally (Windows)
```powershell
cd "c:\Users\SAMARA SIMHAREDDY\OneDrive\Desktop\New folder (14)\portfolio"
python -m http.server 8000
```
Then open: http://localhost:8000

### Deploy to GitHub

```bash
# First time setup
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git branch -M main
git push -u origin main

# Update after changes
git add .
git commit -m "Update: your description here"
git push origin main
```

## 📝 Customization Checklist

Quick edits to personalize your portfolio:

### 1. **Update Your Info** (index.html)
- [ ] Change name from "Samara" to your name
- [ ] Update title/subtitle
- [ ] Update about section
- [ ] Change contact info (email, phone, location)
- [ ] Update social links

### 2. **Add Your Projects** (index.html)
- [ ] Replace project titles
- [ ] Update descriptions
- [ ] Add your tech stack
- [ ] Update demo and GitHub links

### 3. **Update Skills** (index.html)
- [ ] Add/remove frontend skills
- [ ] Add/remove backend skills
- [ ] Add/remove tools

### 4. **Customize Colors** (css/style.css)
```css
--primary-color: #6366f1;        /* Main purple */
--secondary-color: #ec4899;      /* Secondary pink */
```

### 5. **Update README** (README.md)
- [ ] Change project name
- [ ] Update author info
- [ ] Add your GitHub username
- [ ] Add your deploy link

## 🧪 Testing in 30 Seconds

1. Open http://localhost:8000 in your browser
2. Press F12 to open Developer Tools
3. Check Console tab - should be empty (no errors)
4. Open Mobile view (Ctrl+Shift+M)
5. Test hamburger menu on mobile
6. Try the contact form

**If all works → Ready to deploy!**

## 📱 Responsive Check

With DevTools open (F12):
- [ ] 320px (Mobile) - Looks good
- [ ] 768px (Tablet) - Looks good
- [ ] 1440px (Desktop) - Looks good

## 🌐 Deploy in 2 Steps

1. **Create GitHub Repo**
   - Go to github.com/new
   - Name it "portfolio"
   - Click Create

2. **Push Your Code**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to Settings > Pages
   - Select main branch
   - Save
   
   **Wait 1-2 minutes → Your site is live!**

## 📍 Your Portfolio URL
```
https://YOUR_USERNAME.github.io/portfolio
```

## 🔄 Keep It Updated

Every time you make changes:
```bash
git add .
git commit -m "Describe what you changed"
git push origin main
```

## 📞 Need Help?

- **Local server not working?** Try: `python -m SimpleHTTPServer 8000`
- **Git not found?** Install from: https://git-scm.com
- **Push not working?** Check your username in the URL
- **Site not updating?** Clear browser cache (Ctrl+Shift+Del)

## ✨ Pro Tips

- Add your portfolio link to your LinkedIn
- Share on Twitter/GitHub with #portfolio #dev
- Update projects as you complete new work
- Get feedback from the dev community
- Monitor your page speed with Lighthouse
- Use meaningful commit messages

## 📋 File Structure Reminder

```
portfolio/
├── index.html          ← Main file - edit personal info here
├── css/style.css       ← Styling - change colors here
├── js/script.js        ← Functionality - mostly done!
├── README.md           ← Update with your info
├── DEPLOYMENT.md       ← Deployment instructions
└── TESTING.md          ← Testing checklist
```

---

**You're all set! Time to customize and deploy! 🎉**
