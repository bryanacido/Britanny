# Holiday Survival Series Landing Page

A modern, conversion-optimized landing page for Brittany Watkins' Holiday Survival Series - a 6-week live tapping program designed to help people avoid holiday weight gain and emotional eating.

## 🎯 Project Overview

This landing page promotes a holiday-focused emotional eating program with two pricing tiers:
- **Option 1**: Holiday Survival Series Pass ($597 one-time)
- **Option 2**: Holiday Survival Series Inside The Tapping Circle ($199/month for 3 months)

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **JavaScript** - Tailwind configuration
- **Google Fonts** - Inter (sans-serif) and Libre Baskerville (serif)

## 📁 File Structure

```
Praject/
├── index.html          # Main landing page
├── styles.css          # Custom CSS overrides
├── images/             # Image assets folder
│   ├── hero_holiday.jpg
│   ├── logo1.png
│   ├── placeholder.jpg
│   ├── britanny_leaking_cake_in_ref.jpg
│   ├── britanny_eating_cake.jpg
│   ├── britanny1.jpg
│   └── product_image.jpg
└── README.md           # Project documentation
```

## 🎨 Design Features

### Color Palette
- **Warm Cream**: #FAF7F2
- **Soft Beige**: #F6F2EA
- **Muted Red**: #C63C2C
- **Bright Red**: #E83D3D
- **Gold**: #D4AF37
- **Warm Gray**: #596774
- **Deep Blue**: #2E516F

### Key Sections
1. **Hero Section** - Purple-to-red gradient overlay with headline and logo
2. **Video Placeholder** - VSL preview with Join Now CTA
3. **Story Section** - "You know how it goes..." emotional connection
4. **Series Details** - What participants will learn
5. **Product Visual** - Course mockup image
6. **Pricing Options** - Two-tier pricing with "Best Value" badge
7. **Testimonials** - Client success stories
8. **What Makes This Different** - Unique value proposition
9. **Outcomes Section** - Results participants can expect
10. **Final CTA** - Bottom conversion section

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic text editor or IDE
- Local web server (optional, for testing)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/bryanacido/Britanny.git
cd Britanny
```

2. Open `index.html` in your browser, or use a local server:

**Using Python:**
```bash
python -m http.server 8000
```

**Using PowerShell:**
```powershell
python -m http.server 8000
```

3. Navigate to `http://localhost:8000` in your browser

## 📝 Customization Guide

### Updating Images
All images are stored in the `images/` folder. To replace an image:
1. Add your new image to the `images/` folder
2. Update the corresponding `src` attribute in `index.html`

### Changing Colors
Colors are defined in the Tailwind config within `index.html`:
```javascript
tailwind.config = {
  theme: {
    extend: {
      colors: {
        'warm-cream': '#FAF7F2',
        // ... other colors
      }
    }
  }
}
```

### Updating Text Content
All text content is directly in `index.html`. Search for the section you want to modify and update accordingly.

### Modifying Pricing
Pricing details are in the "Pricing Section" around line 145-255 in `index.html`.

## ✨ Special Features

- **Responsive Design** - Mobile-first approach with breakpoints
- **Image Optimization** - Lazy loading and CSS filters for enhanced visuals
- **Hover Effects** - Interactive buttons and cards
- **Text Shadows** - Enhanced readability on hero background
- **Gold Border Highlight** - "Best Value" pricing option emphasis
- **Gradient Overlays** - Purple-to-red hero gradient for brand alignment

## 🌐 Deployment

### GitHub Pages
1. Push your code to GitHub
2. Go to repository Settings > Pages
3. Select branch (main) and root folder
4. Save and wait for deployment

### Other Hosting Options
- Netlify (drag and drop)
- Vercel
- AWS S3 + CloudFront
- Any static hosting service

## 📱 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Development Notes

- Tailwind CSS is loaded via CDN for simplicity
- Images use `brightness`, `contrast`, and `saturate` filters for visual enhancement
- Hero text uses text-shadow for improved readability
- All images implement lazy loading for performance

## 📄 License

This project is proprietary and belongs to Brittany Watkins.

## 👤 Author

**Brittany Watkins**
- Website: [Holiday Survival Series](https://github.com/bryanacido/Britanny)
- Program Start Date: November 24th

## 📞 Support

For questions or support regarding the Holiday Survival Series program, please contact through the landing page contact form.

---

*Last Updated: November 2025*
