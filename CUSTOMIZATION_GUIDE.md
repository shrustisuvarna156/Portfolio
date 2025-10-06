# Portfolio Customization Guide

This guide will help you customize your portfolio to match your personal brand and content, based on the design from [Darshan Rao's portfolio](https://darshanrao.github.io/Portfolio/).

## 🎯 Quick Start Checklist

- [ ] Replace all `[PLACEHOLDER]` text with your actual information
- [ ] Update personal details (name, email, social links)
- [ ] Add your work experience
- [ ] Add your projects
- [ ] Customize skills and technologies
- [ ] Update contact information
- [ ] Test on mobile devices

## 📝 Step-by-Step Customization

### 1. Personal Information (Hero Section)

**File: `index.html` (Lines 45-55)**

Replace the following placeholders:

```html
<!-- Replace these with your actual information -->
<p class="hero-email">your.email@example.com</p>
<h2 class="hero-name">Your Name</h2>
<h3 class="hero-subtitle">Your Professional Tagline</h3>
```

**Example:**
```html
<p class="hero-email">john.doe@example.com</p>
<h2 class="hero-name">John Doe</h2>
<h3 class="hero-subtitle">Full Stack Developer & AI Enthusiast</h3>
```

### 2. About Section

**File: `index.html` (Lines 70-85)**

Replace the placeholder paragraphs with your story:

```html
<p class="about-intro">
    I'm John, a passionate full-stack developer with 5 years of experience 
    building web applications and mobile apps. I specialize in React, Node.js, 
    and cloud technologies, with a keen interest in AI and machine learning.
</p>
<p class="about-details">
    My journey began with a Computer Science degree from XYZ University, 
    where I discovered my love for creating digital solutions that make 
    a real impact. I'm currently working as a Senior Developer at TechCorp, 
    leading a team of 4 developers and building scalable applications.
</p>
```

### 3. Skills Section

**File: `index.html` (Lines 90-120)**

Update your technical skills:

```html
<div class="skill-category">
    <h4>Languages</h4>
    <ul class="skill-list">
        <li>JavaScript</li>
        <li>Python</li>
        <li>TypeScript</li>
        <li>Java</li>
    </ul>
</div>
<div class="skill-category">
    <h4>Libraries & Frameworks</h4>
    <ul class="skill-list">
        <li>React</li>
        <li>Node.js</li>
        <li>Express</li>
        <li>TensorFlow</li>
    </ul>
</div>
<div class="skill-category">
    <h4>Cloud Services & DevOps</h4>
    <ul class="skill-list">
        <li>Amazon Web Services</li>
        <li>Docker</li>
        <li>Kubernetes</li>
    </ul>
</div>
```

### 4. Work Experience

**File: `index.html` (Lines 130-180)**

Update the tab buttons and content:

```html
<!-- Tab Buttons -->
<button class="tab-btn active" data-tab="company1">TechCorp</button>
<button class="tab-btn" data-tab="company2">StartupXYZ</button>
<button class="tab-btn" data-tab="company3">Freelance</button>

<!-- Tab Content -->
<div class="tab-panel active" id="company1">
    <h3 class="job-title">Senior Full Stack Developer @ TechCorp</h3>
    <p class="job-duration">Jan 2022 - Present</p>
    <ul class="job-responsibilities">
        <li>Led development of microservices architecture serving 100K+ users</li>
        <li>Mentored 4 junior developers and improved team productivity by 40%</li>
        <li>Implemented CI/CD pipelines reducing deployment time by 60%</li>
        <li>Designed and built React-based dashboard with real-time analytics</li>
    </ul>
</div>
```

### 5. Featured Projects

**File: `index.html` (Lines 190-280)**

Replace with your actual projects:

```html
<div class="work-item featured">
    <div class="work-text">
        <p class="work-label">Featured Project</p>
        <h3 class="work-title">E-Commerce Platform</h3>
        <div class="work-description">
            <p>A full-stack e-commerce solution built with React, Node.js, and MongoDB. 
            Features include user authentication, payment processing, inventory management, 
            and real-time order tracking. The platform handles 10,000+ daily transactions 
            with 99.9% uptime.</p>
        </div>
        <div class="work-tech">
            <span class="tech-tag">React</span>
            <span class="tech-tag">Node.js</span>
            <span class="tech-tag">MongoDB</span>
            <span class="tech-tag">Stripe API</span>
        </div>
        <div class="work-links">
            <a href="https://github.com/yourusername/project" class="work-link">
                <i class="fab fa-github"></i>
            </a>
            <a href="https://yourproject.com" class="work-link">
                <i class="fas fa-external-link-alt"></i>
            </a>
        </div>
    </div>
</div>
```

### 6. Other Projects

**File: `index.html` (Lines 290-380)**

Update with your additional projects:

```html
<div class="other-project-item">
    <div class="other-project-icon">
        <i class="fas fa-folder"></i>
    </div>
    <div class="other-project-content">
        <h4 class="other-project-title">Task Management App</h4>
        <p class="other-project-description">
            A collaborative task management application with real-time updates, 
            team collaboration features, and project tracking capabilities.
        </p>
        <div class="other-project-tech">
            <span class="tech-tag">React</span>
            <span class="tech-tag">Firebase</span>
        </div>
        <div class="other-project-links">
            <a href="https://github.com/yourusername/task-app" class="work-link">
                <i class="fab fa-github"></i>
            </a>
            <a href="https://taskapp.com" class="work-link">
                <i class="fas fa-external-link-alt"></i>
            </a>
        </div>
    </div>
</div>
```

### 7. Contact Information

**File: `index.html` (Lines 400-420)**

Update contact details:

```html
<div class="contact-content">
    <div class="social-links">
        <a href="https://github.com/yourusername" class="social-link">
            <i class="fab fa-github"></i>
        </a>
        <a href="https://linkedin.com/in/yourusername" class="social-link">
            <i class="fab fa-linkedin"></i>
        </a>
    </div>
    <p class="contact-email">john.doe@example.com</p>
</div>
```

### 8. What's Next Section

**File: `index.html` (Lines 390-400)**

Update with your current goals:

```html
<p class="whats-next-description">
    I'm actively seeking new opportunities in full-stack development and AI. 
    I'm particularly interested in roles where I can work with cutting-edge 
    technologies and contribute to innovative projects. I'm also open to 
    freelance opportunities and collaborations.
</p>
```

## 🎨 Design Customization

### Colors

**File: `styles.css`**

The main colors used in the design:

```css
/* Primary Colors */
--bg-primary: #0a192f;        /* Dark blue background */
--bg-secondary: #112240;      /* Slightly lighter blue */
--text-primary: #ccd6f6;      /* Light blue text */
--text-secondary: #8892b0;    /* Gray text */
--accent: #64ffda;            /* Teal accent color */
```

### Typography

**File: `styles.css`**

The font family is set to 'Inter':

```css
body {
    font-family: 'Inter', sans-serif;
}
```

You can change this to any Google Font by updating the link in `index.html` and the CSS.

### Layout Adjustments

**Container Width:**
```css
.container {
    max-width: 1000px; /* Adjust as needed */
}
```

**Section Spacing:**
```css
section {
    padding: 100px 0; /* Adjust vertical spacing */
}
```

## 📱 Mobile Responsiveness

The portfolio is fully responsive and includes:

- Mobile navigation menu
- Responsive grid layouts
- Touch-friendly buttons
- Optimized typography for mobile

## 🚀 Deployment

### Option 1: GitHub Pages (Recommended)

1. Create a repository named `yourusername.github.io`
2. Upload all files to the repository
3. Enable GitHub Pages in repository settings
4. Your site will be live at `https://yourusername.github.io`

### Option 2: Netlify

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your portfolio folder
3. Get instant deployment with custom URL

### Option 3: Vercel

1. Go to [vercel.com](https://vercel.com)
2. Import your project
3. Deploy with one click

## 📊 SEO Optimization

Add these meta tags to the `<head>` section in `index.html`:

```html
<meta name="description" content="Your Name - Full Stack Developer Portfolio">
<meta name="keywords" content="developer, portfolio, web development, javascript, react">
<meta name="author" content="Your Name">
<meta property="og:title" content="Your Name - Portfolio">
<meta property="og:description" content="Full Stack Developer specializing in...">
<meta property="og:type" content="website">
<meta property="og:url" content="https://yourusername.github.io">
```

## 🔧 Advanced Customizations

### Add Animations

You can add more animations by modifying `script.js`:

```javascript
// Example: Fade in animation for elements
const fadeInElements = document.querySelectorAll('.fade-in');
fadeInElements.forEach(element => {
    element.style.opacity = '0';
    element.style.transform = 'translateY(20px)';
    element.style.transition = 'all 0.6s ease';
});
```

### Add Dark/Light Mode

Add a toggle button and CSS variables for theme switching:

```css
:root {
    --bg-primary: #0a192f;
    --text-primary: #ccd6f6;
}

[data-theme="light"] {
    --bg-primary: #ffffff;
    --text-primary: #333333;
}
```

### Add Blog Section

You can add a blog section by creating a new section in the HTML and styling it similarly to the existing sections.

## 📝 Content Writing Tips

1. **Be Specific**: Use numbers and metrics when possible
2. **Show Impact**: Explain the results and benefits of your work
3. **Use Action Words**: Start bullet points with strong verbs
4. **Keep It Concise**: Aim for 1-2 sentences per bullet point
5. **Be Authentic**: Write in your own voice and style

## 🎯 Best Practices

1. **Regular Updates**: Keep your portfolio current with new projects
2. **Mobile Testing**: Always test on mobile devices
3. **Performance**: Optimize images and minimize file sizes
4. **Accessibility**: Ensure good contrast and keyboard navigation
5. **Backup**: Keep backups of your portfolio files

## 🆘 Troubleshooting

### Common Issues:

1. **Images not loading**: Check file paths and ensure images are in the correct folder
2. **Styling not applied**: Check CSS file path in HTML head
3. **JavaScript not working**: Check console for errors and ensure script.js is linked
4. **Mobile layout issues**: Test responsive design in browser dev tools

### Getting Help:

- Check browser console for error messages
- Validate HTML and CSS
- Test in different browsers
- Use browser dev tools to debug

## 📞 Support

If you need help customizing your portfolio, you can:

1. Check this guide thoroughly
2. Look at the original [Darshan Rao portfolio](https://darshanrao.github.io/Portfolio/) for reference
3. Use browser dev tools to inspect elements
4. Search for specific CSS/HTML solutions online

Remember: The key to a great portfolio is authentic content that showcases your unique skills and personality. Take time to craft compelling descriptions of your work and experiences!
