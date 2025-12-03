# Mahak Malik - Professional Portfolio

A modern, terminal-inspired portfolio website showcasing DevOps engineering skills and experience.

## 🚀 Quick Deploy to GitHub Pages (Free Hosting)

### Step 1: Create GitHub Repository

1. Go to [github.com](https://github.com) and sign in
2. Click the **+** icon → **New repository**
3. Name it: `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
   - Example: `mahakmalik.github.io`
4. Make it **Public**
5. Click **Create repository**

### Step 2: Upload Files

**Option A: Using GitHub Web Interface (Easiest)**
1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop these files:
   - `index.html`
   - `styles.css`
   - `script.js`
3. Click **Commit changes**

**Option B: Using Git Command Line**
```bash
cd /Users/MMalik/Projects/mahak-portfolio

git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository **Settings**
2. Click **Pages** in the left sidebar
3. Under "Source", select **main** branch
4. Click **Save**

### Step 4: Access Your Site

Your site will be live at: `https://yourusername.github.io`

(It may take 1-2 minutes to deploy)

---

## 📁 Project Structure

```
mahak-portfolio/
├── index.html      # Main HTML structure
├── styles.css      # All styling (dark theme, animations)
├── script.js       # Interactivity & animations
└── README.md       # This file
```

## ✨ Features

- **Terminal-inspired design** - Reflects DevOps aesthetic
- **Fully responsive** - Works on all devices
- **Animated skill bars** - Visual skill representation
- **Smooth scroll navigation** - Enhanced UX
- **Animated counters** - Experience stats
- **Dark theme** - Easy on the eyes
- **Fast loading** - No frameworks, pure HTML/CSS/JS

## 🎨 Customization

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --accent-primary: #00d4aa;      /* Main accent color */
    --accent-secondary: #00b894;    /* Secondary accent */
    --bg-primary: #0a0e14;          /* Main background */
}
```

### Update Content
All content is in `index.html` - edit sections as needed.

### Add a Profile Photo
Replace the YAML code block in the About section with an image:
```html
<img src="your-photo.jpg" alt="Mahak Malik" class="profile-photo">
```

## 🔧 Alternative Free Hosting Options

### Netlify
1. Go to [netlify.com](https://netlify.com)
2. Drag & drop the project folder
3. Get URL like `your-site.netlify.app`

### Vercel
1. Go to [vercel.com](https://vercel.com)
2. Import from GitHub or upload
3. Get URL like `your-site.vercel.app`

### Cloudflare Pages
1. Go to [pages.cloudflare.com](https://pages.cloudflare.com)
2. Connect GitHub repo
3. Get URL like `your-site.pages.dev`

---

## 📝 License

MIT License - Feel free to use and modify!

---

Built with ❤️ for Mahak Malik

