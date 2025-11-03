# Quick Setup Guide for GitHub

## 📋 Files You Have

- `index.html` - Your portfolio website
- `README.md` - Documentation for your repository
- `.gitignore` - Files to ignore in git

## 🚀 Two Ways to Upload

### Method 1: GitHub Website (Easiest)

**Step 1: Create Repository**
1. Go to https://github.com/new
2. Repository name: `portfolio` (or `yourusername.github.io`)
3. Make it **Public**
4. ❌ DON'T initialize with README
5. Click "Create repository"

**Step 2: Upload Files**
1. Click "uploading an existing file"
2. Drag and drop all your files:
   - index.html
   - README.md
   - .gitignore
3. Write commit message: "Initial commit"
4. Click "Commit changes"

**Step 3: Enable GitHub Pages**
1. Go to **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** → **/ (root)** → **Save**
4. Wait 2 minutes
5. Visit: `https://yourusername.github.io/portfolio`

---

### Method 2: Git Command Line

```bash
# 1. Navigate to your folder with the files
cd ~/Downloads/portfolio-files

# 2. Initialize git
git init

# 3. Add all files
git add .

# 4. Commit
git commit -m "Initial commit: Portfolio website"

# 5. Connect to GitHub (replace with your username and repo name)
git remote add origin https://github.com/yourusername/portfolio.git

# 6. Push to GitHub
git branch -M main
git push -u origin main
```

Then enable GitHub Pages as in Method 1, Step 3.

---

## ✅ Checklist Before Publishing

- [ ] Update your name in index.html
- [ ] Add your email address
- [ ] Update social media links
- [ ] Replace placeholder image with your photo
- [ ] Customize the About section
- [ ] Add your real projects
- [ ] Update skills list
- [ ] Test the website locally by opening index.html

---

## 🎯 Pro Tips

1. **Custom Domain**: You can use your own domain name
   - Go to Settings → Pages → Custom domain

2. **Repository Name Trick**:
   - If you name it `yourusername.github.io`, your site will be at:
     `https://yourusername.github.io` (no /portfolio)
   - Otherwise it will be at: `https://yourusername.github.io/portfolio`

3. **Updates**: After making changes locally:
   ```bash
   git add .
   git commit -m "Update portfolio"
   git push
   ```

4. **View Live Site**: After enabling Pages, look for:
   "Your site is live at https://..."

---

## ❓ Common Issues

**Issue**: Site shows 404
- **Solution**: Wait 2-3 minutes after enabling Pages
- Check Settings → Pages to see if it's deployed

**Issue**: Changes not showing
- **Solution**: Hard refresh browser (Ctrl+Shift+R or Cmd+Shift+R)
- Clear browser cache

**Issue**: Images not loading
- **Solution**: Use full URLs for images (https://...)
- Or commit images to your repo and use relative paths

---

## 📚 Learn More

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Git Basics](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
- [Markdown Guide](https://www.markdownguide.org/)

---

Need help? Open an issue on GitHub or reach out! 🚀
