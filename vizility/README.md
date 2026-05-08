# Vizilti Salon - Premium Luxury Beauty Website

A modern, responsive, and premium salon website built with HTML5, CSS3, and vanilla JavaScript. This website showcases Vizilti Salon's luxury beauty services in Bangalore.

## 🌟 Features

### Design & UX
- **Luxury Design**: Black, white, beige, and gold color palette
- **Modern Typography**: Playfair Display (serif) and Poppins (sans-serif) fonts
- **Smooth Animations**: Hover effects, parallax scrolling, and micro-interactions
- **Mobile-First**: Fully responsive design for all devices
- **Premium Aesthetic**: High-end salon industry standards

### Pages
1. **Home** (`index.html`) - Landing page with hero section, services overview, reviews, gallery, and contact
2. **Services** (`services.html`) - Detailed service descriptions with pricing tiers
3. **About** (`about.html`) - Salon story, team, mission, and achievements
4. **Contact** (`contact.html`) - Contact form, map integration, and location information

### Interactive Features
- **Sticky Navigation**: Transparent navbar with scroll effects
- **WhatsApp Integration**: Direct booking via WhatsApp
- **Gallery Lightbox**: Interactive image viewing
- **FAQ Accordion**: Expandable Q&A sections
- **Contact Form**: Form validation and WhatsApp submission
- **Testimonial Slider**: Auto-rotating customer reviews
- **Smooth Scrolling**: Seamless navigation between sections

### Services Included
- Haircut & Styling
- Hair Coloring
- Facial Treatments
- Hair Spa
- Bridal Makeup
- Manicure & Pedicure

## 📁 Project Structure

```
vizility/
├── index.html                 # Home page
├── services.html              # Services page
├── about.html                 # About page
├── contact.html               # Contact page
├── css/
│   └── style.css             # Main stylesheet
├── js/
│   └── script.js             # JavaScript functionality
├── images/
│   ├── logo.png             # Salon logo
│   ├── hero-bg.jpg         # Hero background
│   ├── page-header-bg.jpg   # Page headers
│   ├── gallery/            # Gallery images
│   ├── services/           # Service images
│   ├── team/              # Team member photos
│   ├── experts/            # Expert photos
│   ├── about/             # About page images
│   └── testimonials/       # Client testimonials
└── README.md               # This file
```

## 🎨 Design System

### Colors
- **Primary Black**: `#000000`
- **Primary White**: `#FFFFFF`
- **Primary Beige**: `#F5E6D3`
- **Primary Gold**: `#D4AF37`
- **Text Dark**: `#222222`
- **Text Light**: `#666666`

### Typography
- **Headings**: Playfair Display (serif)
- **Body Text**: Poppins (sans-serif)
- **Font Weights**: 300, 400, 500, 600, 700

### Components
- **Buttons**: Rounded corners with hover effects
- **Cards**: Elevated with shadow effects
- **Icons**: Font Awesome 6.4.0
- **Forms**: Modern input styling with validation

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Installation
1. Clone or download the project files
2. Ensure all image assets are in the correct directories
3. Open `index.html` in a web browser

### Development
For local development with live reload:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if installed)
npx serve .

# Using PHP (if installed)
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 📱 Responsive Breakpoints

- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px
- **Mobile**: < 768px
- **Small Mobile**: < 480px

## 🔧 Customization

### Colors
Edit CSS variables in `css/style.css`:
```css
:root {
    --primary-black: #000000;
    --primary-white: #FFFFFF;
    --primary-beige: #F5E6D3;
    --primary-gold: #D4AF37;
}
```

### Contact Information
Update contact details in:
- `index.html` (footer and contact section)
- `contact.html` (contact cards)
- `about.html` (footer)
- WhatsApp links throughout

### Services
Modify services in:
- `index.html` (service cards)
- `services.html` (detailed service pages)

## 📞 WhatsApp Integration

The website includes WhatsApp integration for:
- Direct booking buttons
- Contact form submissions
- Floating WhatsApp button

**Update WhatsApp number**: Replace `919876543210` with your actual WhatsApp number in all HTML files.

## 🗺️ Google Maps

The contact page includes Google Maps integration. To use your actual location:
1. Get your Google Maps embed code
2. Replace the iframe src in `contact.html`
3. Update map link in contact cards

## 🖼️ Images

### Required Images
- `images/logo.png` - Salon logo (40x40px)
- `images/hero-bg.jpg` - Hero background (1920x1080px)
- `images/page-header-bg.jpg` - Page headers (1920x600px)
- `images/gallery/` - 6 gallery images (400x300px)
- `images/services/` - 6 service images (400x300px)
- `images/team/` - Team member photos (300x300px)
- `images/experts/` - Expert photos (300x300px)
- `images/about/` - About page images (800x600px)
- `images/testimonials/` - Client photos (60x60px)

### Image Optimization
- Use WebP format for better compression
- Implement lazy loading for performance
- Add alt text for accessibility

## 🎯 Performance Features

### Built-in Optimizations
- Lazy loading for images
- Debounced scroll events
- Optimized animations with CSS transforms
- Efficient DOM manipulation

### Recommended Improvements
- Image compression and WebP conversion
- CSS and JS minification
- Implement service worker for offline support
- Add structured data for SEO

## 🔍 SEO Features

### Meta Tags
- Title tags for all pages
- Meta descriptions
- Open Graph tags (add as needed)
- Semantic HTML5 structure

### Accessibility
- ARIA labels where needed
- Keyboard navigation support
- Screen reader friendly
- High contrast color scheme

## 🌐 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

For questions or support regarding this website template:
- Email: info@viziltisalon.com
- Phone: +91 98765 43210
- WhatsApp: +91 98765 43210

---

**Vizilti Salon** - Where Beauty Meets Excellence
*123 Brigade Road, Indiranagar, Bangalore - 560038*
