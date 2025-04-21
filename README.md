# 3D Portfolio Website

A modern, responsive 3D portfolio website showcasing projects and skills with engaging animations and interactive elements.

## Features

- 🚀 Fully responsive design that works on all devices
- 🌙 Dark/Light theme toggle with localStorage persistence
- 🌟 Interactive 3D elements using Three.js
- ✨ Smooth scroll animations and parallax effects
- 📱 Mobile-friendly navigation with hamburger menu
- 📝 Functional contact form (frontend only)
- 🎨 Modern UI/UX with engaging animations
- 🖥️ Project showcase with hover effects
- 📄 Resume download functionality

## Technologies Used

- HTML5
- CSS3 with modern features (CSS variables, flexbox, grid)
- JavaScript (ES6+)
- Three.js for 3D effects
- GSAP for animations
- Intersection Observer API for scroll animations
- Font Awesome for icons

## Getting Started

1. Clone this repository
2. Open `index.html` in your browser
3. Customize the content in HTML files to match your information
4. Replace placeholder images with your own
5. Update the resume.pdf file with your actual resume

## Customization

### Colors

You can easily change the color scheme by editing the CSS variables in the `:root` selector in `styles.css`:

```css
:root {
    --primary-color: #6c63ff;
    --secondary-color: #4a42e8;
    /* other variables */
}
```

### Content

Update the HTML file to replace placeholder content with your own information:

- Personal information in the about section
- Skills in the skills section
- Projects in the projects section
- Contact information

### Projects

Add or remove project cards in the projects section of `index.html`. Each project should follow this structure:

```html
<div class="project-card">
    <div class="project-content">
        <h3>Project Name</h3>
        <p class="project-tech">Technologies Used</p>
        <p class="project-description">Project description goes here.</p>
        <div class="project-links">
            <a href="project-url" target="_blank" class="project-link">
                <i class="fab fa-github"></i> View Repository
            </a>
        </div>
    </div>
    <div class="project-image">
        <!-- Add your project image here -->
    </div>
</div>
```

## License

Feel free to use this template for your personal portfolio.

## Credits

- [Three.js](https://threejs.org/) - For 3D graphics
- [Font Awesome](https://fontawesome.com/) - For icons
- [Google Fonts](https://fonts.google.com/) - For typography
- [GSAP](https://greensock.com/gsap/) - For animations 