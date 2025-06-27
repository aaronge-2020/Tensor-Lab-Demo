# Tensor Lab Website

A professionally designed website for marketing Tensor Lab, a cutting-edge research organization focused on artificial intelligence, machine learning, and computational mathematics.

## Features

### 🎨 **Modern Design**
- Clean, professional aesthetic with gradient accents
- Responsive design that works on all devices
- Smooth animations and hover effects
- Typography optimized for readability

### 📱 **Responsive Layout**
- Mobile-first design approach
- Hamburger menu for mobile navigation
- Flexible grid systems that adapt to screen size
- Touch-friendly interface elements

### 🚀 **Interactive Elements**
- Animated tensor cubes in hero section
- Smooth scrolling navigation
- Contact form with validation
- Notification system for user feedback
- Parallax effects and scroll animations

### 🧭 **Navigation**
- Fixed header with blur effect on scroll
- Active section highlighting
- Smooth scroll to sections
- Keyboard navigation support

## Sections

1. **Hero Section** - Eye-catching introduction with animated visuals
2. **About** - Organization mission, statistics, and key features
3. **Research Areas** - Detailed overview of research focus areas
4. **Team** - Team member profiles with social links
5. **Publications** - Showcase of recent research publications
6. **Contact** - Contact information and inquiry form
7. **Footer** - Additional links and social media

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Web server (optional, for local development)

### Running the Website

#### Option 1: Direct File Opening
1. Download all files to a local directory
2. Open `index.html` in your web browser
3. The website will load with full functionality

#### Option 2: Local Web Server (Recommended)
```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open your browser to `http://localhost:8000`

## File Structure

```
tensor-lab-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Customization

### Colors and Branding
The website uses a purple gradient color scheme. To change colors:

1. **Primary Colors**: Edit the gradient values in `styles.css`
   ```css
   /* Main brand gradient */
   background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
   ```

2. **Text Colors**: Update color variables throughout the CSS

### Content Updates

#### Team Members
Update the team section in `index.html`:
```html
<div class="team-member">
    <div class="member-photo">
        <div class="placeholder-avatar">
            <i class="fas fa-user"></i>
        </div>
    </div>
    <h3>Your Name</h3>
    <p class="member-role">Your Role</p>
    <p class="member-bio">Your bio...</p>
    <div class="member-social">
        <!-- Add your social links -->
    </div>
</div>
```

#### Publications
Add your publications in the publications section:
```html
<div class="publication-item">
    <div class="pub-info">
        <h3>Paper Title</h3>
        <p class="pub-authors">Authors</p>
        <p class="pub-venue">Conference/Journal</p>
        <p class="pub-description">Description...</p>
    </div>
    <div class="pub-links">
        <a href="link-to-paper" class="btn btn-small">Paper</a>
        <a href="link-to-code" class="btn btn-small btn-outline">Code</a>
    </div>
</div>
```

#### Contact Information
Update contact details in the contact section:
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div>
        <h4>Email</h4>
        <p>your-email@tensorlab.org</p>
    </div>
</div>
```

### Adding Photos
To replace placeholder avatars with actual photos:

1. Add image files to your directory
2. Replace the placeholder avatar HTML:
   ```html
   <!-- Replace this -->
   <div class="placeholder-avatar">
       <i class="fas fa-user"></i>
   </div>
   
   <!-- With this -->
   <img src="path-to-photo.jpg" alt="Person Name" style="width: 120px; height: 120px; border-radius: 50%; object-fit: cover;">
   ```

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- Optimized CSS with efficient selectors
- Lazy loading animations with Intersection Observer
- Smooth 60fps animations using transform and opacity
- Minimal JavaScript footprint
- CDN-hosted fonts and icons

## SEO Optimized

- Semantic HTML structure
- Meta tags for search engines
- Descriptive alt texts (when images are added)
- Proper heading hierarchy
- Fast loading times

## Accessibility Features

- Keyboard navigation support
- Focus indicators for interactive elements
- Semantic HTML elements
- ARIA labels where needed
- High contrast ratios for text

## Dependencies

### External CDNs Used:
- **Google Fonts**: Inter font family
- **Font Awesome**: Icons (version 6.4.0)

All dependencies are loaded from CDNs, so an internet connection is required for full functionality.

## Deployment

### GitHub Pages
1. Create a GitHub repository
2. Upload files to the repository
3. Enable GitHub Pages in repository settings
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop the folder to Netlify
2. Your site will be deployed instantly

### Traditional Web Hosting
1. Upload files via FTP to your web server
2. Ensure `index.html` is in the root directory

## Contact Form Integration

The contact form currently shows a success message. To make it functional:

1. **Backend Integration**: Connect to a server-side script (PHP, Node.js, etc.)
2. **Form Services**: Use services like Formspree, Netlify Forms, or Typeform
3. **Email Services**: Integrate with EmailJS for client-side email sending

Example with Formspree:
```html
<form class="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
```

## License

This website template is created for Tensor Lab. Feel free to modify and use as needed for your research organization.

## Support

For questions about customization or technical issues, please refer to the code comments or create an issue in your repository. # Tensor-Lab-Demo
