# D.A. Marvel Enterprise Website

A professional, multi-page static website for D.A. Marvel Enterprise - manufacturer of high-quality galvanized false ceiling components and metal framing solutions.

## 📁 Website Structure

```
damarvel-website/
├── index.html              # Homepage
├── about.html              # About Us page
├── products.html           # Products page (Gypsum boards, ceiling tiles, accessories)
├── metal-framing.html      # Metal Framing systems page
├── pvc-panels.html         # PVC Panels page
├── contact.html            # Contact page
├── css/
│   └── style.css          # Main stylesheet
├── js/
│   └── script.js          # Interactive JavaScript
└── images/                # (Empty - ready for your images)
```

## 🌟 Features

### Homepage (index.html)
- Hero section with compelling tagline
- Key features showcase
- Product categories overview
- Call-to-action sections

### About Us (about.html)
- Company story and philosophy
- Mission and Vision statements
- Core values
- Professional layout

### Products (products.html)
- Gypsum boards (Standard, Moisture Resistant, Fire Resistant)
- Ceiling tiles and grid systems
- Accessories (Hangers, Compounds, Screws)
- Detailed specifications for each product

### Metal Framing (metal-framing.html)
- MARVEL X Series (0.70mm, 0.40mm variants)
- SIGNATURE ALPHA Series (0.50mm, 0.40mm variants)
- SIGMA Series (0.60mm, 0.35mm, 0.40mm variants)
- Complete specifications for each component
- Quality assurance information

### PVC Panels (pvc-panels.html)
- 6 different panel types
- Features and benefits
- Color options
- Applications section

### Contact (contact.html)
- Contact form with validation
- Contact information
- Business hours
- FAQ section
- Map placeholder

## 🎨 Design Features

### Color Scheme
- Primary Color: #1a4d7a (Professional Blue)
- Secondary Color: #2c7ab5 (Light Blue)
- Accent Color: #f39c12 (Orange/Gold)
- Modern gradient backgrounds

### Typography
- Font Family: Poppins (Google Fonts)
- Clean, professional, and readable

### Responsive Design
- Mobile-first approach
- Breakpoints at 968px, 768px, 480px
- Hamburger menu for mobile navigation

### Interactive Elements
- Smooth scrolling
- Hover effects on cards and buttons
- Form validation
- Mobile navigation toggle
- Scroll animations
- Parallax effects

## 🚀 How to Use

1. **Customize Content:**
   - Update contact information in all pages
   - Add your actual phone numbers and email addresses
   - Update the map section with actual location

2. **Add Images:**
   - Place product images in the `images/` folder
   - Update image paths in HTML files
   - Recommended image formats: JPG, PNG, WebP

3. **Customize Colors:**
   - Edit CSS variables in `style.css` (lines 15-30)
   - Change primary, secondary, and accent colors

4. **Deploy:**
   - Upload all files to your web hosting
   - Ensure folder structure is maintained
   - Test on mobile and desktop browsers

## 📱 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Customization Tips

### Changing Colors
Edit the CSS variables at the top of `style.css`:
```css
:root {
    --primary-color: #1a4d7a;    /* Your primary color */
    --accent-color: #f39c12;      /* Your accent color */
}
```

### Adding New Pages
1. Copy structure from existing page
2. Update navigation links in all pages
3. Add corresponding styles if needed

### Updating Contact Form
Currently shows alert on submission. To connect to email:
- Use a backend service (PHP, Node.js)
- Or use services like Formspree, EmailJS
- Update form action in `contact.html`

## 📝 Content Notes

- All product specifications based on provided content
- Phone numbers marked as "XXX XXX XXXX" - replace with actual numbers
- Email addresses are placeholders - update with real emails
- Map section is a placeholder - integrate Google Maps if needed

## 🎯 SEO Ready

- Semantic HTML5 structure
- Meta tags ready for customization
- Clean URL structure
- Fast loading times
- Mobile responsive

## 💡 Future Enhancements

- Add product image gallery
- Implement live chat
- Add customer testimonials
- Create product catalog download
- Add language switcher for regional markets

## 📞 Support

For customization help or questions:
- Review the code comments
- Check browser console for JavaScript errors
- Validate HTML at validator.w3.org

---

**Built with modern web standards and best practices for D.A. Marvel Enterprise**

*"A roof over your head on our shoulders"*
