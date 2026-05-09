# Aman Sharma - Portfolio Website

A modern, responsive portfolio website built with pure HTML, CSS, and JavaScript. Features a dark theme with stunning animations and particle effects.

![Portfolio Preview](https://img.shields.io/badge/Portfolio-Live-success?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Features

- 🌙 **Dark Theme** - Modern dark UI with gradient accents
- ✨ **Particle Animation** - Floating particles background effect
- 🖱️ **Custom Cursor** - Animated cursor with hover effects (desktop)
- 📱 **Fully Responsive** - Works on all devices
- 🎭 **Scroll Animations** - Elements fade in as you scroll
- ⚡ **Fast Loading** - Pure HTML/CSS/JS, no heavy frameworks
- 🎯 **SEO Optimized** - Meta tags and semantic HTML

## 🚀 Live Demo

**[View Live Portfolio →](https://krishnendumajumder.github.io/portfolio)** *(Update with your GitHub Pages URL)*

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── README.md           # Project documentation
└── .github/
    └── workflows/      # GitHub Actions (optional)
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, grid, flexbox, animations
- **JavaScript** - Intersection Observer, event handling
- **Google Fonts** - Space Grotesk & Fira Code

## 📱 Sections

1. **Hero** - Introduction with animated code card
2. **Skills** - Tech stack with proficiency bars
3. **Projects** - Featured work showcase
4. **About** - Personal story and stats
5. **Contact** - Contact form and social links

## 🚀 Deploy to GitHub Pages

### Step 1: Create GitHub Repository
1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `portfolio` or `krishnendumajumder.github.io` (for username.github.io site)
3. Make it **Public**

### Step 2: Upload Files
```bash
# Initialize git
git init

# Add remote repository
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git

# Add files
git add .
git commit -m "Initial portfolio commit"

# Push to GitHub
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under "Source", select **Deploy from a branch**
4. Select **main** branch and **/ (root)** folder
5. Click **Save**
6. Wait 2-3 minutes for the site to deploy

### Step 4: Your Site is Live! 🎉
Your portfolio will be available at:
- `https://YOUR_USERNAME.github.io/portfolio` (if using /portfolio repo)
- `https://YOUR_USERNAME.github.io` (if using username.github.io repo)

## 📝 Customization Guide

### Update Personal Information

Edit `index.html` and modify:

```html
<!-- Hero Section -->
<h1>Hi, I'm<br><span class="name-accent">Aman Sharma.</span></h1>

<!-- About Section -->
<p>I'm <strong style="color:#fff">Aman Sharma</strong>, a self-driven Web Developer...</p>

<!-- Footer -->
<p>Designed & built with ❤️ by <span style="color:var(--accent)">Aman Sharma</span></p>
```

### Update Social Links

Find the social sidebar section and update URLs:

```html
<a href="https://github.com/YOUR_USERNAME" target="_blank" title="GitHub">
<a href="https://linkedin.com/in/YOUR_USERNAME" target="_blank" title="LinkedIn">
<a href="https://twitter.com/YOUR_USERNAME" target="_blank" title="Twitter">
<a href="mailto:your.email@example.com" title="Email">
```

### Update Projects

Find the projects section and modify project cards:

```html
<div class="project-card reveal">
  <div class="project-img" style="background:linear-gradient(...)">🎨</div>
  <div class="project-body">
    <div class="project-tags"><span class="tag">Tech</span></div>
    <div class="project-name">Project Name</div>
    <p class="project-desc">Description...</p>
    <div class="project-links">
      <a href="https://github.com/..." class="proj-link">GitHub</a>
      <a href="https://..." class="proj-link">Live Demo</a>
    </div>
  </div>
</div>
```

### Update Skills

Modify skill cards in the skills section:

```html
<div class="skill-card reveal">
  <span class="skill-icon">🌐</span>
  <div class="skill-name">HTML5</div>
  <div class="skill-level">Expert</div>
  <div class="skill-bar"><div class="skill-fill" style="width:95%"></div></div>
</div>
```

### Update Colors

Edit CSS variables in the `:root` selector:

```css
:root{
  --accent:#7c3aed;     /* Primary purple */
  --accent2:#06b6d4;    /* Secondary cyan */
  --accent3:#f59e0b;    /* Accent orange */
  --bg:#050510;         /* Background */
  --text:#e2e8f0;       /* Text color */
}
```

## 📄 Adding Your CV/Resume

1. Add your resume PDF to the repository root
2. Update the `downloadCV()` function:

```javascript
function downloadCV(){
  window.open('resume.pdf', '_blank');
}
```

## 🔧 Advanced Customization

### Adding a Favicon
1. Add `favicon.ico` or `favicon.png` to the root
2. Add this to `<head>`:

```html
<link rel="icon" type="image/x-icon" href="favicon.ico">
```

### Custom Domain (Optional)
1. Add a `CNAME` file with your domain:
```
www.krishnendumajumder.dev
```
2. Configure DNS with your domain provider
3. Enable HTTPS in GitHub Pages settings

## 📊 Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers

## 📧 Contact

- Email: hello@krishnendumajumder.dev
- GitHub: [@krishnendumajumder](https://github.com/Krishnendumajumder?tab=stars)
- LinkedIn: [Krishnendu Majumder](https://www.linkedin.com/in/krishnendu-majumder-a376b83a8)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**⭐ Star this repo if you found it helpful!**
