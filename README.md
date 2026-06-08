# Jass Pixels - Digital Product Design Studio Website

A professional, responsive portfolio website for Jass Pixels, a digital design and branding studio.

## Features

✨ **Modern Design**
- Clean, professional aesthetic with custom color palette
- Smooth animations and transitions
- Fully responsive design (desktop, tablet, mobile)

🎯 **Conversion Optimized**
- Clear call-to-action buttons
- FAQ section to address common questions
- Easy-to-use contact form
- Trust indicators (stats section)

🚀 **Performance**
- Lightweight and fast-loading
- Optimized images and SVG graphics
- Smooth scroll animations
- Mobile-first approach

📱 **Responsive Sections**
1. **Navigation** - Sticky header with smooth navigation
2. **Hero** - Eye-catching introduction with visual cards
3. **Stats** - Key metrics to build credibility
4. **Services** - 4 core service offerings with icons
5. **Portfolio** - Filterable project showcase
6. **Process** - Clear 4-step workflow
7. **FAQ** - Expandable frequently asked questions
8. **Contact** - Contact form + contact information
9. **Footer** - Social links and legal

## Quick Start

### 1. Local Testing
Simply open `portfolio.html` in your web browser:
- Windows: Double-click the file
- Mac/Linux: Right-click → Open with → Browser

### 2. Customize Your Content

Edit these sections in `portfolio.html`:

**Company Details:**
```html
<div class="nav-logo">jass_pixels<span> . </span>studio</div>
```

**Contact Information:**
```html
<span>hello@made.studio</span>
<span>Typically responds in < 24 hours</span>
```

**Hero Section:**
- Update heading and description
- Replace placeholder images (1.jpeg, 2.jpeg, etc.)

**Portfolio Projects:**
- Update project titles and tags
- Customize SVG placeholder graphics or replace with images

**Contact Form:**
- Update email address
- Customize service options

### 3. Adding Images

Create an `assets` folder:
```
/JassPixels
├── portfolio.html
├── assets/
│   ├── images/
│   │   ├── logo.png
│   │   ├── hero-1.jpg
│   │   ├── project-1.jpg
│   │   └── ...
│   └── logos/
└── README.md
```

Replace `<img src="1.jpeg" alt="">` with actual image paths:
```html
<img src="assets/images/project-1.jpg" alt="Project name">
```

## Deployment Options

### Option 1: Netlify (Recommended - FREE)

**Steps:**
1. Create a free account at [netlify.com](https://www.netlify.com)
2. Drag and drop the `portfolio.html` file (or entire folder)
3. Your site goes live instantly!
4. Custom domain available ($12/year or free .netlify.com)

**Advantages:**
- Free hosting
- Instant deployment
- Free SSL certificate
- Fast CDN worldwide

### Option 2: Vercel

**Steps:**
1. Create account at [vercel.com](https://vercel.com)
2. Connect your GitHub/GitLab repository (or upload directly)
3. Deploy automatically
4. Automatic previews for every change

**Advantages:**
- Free for individuals
- Git integration
- Serverless functions available
- Edge caching for speed

### Option 3: GitHub Pages (FREE)

**Steps:**
1. Create GitHub account
2. Create repository: `yourusername.github.io`
3. Push `portfolio.html` to the repo
4. Your site is live at `yourusername.github.io`

**Advantages:**
- Completely free
- Built into GitHub
- Good for version control

### Option 4: Traditional Web Hosting

1. Purchase hosting (GoDaddy, Bluehost, etc.)
2. Upload files via FTP
3. Point domain to hosting

## Email Integration (Contact Form)

The contact form currently shows alerts. To actually send emails, add one of these services:

### Formspree (Easy, Free)
1. Go to [formspree.io](https://formspree.io)
2. Create an account
3. Update form action:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
  <!-- form fields -->
</form>
```

### Getform
1. Sign up at [getform.io](https://getform.io)
2. Create a form
3. Update form action with provided endpoint

## SEO Optimization

Already included:
- Meta description
- Keywords
- Open Graph tags for social sharing
- Semantic HTML structure
- Mobile-friendly design
- Fast page speed

Further improvements:
1. Add Google Analytics
2. Create sitemap.xml
3. Add robots.txt
4. Get Google Search Console
5. Build backlinks

## Browser Compatibility

✅ Tested and working on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

1. **Optimize images** - Use tools like TinyPNG
2. **Minimize CSS** - Use production-ready CSS
3. **Use WebP** - Modern image format
4. **Enable caching** - On hosting providers
5. **Content Delivery** - Use CDN for images

## Customization Guide

### Colors
Edit the CSS variables at the top:
```css
:root {
  --cream: #F7F3EE;      /* Background */
  --ink: #1A1714;        /* Text */
  --accent: #D4622A;     /* Buttons, highlights */
  --warm-mid: #C4A882;   /* Secondary accent */
  /* ... more colors ... */
}
```

### Fonts
Currently using:
- **Headings:** Playfair Display (elegant serif)
- **Body:** DM Sans (clean sans-serif)

Change in the `<link>` tag or use Google Fonts alternatives.

### Spacing
Adjust padding/margins in the CSS for different layouts.

## Support & Customization

For further customization:
- Update text content directly in HTML
- Modify colors in the `:root` CSS variables
- Adjust responsive breakpoints in `@media` queries
- Replace SVG graphics with real images

## File Structure

```
portfolio.html       # Main website file (all-in-one)
README.md           # This file
(optional) assets/  # Images and resources
```

## Tips for Success

1. **Professional Photos** - High-quality portfolio images boost credibility
2. **Updated Portfolio** - Show your best 5-10 projects
3. **Clear Messaging** - Help visitors understand what you do
4. **Fast Loading** - Optimize images before uploading
5. **Mobile First** - Always test on mobile devices
6. **Regular Updates** - Keep content fresh and current

---

**Ready to launch?** Start with Netlify - it takes just 2 minutes! 🚀
