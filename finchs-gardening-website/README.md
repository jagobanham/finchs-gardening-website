# Finch's Gardening Services Website

This is a fully responsive website for Finch's Gardening Services, a local gardening business in Surrey, UK. The website showcases their services, portfolio, and provides a way for potential customers to request quotes.

## Website Structure

The website consists of the following pages:

1. **Home** (`index.html`) - Main landing page with hero banner, introduction, featured services, recent projects, testimonials, and call-to-action.
2. **About** (`about.html`) - Information about the company, team, values, and process.
3. **Services** (`services.html`) - Detailed information about all services offered.
4. **Portfolio** (`portfolio.html`) - Showcase of past projects with before/after images.
5. **Testimonials** (`testimonials.html`) - Customer reviews and feedback.
6. **Contact** (`contact.html`) - Contact form, map, and business information.

## Features

- Fully responsive design that works on all screen sizes
- Mobile-friendly navigation menu
- Interactive before/after image slider for portfolio projects
- Quote request modal accessible from any page
- Form validation for all forms
- Smooth scrolling for anchor links
- FAQ accordion on the contact page
- SEO-optimized with meta tags and descriptions

## File Structure

```
finchs-gardening-website/
├── css/
│   ├── normalize.css
│   └── styles.css
├── js/
│   └── main.js
├── images/
│   ├── finchs-logo.png
│   ├── hero-garden.png
│   ├── icon-*.png
│   ├── portfolio-*.png
│   ├── team-photo.png
│   └── testimonial-*.png
├── index.html
├── about.html
├── services.html
├── portfolio.html
├── testimonials.html
└── contact.html
```

## Technologies Used

- HTML5
- CSS3 (with CSS variables for theming)
- JavaScript (vanilla, no frameworks)
- Font Awesome for icons
- Google Fonts for typography

## Customization Guide

### Changing Colors

The website uses CSS variables for colors, which can be easily modified in the `css/styles.css` file. Look for the `:root` selector at the top of the file:

```css
:root {
    /* Primary Colors */
    --color-dark-green: #2A5D3C;
    --color-medium-green: #4A8C5F;
    --color-light-green: #8FBF9F;
    
    /* Neutral Colors */
    --color-dark-brown: #5D4A2A;
    --color-medium-brown: #8C7F5F;
    --color-light-beige: #F2EFE6;
    
    /* Accent Colors */
    --color-yellow: #F2C94C;
    /* ... more colors ... */
}
```

### Updating Content

To update the content of the website:

1. Open the HTML file for the page you want to modify
2. Find the section you want to update
3. Change the text or images as needed

### Adding New Services

To add a new service:

1. Open `services.html`
2. Copy an existing service item block
3. Paste it where you want the new service to appear
4. Update the content and ID

### Adding New Portfolio Projects

To add a new portfolio project:

1. Open `portfolio.html`
2. Copy an existing portfolio item block
3. Paste it where you want the new project to appear
4. Update the content, images, and ID

## Browser Compatibility

The website has been tested and works well in the following browsers:

- Google Chrome (latest)
- Mozilla Firefox (latest)
- Safari (latest)
- Microsoft Edge (latest)

## Deployment

The website is currently deployed at: [https://nnvikfvk.manus.space](https://nnvikfvk.manus.space)

To deploy the website to your own server:

1. Upload all files to your web server
2. Ensure the file structure is maintained
3. No special server configuration is required as this is a static website

## Support

For any questions or support regarding this website, please contact the developer.

---

© 2025 Finch's Gardening Services. All rights reserved.

