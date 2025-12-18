# Images Folder

Place your website images in this folder.

## Recommended Images

### Logo
- **Filename**: `logo.png` or `logo.svg`
- **Size**: 200x60px (or similar aspect ratio)
- **Use**: Navigation bar logo

### Hero Background
- **Filename**: `hero-bg.jpg`
- **Size**: 1920x600px minimum
- **Use**: Homepage hero section background
- **Theme**: Outdoor/hunting scene, forest, or related imagery

### Service Images
- **Taxidermy**:
  - `taxidermy-1.jpg` - Shoulder mount example
  - `taxidermy-2.jpg` - Full body mount
  - `taxidermy-3.jpg` - European mount
  
- **Processing**:
  - `processing-1.jpg` - Processing facility
  - `processing-2.jpg` - Meat cuts/products
  - `processing-3.jpg` - Vacuum sealed packages

### About Page
- `facility.jpg` - Your business location/building
- `team.jpg` - Staff photo (optional)
- `workshop.jpg` - Work area/facility interior

### General
- `about-hero.jpg` - About page header image
- `services-hero.jpg` - Services page header image
- `contact-hero.jpg` - Contact page header image

## Image Guidelines

- **Format**: JPG for photos, PNG for logos with transparency
- **Optimization**: Compress images to keep file sizes under 500KB
- **Resolution**: Use high-quality images (at least 1200px wide for full-width images)
- **Aspect Ratios**: 
  - Hero images: 16:9 or 21:9
  - Service cards: 4:3 or 1:1
  - Logo: Keep original proportions

## Tools for Image Optimization

- [TinyPNG](https://tinypng.com/) - Compress PNG and JPG
- [Squoosh](https://squoosh.app/) - Google's image compressor
- [CompressJPEG](https://compressjpeg.com/) - Batch compress

## Adding Images to Your Website

Once you have images in this folder, update the HTML:

**Example - Adding logo to navigation:**
```html
<!-- In all HTML files, update the logo section -->
<a href="index.html" class="logo">
    <img src="images/logo.png" alt="Field To Freezer Logo" style="height: 40px;">
</a>
```

**Example - Adding hero background:**
```css
/* In css/style.css, update the .hero class */
.hero {
    background-image: url('../images/hero-bg.jpg');
    background-size: cover;
    background-position: center;
}
```

**Example - Adding service images:**
```html
<!-- Replace image placeholders in HTML -->
<div class="image-placeholder">
    <img src="images/taxidermy-1.jpg" alt="Taxidermy example">
</div>
```

## Stock Photo Resources (if needed)

Free stock photos:
- [Unsplash](https://unsplash.com/) - Search "hunting", "deer", "forest"
- [Pexels](https://pexels.com/) - High-quality free images
- [Pixabay](https://pixabay.com/) - Free images and videos

**Note**: Make sure you have rights to use any images on your website. Using your own photos is always best!