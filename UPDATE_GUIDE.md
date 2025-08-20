# Website Update Guide for Ziad Ahmed Portfolio

This guide explains how to update various aspects of your portfolio website in the future.

## 🔧 Basic File Structure

```
ai-portfolio/
├── index.html              # Main website content
├── assets/
│   ├── css/style.css       # Website styling
│   ├── js/script.js        # Website functionality
│   └── images/             # All images and assets
│       ├── profile.png     # Your profile photo
│       ├── logo.png        # Website logo
│       └── *.jpg           # Background images
└── README.md               # Deployment instructions
```

## 📝 How to Update Content

### 1. Personal Information
**File:** `index.html`

**To change your name/title:**
- Find: `<span class="gradient-text">ZIAD AHMED</span>`
- Replace with your new name

**To update description:**
- Find the hero description paragraph
- Replace with your new description

### 2. About Section
**File:** `index.html`

**To update your about text:**
- Find the `<!-- About Section -->` comment
- Update the paragraphs within the `.about-text` div

### 3. Education
**File:** `index.html`

**To add/modify education:**
- Find the `<!-- Education Section -->` comment
- Update university name, degree, and expected graduation year

### 4. Skills
**File:** `index.html`

**To add/remove skills:**
- Find the `<!-- Skills Section -->` comment
- Add new skill items following this format:
```html
<div class="skill-item">
    <i class="fas fa-icon-name"></i>
    <span>Skill Name</span>
</div>
```

### 5. Experience
**File:** `index.html`

**To update work experience:**
- Find the `<!-- Experience Section -->` comment
- Update company name, position, dates, and bullet points

### 6. Services
**File:** `index.html`

**To modify services:**
- Find the `<!-- Services Section -->` comment
- Update service titles, descriptions, and pricing
- Each service card follows this structure:
```html
<div class="service-card">
    <div class="service-icon">
        <i class="fas fa-icon-name"></i>
    </div>
    <h3>Service Name</h3>
    <p>Service description</p>
    <div class="service-price">Starting from $XX / project</div>
    <button class="btn btn-primary service-btn" data-service="Service Name">Buy Service</button>
</div>
```

### 7. Projects
**File:** `index.html`

**To add/update projects:**
- Find the `<!-- Projects Section -->` comment
- Add new project cards following this format:
```html
<div class="project-card">
    <div class="project-icon">
        <i class="fas fa-icon-name"></i>
    </div>
    <h3>Project Name</h3>
    <p>Project description</p>
    <div class="project-tech">
        <span class="tech-tag">Technology 1</span>
        <span class="tech-tag">Technology 2</span>
    </div>
</div>
```

### 8. Contact Information
**File:** `index.html`

**To update contact details:**
- Find the `<!-- Contact Section -->` comment
- Update phone number, email, GitHub, and LinkedIn links

## 🖼️ How to Update Images

### 1. Profile Photo
- Replace `assets/images/profile.png` with your new photo
- Keep the same filename or update the reference in `index.html`

### 2. Logo
- Replace `assets/images/logo.png` with your new logo
- Recommended size: 200x200 pixels, transparent background

### 3. Background Images
- Replace files in `assets/images/` folder
- Update references in CSS if you change filenames

## 📄 How to Update CV

### Option 1: Replace the File
- Replace the CV file in the project directory
- Update the download link in `index.html`:
```html
<a href="path/to/your/new-cv.pdf" class="btn btn-secondary" download>
    <i class="fas fa-download"></i> Download CV
</a>
```

### Option 2: Use External Link
- Upload your CV to Google Drive, Dropbox, or similar
- Update the href attribute with the direct download link

## 🎨 How to Customize Styling

### Colors
**File:** `assets/css/style.css`

**To change the color scheme:**
- Find the `:root` section at the top
- Update CSS variables:
```css
:root {
    --bg-color: #ffffff;        /* Background color */
    --text-color: #333333;      /* Text color */
    --card-bg: #ffffff;         /* Card background */
    --border-color: #e0e0e0;    /* Border color */
}
```

### Fonts
**To change fonts:**
- Update the Google Fonts import in `index.html`
- Update the font-family in CSS

## 🌐 Domain Setup for Name-Based Navigation

To make your website accessible by typing your name in the browser:

### Option 1: Custom Domain
1. Purchase a domain like `ziadahmed.com` from providers like:
   - Namecheap
   - GoDaddy
   - Google Domains

2. Point the domain to your hosting service
3. Update DNS settings to point to your website

### Option 2: GitHub Pages with Custom Domain
1. Upload your website to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Add a custom domain in the Pages settings
4. Update your domain's DNS to point to GitHub Pages

### Option 3: Free Subdomain Services
- Use services like:
  - Netlify (yourname.netlify.app)
  - Vercel (yourname.vercel.app)
  - GitHub Pages (yourusername.github.io)

## 🚀 Deployment Options

### 1. Netlify (Recommended)
1. Create account at netlify.com
2. Drag and drop your project folder
3. Get instant live URL
4. Easy updates by re-uploading

### 2. Vercel
1. Create account at vercel.com
2. Connect GitHub repository or upload files
3. Automatic deployments on updates

### 3. GitHub Pages
1. Create GitHub repository
2. Upload files to repository
3. Enable Pages in repository settings
4. Access via username.github.io/repository-name

### 4. Traditional Web Hosting
- Upload files via FTP to any web hosting provider
- Services like Bluehost, HostGator, SiteGround

## 🔄 Regular Maintenance

### Monthly Updates
- Update project descriptions
- Add new skills as you learn them
- Update experience section with new achievements

### Quarterly Updates
- Review and update services/pricing
- Add new projects
- Update CV with latest information

### Annual Updates
- Review overall design and consider updates
- Update profile photo if needed
- Review and optimize for search engines

## 📞 Technical Support

If you need help with updates:
1. Basic HTML/CSS tutorials: W3Schools, MDN Web Docs
2. For complex changes, consider hiring a web developer
3. Use browser developer tools (F12) to test changes

## 🔍 SEO Tips

To improve search visibility:
1. Add meta descriptions to `index.html`
2. Use descriptive alt text for images
3. Submit your website to Google Search Console
4. Create social media profiles linking to your website

---

**Remember:** Always backup your website files before making changes!

