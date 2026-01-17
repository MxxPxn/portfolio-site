# Modern Portfolio Website

A clean, modern single-page portfolio website for showcasing your work as a Frontend Developer.

## 🚀 Quick Start

1. **Download the files** to your computer
2. **Open `index.html`** in your browser to see the site
3. **Customize** the content (see below)
4. **Deploy** to GitHub Pages or Vercel

## 📁 Project Structure

```
modern-portfolio/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styling
├── js/
│   └── main.js         # JavaScript for interactions
├── images/             # Place your project screenshots here
└── README.md           # This file
```

## ✏️ Customization Guide

### 1. Replace Placeholders

**Avatar (line 33-35 in index.html):**
```html
<!-- Current: initials placeholder -->
<div class="avatar-placeholder">MP</div>

<!-- Option 1: Add your photo -->
<img src="images/profile.jpg" alt="Maksym Panarin" class="avatar">

<!-- Option 2: Keep initials but change them -->
<div class="avatar-placeholder">YI</div>
```

**Project Screenshots:**
- Take screenshots of your deployed projects
- Save them in the `images/` folder
- Replace the placeholder divs (lines 181, 203, 225):

```html
<!-- Before -->
<div class="image-placeholder">Weather App Screenshot</div>

<!-- After -->
<img src="images/weather-app.png" alt="Weather Dashboard">
```

### 2. Update Your Information

**Hero Section (lines 37-47):**
- Name: Line 38
- Title/Role: Line 39
- Description: Lines 40-45

**About Section (lines 60-76):**
- Update all three paragraphs with your story
- Modify the "Download Resume" link (line 77)

**Skills Section (lines 89-156):**
- Edit skill titles and descriptions to match your strengths
- Keep or modify the 5 skill cards

**Projects (lines 180-229):**
- Update project titles, descriptions, and tech stacks
- Add/remove project cards as needed
- Update live demo links

**Contact Information:**
- Email: Lines 258, 268, 289
- Location: Line 269
- LinkedIn: Line 347
- GitHub: Line 338, 186

### 3. Color Customization

Edit `css/styles.css` (lines 1-18) to change colors:

```css
:root {
    --accent-primary: #4a9eff;    /* Change to your preferred color */
    --accent-hover: #3a8eef;      /* Slightly darker version */
}
```

**Color suggestions:**
- Blue (current): `#4a9eff`
- Green: `#4ade80`
- Purple: `#a78bfa`
- Orange: `#fb923c`

### 4. Add More Projects

Copy a project card block (lines 180-200) and paste it inside the `projects-grid` div:

```html
<div class="project-card" data-category="react typescript">
    <div class="project-image">
        <img src="images/your-project.png" alt="Project Name">
    </div>
    <div class="project-content">
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-description">Project description here</p>
        <div class="project-tech">
            <span class="tech-tag">React</span>
            <span class="tech-tag">TypeScript</span>
        </div>
        <div class="project-links">
            <a href="your-live-demo-url" target="_blank" class="project-link">
                <svg>...</svg>
            </a>
        </div>
    </div>
</div>
```

## 🌐 Deployment

### GitHub Pages

1. Create a new repository named `yourusername.github.io`
2. Push your files:
```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```
3. Your site will be live at `https://yourusername.github.io`

### Vercel

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Import your repository
4. Deploy (automatic)

## 🎨 Features

- ✅ Smooth scrolling navigation
- ✅ Project filtering
- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Scroll animations
- ✅ Contact form with mailto
- ✅ Social media links
- ✅ Modern, clean design

## 📱 Testing

Test your portfolio on different screen sizes:
- Desktop: 1920px, 1440px, 1280px
- Tablet: 768px
- Mobile: 375px, 414px

## 🐛 Common Issues

**Images not showing:**
- Make sure images are in the `images/` folder
- Check file names match exactly (case-sensitive)
- Use relative paths: `images/project.png`

**Contact form not working:**
- The form uses `mailto:` which opens the user's email client
- For a real form, use services like Formspree or EmailJS

**Smooth scrolling not working:**
- Make sure `js/main.js` is loaded
- Check browser console for errors

## 📝 To-Do After Setup

- [ ] Add real project screenshots
- [ ] Update all personal information
- [ ] Test on mobile devices
- [ ] Check all links work
- [ ] Add your resume PDF (if using download button)
- [ ] Deploy to GitHub Pages or Vercel
- [ ] Share your portfolio URL on LinkedIn/Resume

## 🎯 Next Steps

Once your portfolio is live:
1. Update your LinkedIn with the portfolio URL
2. Add it to your resume header
3. Include it in job applications
4. Get feedback from developer communities
5. Keep adding projects as you build them

## 📧 Questions?

If you need help customizing anything, just ask!

---

Built with ❤️ by Maksym Panarin
