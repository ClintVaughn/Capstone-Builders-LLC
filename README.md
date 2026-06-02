# Capstone Builders - Landing Page

A professional, responsive landing page for Capstone Builders construction services.

## Color Scheme
Designed to match your brand identity:
- **Primary Blue:** #0052CC
- **Secondary Gray:** #333333
- **Clean White:** #FFFFFF

## Setup Instructions

### 1. Enable GitHub Pages
- Go to your repository settings at: https://github.com/ClintVaughn/Capstone-Builders-LLC/settings
- Scroll down to "GitHub Pages" section
- Under "Source", select "Deploy from a branch"
- Select "main" branch
- Your site will be available at: `https://ClintVaughn.github.io/Capstone-Builders-LLC/`

## How to Customize

### Update Contact Information
Open `index.html` and find the Contact section:
- Replace `Add your email here` with your actual email
- Replace `https://facebook.com/your-page` with your Facebook page URL

### Add Your Services
In `index.html`, update the Services section:
- Replace "Service 1", "Service 2", etc. with your actual service names
- Add descriptions for each service

### Add Main Features
Update the "Why Choose Us" section:
- Replace "Feature 1", "Feature 2", "Feature 3" with your main business features

### Add Images
1. Find image URLs online or upload them to a free service like:
   - Unsplash (unsplash.com)
   - Pexels (pexels.com)
   - Pixabay (pixabay.com)

2. In `index.html`, uncomment and replace the image URLs:
   - Hero image: Look for `<!-- <img src="YOUR_HERO_IMAGE_URL"...`
   - Service images: Look for `<!-- <img src="SERVICE_*_IMAGE_URL"...`

Example:
```html
<img src="https://images.unsplash.com/photo-construction-123" alt="Construction Work">
```

### Customize Colors
Edit `styles.css` and update the color variables at the top:
```css
:root {
    --primary-color: #0052CC;  /* Primary blue color */
    --secondary-color: #333333; /* Gray color */
}
```

## File Structure
- `index.html` - Main landing page
- `styles.css` - Styling and responsive design
- `README.md` - This file

## Features
✅ Professional design matching your brand
✅ Fully responsive (works on mobile, tablet, desktop)
✅ Smooth animations and hover effects
✅ Easy to customize
✅ SEO-friendly structure
✅ Fast loading

## Need Help?
If you need to make changes:
1. Edit the files in your repository
2. Commit and push the changes
3. Your live site will update automatically within a minute

Good luck with Capstone Builders! 🏗️