# Broadleaf Commerce Template

A responsive frontend template that replicates the visual design and layout of the Broadleaf Commerce website (https://broadleafcommerce.com/).

## Overview

This template captures the modern, professional design of Broadleaf Commerce with:
- Clean, responsive layout
- Colorful navigation with hover effects
- Hero section with geometric shapes and animations
- Modern typography using Manrope font
- Interactive tabs and smooth scrolling
- Mobile-responsive design

## Technologies Used

### Frontend Frameworks & Libraries
- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox and Grid
- **Vanilla JavaScript**: Interactive functionality without heavy frameworks
- **Google Fonts**: Manrope font family for typography
- **Font Awesome**: Icon library for UI elements

### Design Features
- **Responsive Design**: Mobile-first approach with breakpoints
- **CSS Grid & Flexbox**: Modern layout techniques
- **CSS Animations**: Smooth transitions and hover effects
- **Gradient Backgrounds**: Modern visual styling
- **Box Shadows**: Depth and elevation effects

### JavaScript Features
- **Intersection Observer API**: Scroll-based animations
- **Event Listeners**: Interactive elements
- **Smooth Scrolling**: Enhanced navigation experience
- **Mobile Menu**: Responsive navigation
- **Tab Functionality**: Dynamic content switching

## Installation

### Prerequisites
- A modern web browser
- A local web server (optional, for development)

### Setup Instructions

1. **Download the template**:
   ```bash
   # Extract the provided zip file to your desired location
   unzip broadleaf-template.zip
   cd broadleaf-template
   ```

2. **Open in browser**:
   - Simply open `index.html` in your web browser
   - Or use a local development server:

   ```bash
   # Using Python (if installed)
   python -m http.server 8000
   
   # Using Node.js (if installed)
   npx serve .
   
   # Using PHP (if installed)
   php -S localhost:8000
   ```

3. **Access the template**:
   - Direct file: `file:///path/to/broadleaf-template/index.html`
   - Local server: `http://localhost:8000`

## File Structure

```
broadleaf-template/
├── index.html          # Main HTML file
├── style.css           # Main stylesheet
├── script.js           # JavaScript functionality
├── assets/             # Images and media files
│   ├── broadleaf_logo.svg+xml
│   └── hero_image.png
└── README.md           # This file
```

## Customization

### Colors
The template uses a modern color palette. Main colors can be customized in `style.css`:
- Primary Green: `#22c55e`
- Secondary Green: `#16a34a`
- Orange Accent: `#f97316`
- Dark Text: `#1e293b`
- Light Gray: `#64748b`

### Typography
The template uses the Manrope font family. To change fonts, update the Google Fonts import in `index.html` and the font-family declarations in `style.css`.

### Layout
The template is built with CSS Grid and Flexbox for easy customization:
- Header: Sticky navigation with colorful borders
- Hero: Two-column layout with shapes and form
- Features: Grid layout for feature cards
- Sections: Modular design for easy rearrangement

## Browser Compatibility

- **Modern Browsers**: Chrome 60+, Firefox 60+, Safari 12+, Edge 79+
- **Mobile**: iOS Safari 12+, Chrome Mobile 60+
- **Features Used**: CSS Grid, Flexbox, Intersection Observer API

## Performance Considerations

- **Optimized Images**: Compressed images for faster loading
- **Minimal Dependencies**: Only essential external resources
- **Efficient CSS**: Organized stylesheets with minimal redundancy
- **Debounced Scroll Events**: Optimized scroll performance

## Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## Assets Information

### Images
- **Logo**: SVG format for crisp scaling
- **Hero Image**: High-quality PNG for visual impact
- **Placeholder Images**: Used for brand logos (replace with actual logos)

### External Dependencies
- **Google Fonts**: Manrope font family
- **Font Awesome**: Icon library (CDN)
- **No other external dependencies**

## Development Notes

### Missing Assets
Some assets are referenced but not included:
- Brand logos in the "Trusted by Leading Brands" section
- Additional images for industry solutions
- Replace placeholder images with actual brand assets

### Functionality Notes
- Form submission shows alert (replace with actual form handling)
- Navigation links are placeholder (update with actual URLs)
- Tab content is static (can be made dynamic with CMS integration)

## Production Deployment

### Build for Production
1. **Optimize Images**: Compress all images for web
2. **Minify CSS/JS**: Use build tools to reduce file sizes
3. **Add Meta Tags**: Include proper SEO meta tags
4. **Test Responsiveness**: Verify on multiple devices
5. **Performance Audit**: Use tools like Lighthouse

### Hosting Options
- **Static Hosting**: Netlify, Vercel, GitHub Pages
- **Traditional Hosting**: Any web server with HTML support
- **CDN**: CloudFlare, AWS CloudFront for global distribution

## License

This template is created for educational and demonstration purposes. The design is inspired by Broadleaf Commerce's website. For commercial use, ensure you have appropriate rights and permissions.

## Support

For questions or issues with this template:
1. Check browser console for JavaScript errors
2. Verify all file paths are correct
3. Ensure images are properly loaded
4. Test on different browsers and devices

## Version History

- **v1.0**: Initial release with complete design replication
- Responsive design implementation
- Interactive JavaScript features
- Modern CSS styling and animations

