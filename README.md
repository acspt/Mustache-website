# Portfolio Website - Static HTML

A modern, responsive portfolio website built with component-based HTML templates. This project showcases a clean architecture using reusable components and modern web technologies.

## Features

- **Component-Based Architecture**: Modular HTML structure with reusable components
- **Responsive Design**: Mobile-first approach with modern CSS Grid and Flexbox
- **Interactive Elements**: JavaScript-powered navigation, project filtering, and animations
- **Modern UI**: Clean, professional design with smooth transitions and hover effects
- **SEO Friendly**: Semantic HTML structure and proper meta tags
- **Static Files**: No server required - runs directly in any web browser

## Project Structure

```
portfolio/
├── assets/
│   ├── css/
│   │   └── styles.css              # Main stylesheet
│   └── js/
│       └── main.js                 # Interactive JavaScript
├── templates/                      # Mustache templates (for reference)
│   ├── partials/
│   │   ├── header.mustache         # Navigation header component
│   │   ├── footer.mustache         # Footer component
│   │   ├── feature-card.mustache   # Feature card component
│   │   ├── skills-section.mustache # Skills section component
│   │   ├── timeline-item.mustache  # Timeline item component
│   │   ├── project-card.mustache   # Project card component
│   │   ├── contact-info-cards.mustache # Contact info cards component
│   │   └── contact-form.mustache   # Contact form component
│   ├── layout.mustache             # Base layout template
│   ├── index.mustache              # Home page template
│   ├── about.mustache              # About page template
│   ├── projects.mustache           # Projects page template
│   └── contact.mustache            # Contact page template
├── index.html                      # Compiled home page
├── about.html                      # Compiled about page
├── projects.html                   # Compiled projects page
├── contact.html                    # Compiled contact page
└── README.md                       # This file
```

## Pages Overview

### Home Page (`index.html`)
- Hero section with call-to-action
- Features/services overview
- Call-to-action section

### About Page (`about.html`)
- Personal story and background
- Skills section organized by category
- Experience and education timeline

### Projects Page (`projects.html`)
- Project portfolio with filtering functionality
- Category-based project organization (Web Apps, Mobile, APIs)
- Interactive project cards with hover effects

### Contact Page (`contact.html`)
- Contact information with icons
- Functional contact form with validation
- Social media links

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Grid and Flexbox
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icon library
- **Mustache.js**: Template engine (for development)

## Quick Start

1. **Download or clone the project**

2. **Open in browser**:
   Simply open `index.html` in any modern web browser.

3. **View locally**:
   ```
   Open index.html directly in your browser
   or
   Use a local server like Live Server in VS Code
   ```

## Features in Detail

### Responsive Design
- Mobile-first approach
- Breakpoints for tablets and desktops
- Flexible grid layouts

### Interactive Elements
- Smooth scrolling navigation
- Project filtering by category
- Form validation and submission simulation
- Hover effects and animations
- Mobile menu toggle

### Navigation
- Portuguese labels: "Projectos" and "Contactos"
- Consistent navigation across all pages
- Mobile-responsive hamburger menu

### Performance Optimizations
- Efficient CSS with minimal dependencies
- Optimized JavaScript with event delegation
- Semantic HTML structure

## Customization

### Updating Content
- Edit the HTML files directly to change text content
- Replace placeholder icons and content with your own information
- Update social media links in the footer

### Styling Changes
- Edit `assets/css/styles.css` for styling modifications
- The CSS is organized by sections (navigation, hero, features, etc.)

### Adding New Sections
- Add new HTML sections to any page
- Use existing CSS classes or add new ones
- Follow the established component pattern

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT License - feel free to use this project for your own portfolio!

## Template Development

The `templates/` folder contains the original Mustache templates used to generate the static HTML files. These can be used for future updates or as a reference for the component structure.
