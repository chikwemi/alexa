# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design with smooth animations and mobile-friendly layout.

## Features

- ✨ Modern, responsive design
- 📱 Mobile-first approach
- 🎨 Smooth animations and transitions
- 📧 Contact form with validation
- 🔗 Social media integration
- 📊 Skills and projects showcase
- 🎯 Smooth scrolling navigation

## File Structure

```
Royalty/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Customization Guide

### 1. Personal Information

Update the following in `index.html`:

- **Name**: Replace "Your Name" with your actual name
- **Title**: Change "Full Stack Developer & Designer" to your profession
- **Description**: Update the hero description to match your background
- **Contact Information**: Update email, phone, and location in the contact section

### 2. Profile Picture

Replace the placeholder icon with your actual profile picture:

```html
<!-- Replace this in the hero section -->
<div class="profile-placeholder">
    <img src="your-photo.jpg" alt="Your Name" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
</div>
```

### 3. Projects

Update the projects section with your actual projects:

```html
<div class="project-card">
    <div class="project-image">
        <img src="project-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Description of your project</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link"><i class="fab fa-github"></i> Code</a>
            <a href="your-live-link" class="project-link"><i class="fas fa-external-link-alt"></i> Live</a>
        </div>
    </div>
</div>
```

### 4. Skills

Update the skills section with your actual skills and technologies:

```html
<div class="skill-item">
    <i class="fab fa-react"></i>
    <span>React</span>
</div>
```

### 5. Statistics

Update the about section statistics with your actual numbers:

```html
<div class="stat">
    <h3>5+</h3>
    <p>Years Experience</p>
</div>
```

### 6. Social Media Links

Update the footer social media links:

```html
<div class="footer-social">
    <a href="your-github" class="social-link"><i class="fab fa-github"></i></a>
    <a href="your-linkedin" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="your-twitter" class="social-link"><i class="fab fa-twitter"></i></a>
    <a href="your-instagram" class="social-link"><i class="fab fa-instagram"></i></a>
</div>
```

### 7. Colors and Styling

Customize the color scheme in `styles.css`:

```css
/* Primary color */
:root {
    --primary-color: #2563eb;
    --secondary-color: #fbbf24;
    --text-color: #1f2937;
    --background-color: #ffffff;
}
```

## Getting Started

1. **Open the website**: Double-click on `index.html` to open it in your browser
2. **Customize content**: Follow the customization guide above
3. **Add images**: Place your images in the same folder and update the HTML
4. **Deploy**: Upload the files to your web hosting service

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Technologies Used

- HTML5
- CSS3 (with Flexbox and Grid)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Inter)

## Features in Detail

### Navigation
- Fixed navigation bar with blur effect
- Smooth scrolling to sections
- Mobile hamburger menu
- Active section highlighting

### Hero Section
- Gradient background
- Typing animation effect
- Call-to-action buttons
- Profile picture placeholder

### About Section
- Statistics cards
- Responsive grid layout
- Hover animations

### Projects Section
- Project cards with hover effects
- Technology tags
- Links to code and live demos

### Skills Section
- Categorized skills display
- Icon-based skill representation
- Hover animations

### Contact Section
- Contact form with validation
- Contact information display
- Form submission handling

### Footer
- Social media links
- Copyright information

## Performance Tips

1. **Optimize images**: Use compressed images for faster loading
2. **Minimize CSS/JS**: Consider minifying files for production
3. **Use CDN**: Font Awesome and Google Fonts are loaded from CDN
4. **Lazy loading**: Consider implementing lazy loading for images

## Deployment Options

### GitHub Pages
1. Create a GitHub repository
2. Upload your files
3. Enable GitHub Pages in repository settings

### Netlify
1. Drag and drop your folder to Netlify
2. Get instant deployment

### Vercel
1. Connect your GitHub repository
2. Deploy automatically

## Customization Examples

### Adding a Blog Section
```html
<section id="blog" class="blog">
    <div class="container">
        <h2 class="section-title">Blog</h2>
        <div class="blog-grid">
            <!-- Add your blog posts here -->
        </div>
    </div>
</section>
```

### Adding a Resume Download
```html
<div class="hero-buttons">
    <a href="#projects" class="btn btn-primary">View My Work</a>
    <a href="resume.pdf" class="btn btn-secondary" download>Download Resume</a>
</div>
```

## Support

If you need help customizing your portfolio, feel free to:
- Check the code comments for guidance
- Modify the CSS variables for easy color changes
- Add or remove sections as needed

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy coding! 🚀** 