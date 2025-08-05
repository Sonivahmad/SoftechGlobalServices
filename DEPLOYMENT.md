# 🚀 Portfolio Deployment Guide

## Free Hosting Options

### 1. GitHub Pages (Recommended)

#### Prerequisites:
- GitHub account
- Git installed on your computer

#### Steps:
1. **Create GitHub Repository:**
   - Go to [GitHub.com](https://github.com)
   - Click "New repository"
   - Name: `soniv-portfolio` or `my-portfolio`
   - Make it Public
   - Click "Create repository"

2. **Upload Files:**
   ```bash
   # Open terminal/command prompt in your portfolio folder
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click "Settings" tab
   - Scroll down to "Pages" section
   - Source: "Deploy from a branch"
   - Branch: "main"
   - Folder: "/ (root)"
   - Click "Save"

4. **Your site will be live at:** `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`

---

### 2. Netlify (Drag & Drop)

#### Steps:
1. Go to [netlify.com](https://netlify.com)
2. Sign up with GitHub/Google
3. Drag your entire portfolio folder to the Netlify dashboard
4. Your site is instantly live!
5. Customize URL in site settings

---

### 3. Vercel (Modern & Fast)

#### Steps:
1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub
3. Click "New Project"
4. Import your GitHub repository
5. Click "Deploy"

---

### 4. Surge.sh (Command Line)

#### Steps:
```bash
# Install Surge globally
npm install -g surge

# Navigate to your portfolio folder
cd your-portfolio-folder

# Deploy
surge

# Follow the prompts:
# - Enter your email
# - Create a password
# - Choose a domain (or use the suggested one)
```

---

## 📋 Pre-Deployment Checklist

### ✅ Files to Include:
- [x] `index.html`
- [x] `styles.css`
- [x] `script.js`
- [x] `README.md`
- [x] `package.json`

### ✅ Test Your Site:
- [x] Open `index.html` in browser
- [x] Check all links work
- [x] Test responsive design
- [x] Verify WhatsApp links work
- [x] Test contact form (if functional)

### ✅ SEO Optimization:
- [x] Title tag is set
- [x] Meta description added
- [x] All images have alt text
- [x] Proper heading structure

---

## 🔧 Custom Domain (Optional)

### GitHub Pages:
1. Buy domain from Namecheap/GoDaddy
2. In repository Settings → Pages
3. Add custom domain
4. Update DNS settings with your domain provider

### Netlify:
1. Go to Site Settings → Domain Management
2. Add custom domain
3. Update DNS settings

---

## 📱 Mobile Testing

After deployment, test on:
- [x] Desktop browsers (Chrome, Firefox, Safari, Edge)
- [x] Mobile browsers (Chrome, Safari)
- [x] Different screen sizes
- [x] WhatsApp integration

---

## 🎯 Quick Start Commands

```bash
# For GitHub Pages
git add .
git commit -m "Update portfolio"
git push

# For Surge
surge

# For Netlify CLI
npm install -g netlify-cli
netlify deploy
```

---

## 🆘 Troubleshooting

### Common Issues:
1. **Images not loading:** Check file paths are relative
2. **CSS not working:** Ensure `styles.css` is in same folder as `index.html`
3. **JavaScript errors:** Check browser console for errors
4. **WhatsApp links:** Test on mobile device

### Support:
- GitHub Pages: [GitHub Help](https://help.github.com/en/pages)
- Netlify: [Netlify Docs](https://docs.netlify.com)
- Vercel: [Vercel Docs](https://vercel.com/docs)

---

## 🎉 Congratulations!

Once deployed, your portfolio will be accessible worldwide! Share your URL on:
- LinkedIn
- Resume
- Business cards
- Social media profiles

**Your portfolio is now live and professional! 🌟** 