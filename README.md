# Portfolio Website

A professional, responsive portfolio website built with HTML and CSS.

## Features

✨ **Modern Design** - Clean, professional layout with smooth animations
📱 **Fully Responsive** - Looks great on desktop, tablet, and mobile devices
⚡ **Fast Loading** - Pure HTML/CSS, no heavy dependencies
🎨 **Customizable** - Easy to personalize with your information
🔗 **Easy Navigation** - Smooth scrolling between sections

## Files

- `index.html` - Main HTML file with all sections
- `styles.css` - All styling and responsive design

## Quick Start

1. Open `index.html` in your web browser
2. Or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (if you have http-server installed)
   http-server
   ```
3. Navigate to `http://localhost:8000` in your browser

## Customization

### Basic Information

1. **Name & Title**: Edit the hero section in `index.html`
   ```html
   <h1>Hi, I'm a Web Developer</h1>
   ```

2. **Email**: Update the email address in the Contact section
   ```html
   <a href="mailto:your-email@example.com">your-email@example.com</a>
   ```

### Projects

Edit the project cards in the Projects section. Each card includes:
- Project title
- Description
- Technology tags
- Link to project

Example:
```html
<div class="project-card">
    <div class="project-header">
        <h3>Your Project Name</h3>
    </div>
    <p>Your project description here.</p>
    <div class="project-tags">
        <span>Technology 1</span>
        <span>Technology 2</span>
    </div>
    <a href="https://your-project-link.com" class="project-link">View Project →</a>
</div>
```

### Skills

Update the skills section in the About area:
```html
<span class="skill-tag">Your Skill</span>
```

### Experience

Modify the timeline items in the Experience section with your actual work history:
```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <h3>Your Job Title</h3>
        <p class="company">Company Name</p>
        <p class="date">Year - Year</p>
        <p>Description of your role and achievements.</p>
    </div>
</div>
```

### Colors & Styling

Customize the color scheme by editing CSS variables in `styles.css`:

```css
:root {
    --primary-color: #0066cc;      /* Main blue color */
    --primary-dark: #004aa3;       /* Darker blue */
    --secondary-color: #f5f5f5;    /* Light gray background */
    --text-dark: #1a1a1a;          /* Dark text */
    --text-light: #666;             /* Light gray text */
}
```

### Fonts

Change the font family in `styles.css`:
```css
body {
    font-family: 'Your Font Name', sans-serif;
}
```

## Social Links

Update the social media links in the Contact section:
```html
<div class="social-links">
    <a href="https://github.com/yourusername" class="social-link">GitHub</a>
    <a href="https://linkedin.com/in/yourusername" class="social-link">LinkedIn</a>
    <a href="https://twitter.com/yourusername" class="social-link">Twitter</a>
</div>
```

## Deployment

You can deploy this website to:

- **GitHub Pages**: Free hosting directly from your GitHub repository
- **Netlify**: Connect your repo for easy deployment
- **Vercel**: Simple deployment platform
- **Any Web Hosting**: FTP upload to your hosting provider

## Tips

- Use high-quality project images if you add them
- Keep descriptions concise and impactful
- Regularly update your projects and experience
- Test on mobile devices before deploying
- Use actual links for projects and social profiles

## License

Feel free to use this template for your portfolio. Customize it as needed!

## Support

For questions about HTML/CSS, check out:
- [MDN Web Docs](https://developer.mozilla.org/)
- [W3Schools](https://www.w3schools.com/)
- [CSS-Tricks](https://css-tricks.com/)
