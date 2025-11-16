# 🚀 ML Engineer Portfolio Website

A modern, responsive portfolio website for Machine Learning Engineers, inspired by [aksh-ai.com](https://aksh-ai.com/).

## ✨ Features

- **Dark Theme** with gradient accents (cyan/teal color scheme)
- **Single-page Scroll Design** with smooth navigation
- **Fully Responsive** - works on mobile, tablet, and desktop
- **Animated Sections** - scroll-based reveal animations
- **Skills Progress Bars** - visual representation of expertise
- **Project Showcase** - grid layout with hover effects
- **Timeline Experience** - professional work history display
- **Contact Form** - with validation and notifications
- **Social Links** - GitHub, LinkedIn, Kaggle integration
- **Mobile Navigation** - hamburger menu for small screens

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML structure
├── styles.css          # Complete CSS styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization Guide

### 1. Personal Information

**Edit `index.html`:**

```html
<!-- Line 26: Update name -->
<a href="#home">Shiva</a>  <!-- Change to your name -->

<!-- Line 49: Update hero section -->
<h1 class="hero-title">
    Hi, I'm <span class="gradient-text">Shiva</span>  <!-- Your name -->
</h1>

<!-- Line 57: Update subtitle -->
<p class="hero-subtitle">
    Machine Learning Engineer | Data Science | AI Systems  <!-- Your titles -->
</p>

<!-- Line 60: Update description -->
<p class="hero-description">
    Building production-ready ML systems...  <!-- Your bio -->
</p>
```

### 2. Social Media Links

**Update lines 71-83 in `index.html`:**

```html
<a href="https://github.com/yourusername" target="_blank">
<a href="https://linkedin.com/in/yourusername" target="_blank">
<a href="https://kaggle.com/yourusername" target="_blank">
<a href="mailto:your.email@example.com">
```

Replace with your actual profiles.

### 3. About Section

**Edit lines 106-125 in `index.html`:**

```html
<p>
    I'm a passionate Machine Learning Engineer...  <!-- Your story -->
</p>

<!-- Update statistics -->
<h3>10+</h3>  <!-- Number of projects -->
<h3>5+</h3>   <!-- Years of experience -->
<h3>2+</h3>   <!-- Technologies mastered -->
```

### 4. Experience Timeline

**Replace the timeline items (lines 141-189):**

```html
<div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
        <h3>Your Job Title</h3>
        <p class="timeline-company">Company Name</p>
        <p class="timeline-date">Start - End Date</p>
        <ul class="timeline-description">
            <li>Achievement 1</li>
            <li>Achievement 2</li>
            <li>Achievement 3</li>
        </ul>
    </div>
</div>
```

Add/remove timeline items as needed.

### 5. Skills Section

**Adjust skill percentages (lines 207-360):**

```html
<div class="skill-bar">
    <div class="skill-info">
        <span>Deep Learning</span>
        <span>90%</span>  <!-- Change percentage -->
    </div>
    <div class="progress-bar">
        <div class="progress" style="width: 90%"></div>  <!-- Match here -->
    </div>
</div>
```

Add/remove skills as needed. Keep percentage values consistent.

### 6. Projects

**For each project (starting line 377):**

```html
<div class="project-card">
    <div class="project-image">
        <!-- Replace placeholder with your project image -->
        <img src="path/to/your/image.png" alt="Project Name">
        <div class="project-overlay">
            <a href="https://demo-link.com" class="project-link">
                <i class="fas fa-external-link-alt"></i>
            </a>
            <a href="https://github.com/yourusername/project" class="project-link">
                <i class="fab fa-github"></i>
            </a>
        </div>
    </div>
    <div class="project-content">
        <div class="project-tags">
            <span class="tag">Technology 1</span>
            <span class="tag">Technology 2</span>
        </div>
        <h3>Project Title</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <!-- Tech stack icons -->
            <i class="fab fa-python"></i>
            <i class="fas fa-brain"></i>
        </div>
        <ul class="project-highlights">
            <li><i class="fas fa-check"></i> Key metric 1</li>
            <li><i class="fas fa-check"></i> Key metric 2</li>
        </ul>
    </div>
</div>
```

**Project Image Tips:**
- Use 600x400px images for consistency
- Compress images for faster loading
- Use tools like [TinyPNG](https://tinypng.com/)
- Or use placeholder service: `https://via.placeholder.com/600x400/1a1a2e/00d9ff?text=Your+Project`

### 7. Contact Information

**Update lines 593-628 in `index.html`:**

```html
<p>Huntersville, North Carolina, US</p>  <!-- Your location -->
<a href="mailto:your.email@example.com">your.email@example.com</a>
<a href="https://linkedin.com/in/yourusername">linkedin.com/in/yourusername</a>
<a href="https://github.com/yourusername">github.com/yourusername</a>
```

### 8. Color Scheme Customization

**Edit `styles.css` (lines 6-14):**

```css
:root {
    --primary-color: #00d9ff;      /* Main accent color */
    --secondary-color: #ff6b6b;    /* Secondary accent */
    --accent-color: #4ecdc4;       /* Additional accent */
    --bg-dark: #0f0f1e;            /* Main background */
    --bg-darker: #0a0a14;          /* Darker sections */
    --bg-card: #1a1a2e;            /* Card backgrounds */
}
```

**Popular Color Schemes:**

**Blue/Purple:**
```css
--primary-color: #667eea;
--accent-color: #764ba2;
```

**Green/Teal:**
```css
--primary-color: #10b981;
--accent-color: #14b8a6;
```

**Orange/Red:**
```css
--primary-color: #f97316;
--accent-color: #ef4444;
```

### 9. Profile Image

**Replace the placeholder (line 93 in `index.html`):**

```html
<div class="placeholder-image">
    <i class="fas fa-user-astronaut"></i>
</div>
```

With an actual image:

```html
<img src="path/to/your/photo.jpg" 
     alt="Your Name" 
     style="width: 100%; height: 100%; object-fit: cover; border-radius: var(--radius-xl);">
```

## 🚀 Deployment Options

### Option 1: GitHub Pages (Free, Easiest)

1. Create a new GitHub repository named `yourusername.github.io`
2. Upload all files (index.html, styles.css, script.js)
3. Go to Settings → Pages
4. Select source: main branch
5. Your site will be live at `https://yourusername.github.io`

**Commands:**
```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

### Option 2: Netlify (Free, Fast)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your folder
3. Site goes live instantly
4. Free custom domain support

### Option 3: Vercel (Free, Fast)

1. Go to [vercel.com](https://vercel.com)
2. Import from GitHub or upload
3. Automatic deployments on every commit
4. Free custom domain

### Option 4: Custom Domain

**After deploying, add a custom domain:**

1. Buy domain from [Namecheap](https://namecheap.com) or [Google Domains](https://domains.google)
2. Add CNAME record pointing to your hosting
3. Update hosting settings with custom domain

## 📱 Responsive Testing

Test your portfolio on different devices:

**Desktop:**
- Chrome DevTools (F12) → Toggle Device Toolbar
- Test at: 1920px, 1440px, 1024px

**Tablet:**
- iPad: 768px
- iPad Pro: 1024px

**Mobile:**
- iPhone SE: 375px
- iPhone 12: 390px
- Galaxy S20: 360px

## ⚡ Performance Optimization

### 1. Optimize Images

```bash
# Install ImageMagick
sudo apt install imagemagick

# Resize images
convert input.jpg -resize 600x400 -quality 85 output.jpg
```

Or use online tools:
- [TinyPNG](https://tinypng.com/)
- [Squoosh](https://squoosh.app/)

### 2. Minify Code (Production)

Use [HTML Minifier](https://www.willpeavy.com/tools/minifier/) for HTML
Use [CSS Minifier](https://cssminifier.com/) for CSS
Use [JavaScript Minifier](https://javascript-minifier.com/) for JS

### 3. Add Favicon

Create `favicon.ico` (32x32px) and add to `<head>`:

```html
<link rel="icon" type="image/x-icon" href="favicon.ico">
```

### 4. Add Meta Tags for SEO

```html
<!-- In <head> section -->
<meta name="description" content="Your Name - ML Engineer Portfolio">
<meta name="keywords" content="Machine Learning, Data Science, AI, Portfolio">
<meta name="author" content="Your Name">

<!-- Open Graph for social sharing -->
<meta property="og:title" content="Your Name - ML Engineer">
<meta property="og:description" content="Production-ready ML systems specialist">
<meta property="og:image" content="https://yoursite.com/preview.jpg">
<meta property="og:url" content="https://yoursite.com">

<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Your Name - ML Engineer">
<meta name="twitter:description" content="Production-ready ML systems specialist">
<meta name="twitter:image" content="https://yoursite.com/preview.jpg">
```

## 🔧 Advanced Customizations

### Add Google Analytics

Add before closing `</head>` tag:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

### Enable Contact Form Backend

**Option 1: Formspree (Easiest)**

1. Go to [formspree.io](https://formspree.io)
2. Create free account
3. Get your form endpoint
4. Update form action in `index.html`:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

**Option 2: EmailJS**

1. Go to [emailjs.com](https://emailjs.com)
2. Setup email service
3. Add EmailJS SDK before closing `</body>`:

```html
<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
<script>
  emailjs.init('YOUR_PUBLIC_KEY');
</script>
```

### Add Blog Section

Add this section after Projects:

```html
<section id="blog" class="blog section">
    <div class="container">
        <h2 class="section-title">Blog</h2>
        <p class="section-subtitle">Technical Articles & Insights</p>
        
        <div class="blog-grid">
            <article class="blog-card">
                <div class="blog-image">
                    <img src="blog-image.jpg" alt="Blog post title">
                </div>
                <div class="blog-content">
                    <span class="blog-date">November 15, 2025</span>
                    <h3>Blog Post Title</h3>
                    <p>Brief description of the blog post...</p>
                    <a href="blog-post.html" class="btn btn-secondary">Read More</a>
                </div>
            </article>
        </div>
    </div>
</section>
```

Add corresponding CSS in `styles.css`:

```css
.blog-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: var(--spacing-lg);
}

.blog-card {
    background: var(--bg-card);
    border-radius: var(--radius-lg);
    overflow: hidden;
    box-shadow: var(--shadow-md);
    transition: var(--transition-base);
}

.blog-card:hover {
    transform: translateY(-10px);
    box-shadow: var(--shadow-lg);
}

.blog-image img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.blog-content {
    padding: var(--spacing-md);
}

.blog-date {
    color: var(--text-muted);
    font-size: var(--font-size-sm);
}
```

## 🐛 Troubleshooting

### Icons Not Showing

**Issue:** Font Awesome icons not loading

**Fix:** Verify CDN link in `<head>`:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```

### Smooth Scrolling Not Working

**Issue:** Navigation jumps instead of scrolling

**Fix:** Ensure `scroll-behavior: smooth` is in CSS:
```css
html {
    scroll-behavior: smooth;
}
```

### Mobile Menu Not Opening

**Issue:** Hamburger click does nothing

**Fix:** Check `script.js` is linked before `</body>`:
```html
<script src="script.js"></script>
```

### Progress Bars Not Animating

**Issue:** Skill bars stay at 0%

**Fix:** Check widths are set inline in HTML:
```html
<div class="progress" style="width: 90%"></div>
```

## 📚 Resources

**Design Inspiration:**
- [Dribbble](https://dribbble.com/search/portfolio) - Design ideas
- [Behance](https://www.behance.net/search/projects?search=portfolio) - Creative portfolios
- [Awwwards](https://www.awwwards.com/websites/portfolio/) - Award-winning designs

**Free Images:**
- [Unsplash](https://unsplash.com/) - High-quality photos
- [Pexels](https://www.pexels.com/) - Free stock photos
- [Pixabay](https://pixabay.com/) - Free images

**Icons:**
- [Font Awesome](https://fontawesome.com/) - Icon library
- [Heroicons](https://heroicons.com/) - Beautiful SVG icons
- [Feather Icons](https://feathericons.com/) - Simple icons

**Learning Resources:**
- [MDN Web Docs](https://developer.mozilla.org/) - HTML/CSS/JS reference
- [CSS-Tricks](https://css-tricks.com/) - CSS tutorials
- [JavaScript.info](https://javascript.info/) - Modern JS tutorial

## 📝 Checklist Before Going Live

- [ ] Updated all personal information
- [ ] Replaced all "yourusername" placeholders
- [ ] Added real project images
- [ ] Tested contact form
- [ ] Verified all links work
- [ ] Checked mobile responsiveness
- [ ] Optimized images for web
- [ ] Added favicon
- [ ] Setup Google Analytics (optional)
- [ ] Proofread all text content
- [ ] Tested in multiple browsers (Chrome, Firefox, Safari)
- [ ] Added custom domain (optional)
- [ ] Setup HTTPS certificate

## 🤝 Support

If you encounter any issues or need help customizing:

1. Check this README thoroughly
2. Inspect browser console for errors (F12)
3. Validate HTML at [W3C Validator](https://validator.w3.org/)
4. Test CSS at [CSS Validator](https://jigsaw.w3.org/css-validator/)

## 📄 License

Free to use for personal portfolios. Attribution appreciated but not required.

## 🎉 You're All Set!

Your portfolio is ready to showcase your ML engineering skills. Remember to:

1. Update content regularly with new projects
2. Keep skills section current
3. Add blog posts (if applicable)
4. Respond to contact form messages promptly

**Good luck with your job search! 🚀**

---

*Built with ❤️ inspired by [aksh-ai.com](https://aksh-ai.com/)*
