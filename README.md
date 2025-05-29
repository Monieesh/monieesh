# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Features a beautiful UI with particle effects, custom cursor, and smooth animations.

## Features

- Responsive design that works on all devices
- Particle.js background effects
- Custom cursor with follow effect
- Smooth scroll animations
- Modern card-based layout
- Gallery with featured projects
- Contact information section
- Mobile-friendly navigation

## Directory Structure

```
.
├── index.html              # Main portfolio page
├── gallery.html           # Gallery page
├── assets/
│   ├── css/
│   │   └── style.css     # Main stylesheet
│   ├── images/           # Image assets
│   │   ├── m1.jpg       # Profile image
│   │   ├── featured1.jpg
│   │   ├── featured2.jpg
│   │   ├── gallery1.jpg
│   │   ├── gallery2.jpg
│   │   └── gallery3.jpg
│   └── js/              # JavaScript files (if needed)
└── README.md            # This file
```

## Deployment

### Deploying to Netlify

1. Create a Netlify account at [netlify.com](https://www.netlify.com)
2. Connect your GitHub repository or drag and drop your project folder
3. Your site will be automatically deployed

### Deploying to Render

1. Create a Render account at [render.com](https://render.com)
2. Create a new Static Site
3. Connect your GitHub repository or upload your files
4. Your site will be automatically deployed

## Customization

### Personal Information

1. Open `index.html` and update:
   - Your name in the nav-brand section
   - Hero section content
   - About section text
   - Experience details
   - Skills
   - Projects
   - Contact information

2. Open `gallery.html` and update:
   - Gallery images and descriptions
   - Featured projects

### Images

1. Replace the images in the `assets/images/` directory with your own:
   - Replace `m1.jpg` with your profile picture
   - Add your project images
   - Update gallery images

### Social Links

Update the social media links in both `index.html` and `gallery.html`:
```html
<div class="social-links">
    <a href="https://github.com/yourusername" class="social-link">...</a>
    <a href="https://linkedin.com/in/yourusername" class="social-link">...</a>
    <a href="https://twitter.com/yourusername" class="social-link">...</a>
</div>
```

### Colors

The color scheme can be customized in `assets/css/style.css`. Look for the `:root` section:

```css
:root {
    --primary-color: #FFD700;
    --primary-gradient: linear-gradient(135deg, #FFD700, #FFA500);
    --secondary-color: #1a1a1a;
    /* ... other color variables ... */
}
```

## Dependencies

- Font Awesome 6.0.0
- Google Fonts (Orbitron, Roboto)
- Particles.js

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License. 