# Image Placeholders Reference

This document lists all image placeholders used in the website. Replace these with actual images by placing them in the `images/` folder.

## Required Images

### Hero Section
1. **images/hero-background.jpg**
   - Description: Background image for the hero section (NFL stadium or field)
   - Recommended size: 1920x1080px or larger
   - Usage: Hero section background with overlay

2. **images/chiefs-logo.png**
   - Description: Kansas City Chiefs official logo
   - Recommended size: 400x400px (square, transparent background preferred)
   - Usage: Hero section team card

3. **images/colts-logo.png**
   - Description: Indianapolis Colts official logo
   - Recommended size: 400x400px (square, transparent background preferred)
   - Usage: Hero section team card

4. **images/arrowhead-stadium.jpg**
   - Description: Arrowhead Stadium exterior or interior photo
   - Recommended size: 800x400px
   - Usage: Chiefs team card in hero section

5. **images/lucas-oil-stadium.jpg**
   - Description: Lucas Oil Stadium exterior or interior photo
   - Recommended size: 800x400px
   - Usage: Colts team card in hero section

### Head-to-Head Section
6. **images/chiefs-colts-action.jpg**
   - Description: Action shot from a Chiefs vs Colts game (any historical matchup)
   - Recommended size: 1200x600px
   - Usage: Head-to-head record section banner

## Image Guidelines

- **Format**: JPG for photos, PNG for logos (with transparency)
- **Optimization**: Compress images for web (aim for <500KB per image)
- **Aspect Ratios**: Maintain the recommended aspect ratios for best display
- **Quality**: Use high-quality images (at least 72 DPI for web)

## Folder Structure

Create an `images/` folder in the same directory as `index.html`:

```
compare-chiefs-and-colts/
├── index.html
└── images/
    ├── hero-background.jpg
    ├── chiefs-logo.png
    ├── colts-logo.png
    ├── arrowhead-stadium.jpg
    ├── lucas-oil-stadium.jpg
    └── chiefs-colts-action.jpg
```

## Fallback Behavior

If images are not found, the page will display placeholder icons and text indicating which image should be replaced. The page is fully functional even without images.

