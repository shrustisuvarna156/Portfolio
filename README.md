# Personal Portfolio Website

A modern, dynamic, and responsive personal portfolio website built with HTML, CSS, and JavaScript. Features smooth animations, interactive elements, and a beautiful design.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: CSS animations and transitions for a polished user experience
- **Interactive Navigation**: Smooth scrolling navigation with active link highlighting
- **Dynamic Typing Animation**: Animated text that cycles through different titles
- **Work Portfolio Filter**: Filter projects by category (Web Apps, Mobile, Design)
- **Contact Form**: Functional contact form with validation and notifications
- **Parallax Effects**: Subtle parallax scrolling for enhanced visual appeal
- **Modern UI/UX**: Clean, professional design with hover effects and micro-interactions

## Sections

1. **Hero Section**: Eye-catching introduction with animated typing text and call-to-action buttons
2. **About Section**: Personal information, skills showcase, and animated statistics
3. **Experience Section**: Professional timeline with detailed work history
4. **Work Section**: Portfolio showcase with filtering capabilities
5. **Contact Section**: Contact form and personal information

## Setup Instructions

1. **Clone or Download**: Download all files to your local machine
2. **Open in Browser**: Simply open `index.html` in any modern web browser
3. **No Build Process Required**: This is a static website that runs directly in the browser

## Customization Guide

### Personal Information
Edit the following in `index.html`:

```html
<!-- Replace "Your Name" with your actual name -->
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>

<!-- Update hero description -->
<p class="hero-description">
    I'm a passionate developer creating amazing digital experiences. 
    Let's build something incredible together.
</p>

<!-- Update contact information -->
<div class="contact-details">
    <h4>Email</h4>
    <p>your.email@example.com</p>
</div>
```

### Skills and Technologies
Update the skills section in `index.html`:

```html
<div class="skill-tags">
    <span class="skill-tag">React</span>
    <span class="skill-tag">Vue.js</span>
    <span class="skill-tag">JavaScript</span>
    <!-- Add your skills here -->
</div>
```

### Work Experience
Modify the timeline items in `index.html`:

```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <div class="timeline-date">2023 - Present</div>
        <h3 class="timeline-title">Your Job Title</h3>
        <h4 class="timeline-company">Your Company</h4>
        <p class="timeline-description">
            Your job description and responsibilities.
        </p>
    </div>
</div>
```

### Portfolio Projects
Update work items in `index.html`:

```html
<div class="work-item" data-category="web">
    <div class="work-image">
        <div class="work-placeholder">
            <i class="fas fa-laptop-code"></i>
        </div>
        <div class="work-overlay">
            <div class="work-actions">
                <a href="your-project-url" class="work-link">
                    <i class="fas fa-external-link-alt"></i>
                </a>
                <a href="your-github-url" class="work-link">
                    <i class="fab fa-github"></i>
                </a>
            </div>
        </div>
    </div>
    <div class="work-content">
        <h3 class="work-title">Your Project Name</h3>
        <p class="work-description">
            Your project description.
        </p>
        <div class="work-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
    </div>
</div>
```

### Statistics
Update the statistics in `index.html`:

```html
<div class="stat-item">
    <div class="stat-number" data-target="50">0</div>
    <div class="stat-label">Projects Completed</div>
</div>
```

### Typing Animation
Modify the typing texts in `script.js`:

```javascript
const typingTexts = [
    'Frontend Developer',
    'Full Stack Developer',
    'UI/UX Designer',
    // Add your own titles
];
```

### Colors and Styling
Main color variables in `styles.css`:

```css
/* Primary colors */
--primary-color: #6366f1;
--secondary-color: #fbbf24;
--accent-color: #667eea;

/* Update these values to match your brand */
```

### Social Media Links
Update social media links in both the hero and contact sections:

```html
<div class="social-links">
    <a href="your-linkedin-url" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="your-github-url" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <!-- Add more social links -->
</div>
```

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- Optimized images and animations
- Throttled scroll events for smooth performance
- Lazy loading for animations
- Minimal dependencies (only Font Awesome and Google Fonts)

## Contact Form

The contact form is currently set up for demonstration purposes. To make it functional:

1. **Backend Integration**: Connect to a backend service (Node.js, PHP, Python, etc.)
2. **Email Service**: Use services like EmailJS, Formspree, or Netlify Forms
3. **Database**: Store form submissions in a database

Example with EmailJS:
```javascript
// Replace the form submission handler in script.js
emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', {
    name: name,
    email: email,
    subject: subject,
    message: message
});
```

## Deployment Options

1. **GitHub Pages**: Free hosting for static websites
2. **Netlify**: Easy deployment with form handling
3. **Vercel**: Fast deployment with great performance
4. **Traditional Web Hosting**: Upload files via FTP

## Tips for Customization

1. **Images**: Replace placeholder icons with actual project screenshots
2. **Content**: Make all content personal and authentic
3. **SEO**: Add meta tags and structured data
4. **Analytics**: Integrate Google Analytics for tracking
5. **Performance**: Optimize images and minimize CSS/JS if needed

## Support

This is a template that you can customize to your needs. Feel free to modify any aspect of the design, content, or functionality to match your personal brand and requirements.

## License

This project is open source and available under the [MIT License](LICENSE).
