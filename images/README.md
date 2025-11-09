# Bubble Brush Car Wash Images

## Image Guidelines

To enhance your website, add professional photos to this `images` folder. Here are the recommended images:

### Hero Section
- **hero-bg.jpg** - High-quality image of a clean, shiny car (1920x1080px minimum)
- Consider showing water droplets, soap bubbles, or a sparkling clean vehicle

### Gallery Section
Replace the placeholder boxes with actual photos:
- **gallery-1.jpg** - Before/after comparison
- **gallery-2.jpg** - Interior detailing work
- **gallery-3.jpg** - Paint polishing results
- **gallery-4.jpg** - Glass treatment
- **gallery-5.jpg** - Ceramic coating application
- **gallery-6.jpg** - Full detail showcase

### Service Icons (Optional)
If you want custom icons instead of emojis:
- **service-wash.svg**
- **service-detail.svg**
- **service-protection.svg**
- etc.

### Tips for Great Car Wash Photos:
1. **Good lighting** - Shoot on a bright, cloudy day for even lighting
2. **Show the process** - Action shots of cleaning, washing, detailing
3. **Before & After** - Dramatic transformations sell the service
4. **Detail shots** - Close-ups of clean wheels, shiny paint, spotless interiors
5. **Professional quality** - High resolution (at least 1200px wide)
6. **Consistent style** - Similar angles and lighting across images

### Free Stock Photo Resources:
- Unsplash.com
- Pexels.com
- Pixabay.com

Search for terms like:
- "car wash"
- "car detailing"
- "clean car"
- "shiny car"
- "car interior cleaning"

## How to Add Images to Your Website

Once you've added images to this folder, update the HTML:

1. **For the hero background**, add this to your CSS (styles.css):
```css
.hero {
    background-image: linear-gradient(rgba(8, 145, 178, 0.8), rgba(59, 130, 246, 0.8)), url('images/hero-bg.jpg');
    background-size: cover;
    background-position: center;
}
```

2. **For gallery items**, replace the `.gallery-placeholder` divs in index.html with:
```html
<img src="images/gallery-1.jpg" alt="Car wash before and after">
```

3. **For service cards**, you can add images above the icons if desired.

Good luck with your Bubble Brush Car Wash website! 🚗✨💧
