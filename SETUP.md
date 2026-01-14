# GitHub Pages Portfolio Website

## Overview
Professional portfolio website built with Jekyll, featuring modern dark theme design with purple/cyan gradients, responsive layouts, and comprehensive sections.

## Structure
```
mhdev01/
├── _config.yml           # Jekyll configuration
├── _layouts/             # Page templates
│   └── default.html
├── _includes/            # Reusable components
│   ├── head.html
│   ├── header.html
│   └── footer.html
├── assets/
│   ├── css/
│   │   └── main.css      # Custom styles
│   ├── js/
│   │   └── main.js       # JavaScript functionality
│   └── images/           # All images
├── index.md              # Home page
├── about.md              # About page
├── projects.md           # Projects showcase
├── architecture.md       # Architecture philosophy
├── consulting.md         # Consulting services
└── resume.pdf            # PDF resume (add yours)
```

## Features
- ✨ **Modern Design**: Dark theme with vibrant purple/cyan gradients
- 📱 **Fully Responsive**: Mobile, tablet, and desktop layouts
- 🎨 **Glassmorphism Effects**: Modern UI with backdrop blur
- 🚀 **Smooth Animations**: Fade-in effects and micro-interactions
- ♿ **Accessible**: Semantic HTML and ARIA labels
- 🔍 **SEO Optimized**: Meta tags and structured data

## Setup & Deployment

### Option 1: GitHub Pages (Recommended)

**Before you start:** Create the repository on GitHub first:
1. Go to https://github.com/new
2. Repository name: **`mhdev01.github.io`** (exactly this)
3. Make it **Public**
4. **Don't** add README, .gitignore, or license
5. Click **Create repository**

**Deploy your site:**
```bash
cd c:\mhdev01
git init
git config user.name "mhdev01"
git config user.email "ebosmani@gmail.com"
git add .
git commit -m "Initial commit: Professional portfolio website"
git branch -M main
git remote add origin https://github.com/mhdev01/mhdev01.github.io.git
git push -u origin main
```

> **Note:** Lines 3-4 set the Git account to `mhdev01` for this project only, keeping your global Git config unchanged.

2. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Source: Deploy from branch
   - Branch: `main` / `root`
   - Save

3. **Your site will be live at**: `https://yourusername.github.io`

### Option 2: Local Development (with Ruby/Jekyll)
1. **Install Ruby and Bundler** (if not installed):
   - Windows: https://rubyinstaller.org/
   - Mac: `brew install ruby`
   - Linux: `sudo apt-get install ruby-full`

2. **Install dependencies**:
   ```bash
   cd c:\mhdev01
   bundle install
   ```

3. **Run local server**:
   ```bash
   bundle exec jekyll serve
   ```

4. **View at**: `http://localhost:4000`

### Option 3: Simple HTTP Server (No Jekyll)
If you want to preview without Jekyll:
```bash
cd c:\mhdev01
python -m http.server 8000
```
Then manually change `.md` files to `.html` in your browser URL.

## Customization

### Update Your Information
1. **Edit `_config.yml`**:
   - Update `title`, `email`, `linkedin`, `github`
   - Modify navigation items if needed

2. **Replace Resume**:
   - Add your `resume.pdf` to the root directory

3. **Update Content**:
   - Edit `index.md`, `about.md`, `projects.md`, etc.
   - Update project descriptions and technologies

### Change Colors
Edit `assets/css/main.css` CSS variables:
```css
:root {
  --color-accent-primary: #8b5cf6;    /* Purple */
  --color-accent-secondary: #06b6d4;  /* Cyan */
  /* ... other colors ... */
}
```

### Add More Projects
Edit `projects.md` and add a new project card:
```html
<div id="project-name" class="project-card">
  <img src="{{ '/assets/images/project-name.png' | relative_url }}" alt="Project Name">
  <div class="project-content">
    <h2>Project Title</h2>
    <p>Description...</p>
    <div class="tech-badges">
      <span class="badge">Tech1</span>
      <span class="badge">Tech2</span>
    </div>
  </div>
</div>
```

## Browser Support
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Technologies Used
- **Jekyll**: Static site generator
- **HTML5**: Semantic markup
- **CSS3**: Custom properties, Grid, Flexbox
- **JavaScript**: Vanilla JS for interactions
- **Font Awesome**: Icons
- **Google Fonts**: Inter & Space Grotesk

## File Checklist
Before deployment, ensure:
- [ ] Profile photo is in `assets/images/profile-photo.jpg`
- [ ] Resume PDF is added as `resume.pdf`
- [ ] All personal information is updated in `_config.yml`
- [ ] GitHub username is correct in all links
- [ ] Email address is correct
- [ ] LinkedIn URL is correct

## Troubleshooting

### Jekyll Build Errors
- Ensure Ruby and Bundler are installed
- Run `bundle install` to install dependencies
- Check `_config.yml` for syntax errors

### Images Not Loading
- Verify image paths in `assets/images/`
- Check that filenames match exactly (case-sensitive)
- Ensure images are committed to Git

### Styling Issues
- Clear browser cache
- Check browser console for CSS errors
- Verify `assets/css/main.css` is loading

## License
This portfolio template is free to use and customize for your own portfolio.

## Contact
For questions about this portfolio, contact: ebosmani@gmail.com

---

**Built with ❤️ using Jekyll and modern web technologies**
