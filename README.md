# AWS Chicago User Group Website

This is the official website for the AWS Chicago User Group - a user-run, user-focused community for AWS users in the Chicago area.

## Recent Improvements

### Security Enhancements
- Added security headers via `.htaccess` file
- Implemented Content Security Policy (CSP)
- Added `rel="noopener noreferrer"` to all external links
- Enabled XSS protection and clickjacking prevention

### Accessibility Improvements
- Added skip navigation links for screen readers
- Implemented proper semantic HTML structure with `<main>`, `<nav>`, and ARIA labels
- Enhanced all images with descriptive alt attributes
- Added proper form labels and validation
- Improved keyboard navigation support
- Added `lang="en"` attribute to HTML elements

### Performance & SEO
- Optimized images with responsive sizing and aspect ratios
- Added proper meta descriptions and keywords
- Implemented browser caching for static assets
- Added compression for text-based files
- Improved font loading with `font-display: swap`

### Code Quality
- Fixed broken banner background image path
- Standardized image paths to use `assets/images/`
- Removed duplicate images folder
- Fixed broken internal links
- Improved HTML validation compliance
- Added proper form validation and error handling

### Mobile Responsiveness
- Enhanced responsive image handling with `object-fit` and `aspect-ratio`
- Improved mobile navigation experience
- Better touch target sizing for mobile devices

## File Structure

```
├── assets/
│   ├── css/
│   │   ├── main.css      # Main stylesheet with responsive design
│   │   └── main.scss     # SCSS source file
│   ├── images/           # All website images
│   └── js/               # JavaScript files
├── *.html                # Website pages
├── .htaccess            # Security headers and caching rules
└── README.md            # This file
```

## Key Pages

- `index.html` - Homepage with group information and upcoming events
- `faqs.html` - Frequently asked questions for sponsors, speakers, and attendees
- `contact.html` - Contact form and social media links
- `codeofconduct.html` - Community guidelines and policies

## Development Notes

### Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive design
- Graceful degradation for older browsers

### External Dependencies
- Google Fonts (Roboto)
- Formspree for contact form handling
- jQuery and custom JavaScript for interactions

### Deployment
1. Upload all files to web server
2. Ensure `.htaccess` file is properly configured
3. Test all external links and form functionality
4. Verify SSL certificate is installed for HTTPS

## Contributing

When making changes:
1. Test on multiple devices and browsers
2. Validate HTML and CSS
3. Check accessibility with screen readers
4. Optimize any new images
5. Update this README if needed

## Contact

For website issues or suggestions, contact the AWS Chicago organizers through the contact form or reach out via our community channels.