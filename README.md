# Von Scholtz Architecture

A modern, minimalist architecture portfolio website showcasing contemporary design work across residential, commercial, and restoration projects.

## Features

- **Responsive Design** - Fully optimized for mobile, tablet, and desktop devices
- **Modern Aesthetic** - Clean, minimalist architecture portfolio style
- **Image Gallery** - Beautiful project showcase with high-quality imagery
- **Contact Form** - Easy way for clients to get in touch
- **Fast Loading** - Optimized images and lightweight CSS

## Project Structure

```
├── HTML/
│   └── index.html          # Main homepage
├── css/
│   └── style.css           # Styling
├── pictures/
│   ├── IMG_0108.PNG        # Logo
│   ├── bentley.jpg         # Hero section background
│   ├── BeveryHills.jpg     # Project 1 image
│   ├── BeveryHills2.jpg.webp # Project 2 image
│   └── BeveryHills3.jpg.webp # Project 3 image
└── README.md               # This file
```

## Getting Started

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/von-scholtz-architecture.git
cd von-scholtz-architecture
```

2. Open the website locally:
   - Open `HTML/index.html` in your web browser

### Deployment to GitHub Pages

1. Ensure your repository is public
2. Go to repository Settings → Pages
3. Select `main` branch as the source
4. In the "Root" or "docs" folder selection, choose the folder containing your HTML file
5. Save and your site will be live at `https://yourusername.github.io/von-scholtz-architecture`

## Files & Navigation

- **HTML/index.html** - Main page containing all sections
- **css/style.css** - All styling and responsive design rules
- **pictures/** - Directory containing all images and logos

## Sections

1. **Navigation Bar** - Sticky navigation with mobile menu toggle
2. **Hero Section** - Full-width header with background image
3. **Projects** - Showcase of recent architectural work
4. **Our Approach** - Design philosophy and methodology
5. **Contact** - Form and contact information
6. **Footer** - Social links and copyright

## Responsive Breakpoints

- **Desktop** - Full layout with 3-column grid
- **Tablet** (≤768px) - 2-column grid with adjusted spacing
- **Mobile** (≤480px) - 1-column layout with hamburger menu

## Customization

### Update Personal Information
Edit the following in `HTML/index.html`:
- Company name in `<title>` tag
- Contact phone number
- Email address
- Studio location
- Social media links

### Modify Colors
Edit CSS variables in `css/style.css`:
```css
:root {
    --primary-color: #0a0a0a;      /* Main dark color */
    --secondary-color: #666;        /* Accent gray */
    --accent-color: #f0f0f0;        /* Light color */
    --text-color: #2a2a2a;          /* Text color */
}
```

### Add/Edit Projects
Update project cards in `HTML/index.html` section with new:
- Project images
- Project titles and locations
- Years and details
- Descriptions

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2026 Scholtz Architecture. All rights reserved.

## Contact

For inquiries or support, please visit the contact section on the website or email hello@scholtzarchitecture.com
