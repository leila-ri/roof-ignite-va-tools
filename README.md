# Roof Ignite VA Tools

Live reference guides for virtual assistant operations at Roof Ignite. Quick access to scripts, workflows, and standard procedures.

## 📍 Live Links

- **Landing Page**: `https://<YOUR_USERNAME>.github.io/roof-ignite-va-tools/`
- **VA Flow Summary**: `https://<YOUR_USERNAME>.github.io/roof-ignite-va-tools/flow-summary.html`
- **VA Lead Playbook**: `https://<YOUR_USERNAME>.github.io/roof-ignite-va-tools/lead-playbook.html`

## 🚀 Quick Start

### Step 1: Create the Repository on GitHub
1. Go to [github.com/new](https://github.com/new)
2. Create a public repository named `roof-ignite-va-tools`
3. Initialize with README (optional, we have one)

### Step 2: Clone & Add Files Locally
```bash
git clone https://github.com/<YOUR_USERNAME>/roof-ignite-va-tools.git
cd roof-ignite-va-tools

# Copy your files (rename for clean URLs)
cp path/to/VA_Flow_Summary__standalone___1_.html flow-summary.html
cp path/to/VA_Lead_Playbook__standalone___1_.html lead-playbook.html

# Add the landing page
cp path/to/index.html index.html
```

### Step 3: Commit & Push
```bash
git add .
git commit -m "Initial commit: Add VA tools and landing page"
git push origin main
```

### Step 4: Enable GitHub Pages
1. Go to **Settings → Pages** in your GitHub repo
2. Set **Source** to `main` branch
3. Set folder to `/ (root)`
4. Click **Save**
5. Wait ~1-2 minutes for GitHub to build and deploy

Your site will be live at: `https://<YOUR_USERNAME>.github.io/roof-ignite-va-tools/`

## 📁 File Structure
```
roof-ignite-va-tools/
├── README.md                 # This file
├── index.html               # Landing page (home)
├── flow-summary.html        # VA Flow Summary tool
├── lead-playbook.html       # VA Lead Playbook tool
└── .gitignore              # (optional) Ignore unnecessary files
```

## 🔗 Cross-Linking

Both documents are linked from the landing page (`index.html`). When you open the site, you'll see cards for each tool.

**Optional**: To add back-links within each HTML file, you can:
1. Edit `flow-summary.html` and `lead-playbook.html`
2. Add a small nav bar at the top pointing back to `index.html`
3. Or create a simple top banner with a "← Back to Home" link

### Adding a Back Button (Quick Fix)
If you want a quick "back to home" link in your tools, add this to the `<body>` section of each HTML file:

```html
<div style="position: fixed; top: 10px; left: 10px; z-index: 10001; background: white; padding: 10px; border-radius: 6px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
  <a href="index.html" style="text-decoration: none; color: #e8472c; font-weight: 500;">← Back to Home</a>
</div>
```

## 🔄 Updating Files

Any time you update the HTML files:
```bash
# After making changes locally
git add .
git commit -m "Update: [description of changes]"
git push origin main
```

GitHub Pages auto-deploys within 30 seconds.

## 💡 Tips

- **Custom Domain** (optional): If you own a domain, update it in **Settings → Pages → Custom domain**
- **Fast URLs**: Keep filenames short (e.g., `flow.html` instead of long ones)
- **Mobile Friendly**: The landing page is fully responsive. Your bundled HTML files will render on mobile too.

## 📞 Support

Questions? Check GitHub's [Pages documentation](https://docs.github.com/en/pages).

---

**Updated**: May 2026
