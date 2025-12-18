# Field To Freezer - Corporate Website

Professional corporate website for Field To Freezer, a company specializing in taxidermy services and game processing.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern Layout**: Clean, professional design with dark forest green and camo color scheme
- **Multiple Pages**:
  - Home page with hero section and services overview
  - About page with company story and values
  - Services page with detailed taxidermy and processing information
  - Contact page with form and business information
- **Interactive Elements**: 
  - Mobile-friendly navigation menu
  - Smooth scrolling
  - Animated elements on scroll
  - Contact form with validation
- **GitHub Pages Ready**: Static HTML/CSS/JS files ready for immediate deployment

## Color Scheme

The website uses a professional dark forest green and camo-inspired color palette:
- **Primary**: Dark Forest Green (#1a3a1a)
- **Accents**: Tan/Khaki, Brown, Olive, Moss Green
- **Highlights**: Light Brown/Gold (#d4a574)

## File Structure

```
Feild To Freezer Website/
├── index.html          # Homepage
├── about.html          # About page
├── services.html       # Services page
├── contact.html        # Contact page
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── script.js       # Interactive JavaScript
└── README.md           # This file
```

## Deployment to GitHub Pages

### Option 1: Using GitHub Web Interface

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to repository Settings → Pages
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Click Save
7. Your site will be published at `https://yourusername.github.io/repository-name/`

### Option 2: Using Git Command Line

```bash
# Navigate to the website directory
cd "D:\Sential_Root\Divisions\Sential_Innovations\Buisness_Other\Feild To Freezer Website"

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit - Field To Freezer website"

# Add your GitHub repository as remote
git remote add origin https://github.com/yourusername/your-repo-name.git

# Push to GitHub
git branch -M main
git push -u origin main

# Enable GitHub Pages in repository settings as described in Option 1
```

## Customization

### Updating Contact Information

Edit the contact.html file and update:
- Phone number: Line 86
- Email address: Line 93
- Physical address: Lines 100-101
- Business hours: Lines 108-110

### Adding Real Images

Replace the image placeholders in the HTML with actual images:
1. Create an `images` folder in the root directory
2. Add your images to the folder
3. Update the HTML to reference your images:
   ```html
   <img src="images/your-image.jpg" alt="Description">
   ```

### Modifying Colors

Edit `css/style.css` and update the CSS variables at the top:
```css
:root {
    --color-primary: #1a3a1a;
    --color-accent: #d4a574;
    /* etc. */
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- Vanilla JavaScript (ES6+)
- No external dependencies or frameworks

## Notes

- The contact form currently uses client-side validation only
- For production use, implement server-side form handling
- Add actual business information before deployment
- Consider adding a logo and real images for a polished look
- This is a static site - no backend required for GitHub Pages

## License

This website template is created for Field To Freezer. Customize as needed for your business.

## Support

For questions or modifications, refer to the HTML, CSS, and JavaScript files which are fully commented and organized.

---

**Field To Freezer** - Professional Taxidermy & Game Processing Services