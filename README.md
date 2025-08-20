# Ziad Ahmed - AI Engineer Portfolio

A professional portfolio website showcasing AI engineering skills, experience, and services.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **CV Download**: Downloadable CV functionality
- **Contact Form**: Working contact form with validation
- **Professional Sections**: About, Education, Skills, Experience, Services, Projects, Contact

## Sections

1. **Hero Section**: Professional introduction with photo and call-to-action buttons
2. **About**: Personal statement and statistics
3. **Education**: Academic background
4. **Skills**: Technical and soft skills with icons
5. **Experience**: Professional experience timeline
6. **Services**: AI services offered with pricing
7. **Projects**: Placeholder for future projects
8. **Contact**: Contact information and form

## Technologies Used

- HTML5
- CSS3 (with modern features like Grid, Flexbox, CSS Variables)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Inter)

## Local Development

1. Clone or download the project files
2. Open a terminal in the project directory
3. Start a local server:
   ```bash
   python3 -m http.server 8000
   ```
4. Open your browser and navigate to `http://localhost:8000`

## Deployment Options

### Option 1: Static Hosting Services
- **Netlify**: Drag and drop the entire folder to Netlify
- **Vercel**: Connect your GitHub repository or upload files
- **GitHub Pages**: Push to a GitHub repository and enable Pages

### Option 2: Traditional Web Hosting
- Upload all files to your web hosting provider's public_html or www directory
- Ensure the main file is named `index.html`

### Option 3: Local Server
- Use the Python HTTP server as shown in Local Development
- For production, consider using nginx or Apache

## File Structure

```
ai-portfolio/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css       # Main stylesheet
│   ├── js/
│   │   └── script.js       # JavaScript functionality
│   └── images/
│       ├── profile.png     # Profile photo
│       ├── ai-bg-1.jpg     # Background image 1
│       ├── ai-bg-2.jpg     # Background image 2
│       └── data-bg.jpg     # Data background
└── README.md               # This file
```

## Customization

### Updating Content
- Edit `index.html` to update text content, contact information, and links
- Replace images in `assets/images/` with your own photos
- Modify `assets/css/style.css` for styling changes
- Update `assets/js/script.js` for functionality changes

### Color Scheme
The website uses a purple gradient color scheme. To change colors, update the CSS variables in `style.css`:
```css
:root {
  --primary-color: #667eea;
  --secondary-color: #764ba2;
  /* Add more custom colors as needed */
}
```

### Adding Projects
Replace the "Coming Soon" placeholder in the Projects section with actual project cards following the same structure as the Services section.

## Contact Information

- **Phone**: 01123618076
- **Email**: ziad130512@gmail.com
- **GitHub**: https://github.com/ziad-ahemd
- **LinkedIn**: [Add LinkedIn URL]

## License

This portfolio template is free to use and modify for personal and commercial purposes.

