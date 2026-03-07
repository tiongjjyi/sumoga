# Sumoga Organic Website

A beautiful, responsive website for Sumoga Organic, a premium organic vegetable retailer in Malaysia.

## Features

### 🏠 Homepage

- **Hero Section**: Eye-catching introduction with call-to-action
- **Company Introduction**: Overview of Sumoga Organic with farm photos
- **Organic Produce Showcase**: Grid display of fresh vegetables with descriptions
- **Customer Reviews**: Rotating testimonials with ratings and customer photos

### 📍 Navigation

- **Responsive Navigation Bar**: Mobile-friendly hamburger menu
- **Smooth Scrolling**: Seamless navigation between sections
- **Active Link Highlighting**: Visual feedback for current page

### 🏢 About Us Page

- **Company History**: Founded in 2010 with rich heritage
- **Farming Philosophy**: Sustainable agriculture practices
- **Quality Assurance**: Rigorous testing and standards
- **Photo Gallery**: Beautiful farm and team photos

### 🗺️ Where to Find Us Page

- **Interactive Map**: Google Maps integration showing store locations
- **Store Categories**: Organized by retailer (Aeon, Jaya Grocer, Mercato, Giant, Publika)
- **Location Coverage**: Kuala Lumpur, Melacca, and Johor Bahru areas
- **Visual Legend**: Color-coded store categories on map

## Technical Features

### 🎨 Design

- **Modern UI/UX**: Clean, professional design with organic color scheme
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: CSS transitions and JavaScript animations
- **Professional Typography**: Poppins font family for readability

### 📱 Mobile Optimization

- **Hamburger Menu**: Collapsible navigation for mobile devices
- **Touch-Friendly**: Optimized button sizes and spacing
- **Responsive Grid**: Adaptive layouts for all screen sizes
- **Fast Loading**: Optimized images and efficient code

### ⚡ Performance

- **Lightweight**: Minimal dependencies, fast loading times
- **SEO Ready**: Semantic HTML structure
- **Accessibility**: Proper ARIA labels and keyboard navigation
- **Cross-Browser**: Compatible with all modern browsers

## Setup Instructions

### 1. File Structure

```
sumoga/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

### 2. Google Maps API Setup

To enable the interactive map functionality:

1. **Get Google Maps API Key**:

   - Go to [Google Cloud Console](https://console.cloud.google.com/)
   - Create a new project or select existing one
   - Enable the "Maps JavaScript API"
   - Create credentials (API Key)
   - Restrict the API key to your domain for security

2. **Update the API Key**:
   - Open `index.html`
   - Find the line: `<script async defer src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap"></script>`
   - Replace `YOUR_API_KEY` with your actual Google Maps API key

### 3. Running the Website

Simply open `index.html` in any modern web browser. For development, you can use:

```bash
# Using Python (if installed)
python -m http.server 8000

# Using Node.js (if installed)
npx http-server

# Or simply double-click index.html
```

### 4. Customization

#### Colors

The website uses a green color scheme representing organic/natural themes:

- Primary Green: `#2d5016`
- Light Green: `#96CEB4`
- Background: `#f8f9fa`

#### Content Updates

- **Images**: Replace placeholder images with actual farm and product photos
- **Text**: Update company information, descriptions, and contact details
- **Store Locations**: Modify coordinates and store information in `script.js`

#### Adding New Features

- **Contact Form**: Add form validation and submission handling
- **Newsletter**: Implement email subscription functionality
- **E-commerce**: Add shopping cart and product ordering
- **Blog**: Create content management system for news and updates

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

1. **Optimize Images**: Compress images before uploading
2. **CDN**: Use a Content Delivery Network for faster loading
3. **Caching**: Implement browser caching for static assets
4. **Minification**: Minify CSS and JavaScript for production

## Security Considerations

1. **API Key Security**: Restrict Google Maps API key to your domain
2. **HTTPS**: Use SSL certificate for production deployment
3. **Input Validation**: Add server-side validation for any forms
4. **Content Security Policy**: Implement CSP headers

## Future Enhancements

- **Multi-language Support**: Add Bahasa Malaysia and Chinese translations
- **Online Ordering**: E-commerce integration
- **Customer Portal**: Account management and order history
- **Mobile App**: Native mobile application
- **Analytics**: Google Analytics integration
- **SEO Optimization**: Meta tags and structured data

## Support

For technical support or customization requests, contact the development team.

---

**Sumoga Organic** - Fresh organic vegetables for a healthier Malaysia 🌱
