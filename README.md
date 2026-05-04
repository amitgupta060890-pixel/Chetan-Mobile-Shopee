# Chetan Mobile Shopee - Display & Mobile Repair Website

A professional, modern website for a mobile and display repair business built with HTML, CSS, and JavaScript.

## 📋 Features

### ✨ Sections Included:

1. **Navigation Bar**
   - Sticky navigation with smooth scrolling
   - Mobile-responsive hamburger menu
   - Active link highlighting
   - Logo and branding

2. **Hero Section**
   - Eye-catching hero image with overlay
   - Clear value proposition
   - Call-to-action button
   - Responsive typography

3. **Services Section**
   - 6 service cards with icons
   - Hover animations
   - Service descriptions:
     - Screen Repair
     - Battery Replacement
     - Hardware Repair
     - Water Damage Repair
     - Camera Repair
     - Software Support

4. **Pricing Section**
   - Transparent pricing for all services
   - Multiple service categories
   - Price ranges for different devices
   - Warranty information

5. **Gallery Section**
   - Before and after repair showcase
   - Responsive image grid
   - Hover overlay effect
   - Smooth animations

6. **About Section**
   - Company information
   - Statistics (8+ years, 5000+ repairs, 100% satisfaction)
   - Why choose us list
   - Professional branding

7. **Contact Section**
   - Contact information display
   - Phone and email links
   - Working hours
   - Contact form with validation
   - Multiple service options
   - Success notification on submission

8. **Footer**
   - Social media links
   - Quick navigation links
   - Company description
   - Copyright information

### 🎨 Design Features:

- **Modern Dark Theme** - Professional red and black color scheme
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Smooth Animations** - Fade-in effects and hover transitions
- **Glass Morphism** - Modern backdrop blur effects
- **Gradient Elements** - Eye-catching red gradients throughout
- **Font Awesome Icons** - Professional icon set included

## 📁 File Structure

```
Chetan-Mobile-Shopee/
├── index.html          # Main HTML file with all sections
├── styles.css          # Complete CSS styling
├── script.js           # Interactive JavaScript functionality
├── README.md           # This file
└── chetan_mobile_shopee.html  # Legacy version (can be deleted)
```

## 🚀 How to Use

1. **Clone or Download** the repository
2. **Open `index.html`** in your web browser
3. **Customize** the contact information, pricing, and content
4. **Deploy** to your hosting provider

## 🔧 Customization Guide

### Update Business Information:

**In `index.html`:**
- Line 115: Update phone number
- Line 119: Update email address
- Line 126: Update business address
- Line 134: Update working hours

### Change Colors:

**In `styles.css` (lines 8-14):**
```css
:root {
    --primary-color: #e8262a;      /* Main red color */
    --secondary-color: #ff4444;    /* Light red */
    --dark-bg: #0a0a0a;            /* Dark background */
    --light-bg: #1a1a1a;           /* Light background */
    --text-light: #e0e0e0;         /* Light text */
    --text-white: #ffffff;         /* White text */
    --accent-gold: #ffd700;        /* Accent color */
}
```

### Update Pricing:

**In `index.html` (lines 165-200):**
Edit the pricing tables for each service

### Add Real Gallery Images:

**In `index.html` (lines 295-315):**
Replace placeholder URLs with real image URLs

### Update Services:

**In `index.html` (lines 90-110):**
Modify service descriptions and add/remove services

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🔧 JavaScript Features

- **Mobile Navigation Toggle** - Hamburger menu for mobile
- **Smooth Scrolling** - Anchor link navigation
- **Form Validation** - Client-side form validation
- **Scroll Animations** - Elements animate in on scroll
- **Counter Animation** - Statistics numbers animate
- **Success Notifications** - Form submission feedback
- **Active Nav Links** - Highlights current section

## 🎯 Contact Form Integration

The contact form currently:
- Validates all inputs
- Shows a success message
- Logs data to browser console

**To integrate with a backend:**
1. Create a backend endpoint
2. Update the form submission in `script.js` (around line 30)
3. Send form data to your backend
4. Process and store contact requests

## 📊 Performance

- Optimized for fast loading
- Lazy loading ready for images
- Smooth 60fps animations
- Mobile-first responsive design

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📝 Content Updates Checklist

- [ ] Update phone number
- [ ] Update email address
- [ ] Update business address
- [ ] Update working hours
- [ ] Add real gallery images
- [ ] Update pricing information
- [ ] Update company statistics
- [ ] Add social media links
- [ ] Customize brand colors (if needed)
- [ ] Add real testimonials

## 🔒 Security Notes

- The contact form currently doesn't send data (shows success locally only)
- Implement backend validation for production
- Use HTTPS for form submissions
- Never expose sensitive information in frontend code

## 📧 Support & Customization

For any modifications or questions:
1. Check the inline comments in the code
2. Review the CSS variables in `styles.css`
3. Update JavaScript event handlers in `script.js`

## 📄 License

This website template is free to use and modify for Chetan Mobile Shopee.

## 🎉 Features Coming Soon

- Customer testimonials slider
- Service booking system
- Google Maps integration
- Chat widget integration
- Blog section
- Newsletter subscription
- Payment gateway integration
- Appointment scheduling system

---

**Last Updated**: 2026-05-04
**Version**: 2.0 - Complete Website
