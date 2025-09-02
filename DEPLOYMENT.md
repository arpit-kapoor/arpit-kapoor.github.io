# GitHub Pages Deployment Guide

## 🚀 Quick Setup

Your website is now ready for GitHub Pages deployment! Follow these steps:

### 1. Push to GitHub

```bash
# Push the data-science-profile branch
git push origin data-science-profile

# Or merge to main/master branch first
git checkout master
git merge data-science-profile
git push origin master
```

### 2. Enable GitHub Pages

1. Go to your GitHub repository: `https://github.com/arpit-kapoor/arpit-kapoor.github.io`
2. Click on **Settings** tab
3. Scroll down to **Pages** section
4. Under **Source**, select:
   - **Deploy from a branch**
   - Choose `data-science-profile` branch (or `master` if you merged)
   - Select `/ (root)` folder
5. Click **Save**

### 3. Access Your Website

Your website will be available at:
**https://arpit-kapoor.github.io**

*Note: It may take 5-10 minutes for the site to be live after enabling Pages.*

## 📁 Repository Structure

```
/
├── index.html                    # Main website file
├── index-ds.html                # Redirect helper
├── .nojekyll                    # Prevents Jekyll processing
├── README.md                    # Project documentation
├── assets/
│   ├── Academic_CV_Env_2025.pdf # Your CV
│   └── ...
├── images/                      # All images and assets
├── archive-legacy/              # Legacy Jekyll site backup
└── node_modules/               # Dependencies (ignored by git)
```

## ✅ GitHub Pages Optimization

The website is optimized for GitHub Pages with:

- ✅ `.nojekyll` file to disable Jekyll processing
- ✅ `index.html` as the main entry point
- ✅ All assets using relative paths
- ✅ No server-side dependencies
- ✅ Responsive design for all devices
- ✅ Fast loading with CDN resources

## 🔧 Custom Domain (Optional)

To use a custom domain:

1. Add a `CNAME` file with your domain:
   ```
   yourdomain.com
   ```
2. Configure DNS settings with your domain provider
3. Update GitHub Pages settings to use the custom domain

## 📊 Features Included

- 🌙 Dark/Light theme toggle
- 📱 Fully responsive design
- ⚡ Fast loading with animations
- 🎨 Professional color scheme
- 📄 CV download functionality
- 🔗 Social media integration
- 🏆 Awards and achievements showcase
- 📚 Publications with PDF links
- 💼 Professional experience timeline

## 🐛 Troubleshooting

**If the site doesn't load:**
1. Check GitHub Pages is enabled in repository settings
2. Ensure `index.html` is in the root directory
3. Wait 10-15 minutes for DNS propagation
4. Check browser console for errors

**For updates:**
1. Make changes to your files
2. Commit and push to GitHub
3. Pages will automatically rebuild and deploy

---

**Ready to go live!** 🚀

Your professional data science portfolio is now ready for the world to see.
