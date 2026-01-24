# Sattanathan Chandran - Portfolio Website

A modern, professional, and fully responsive personal portfolio website for a Supply Chain & Logistics professional based in Dubai, UAE.

## 🚀 Features

- **Fully Responsive Design** - Mobile-first approach, works seamlessly on all devices
- **Modern UI/UX** - Clean, minimal, corporate design with professional color palette
- **Smooth Animations** - Scroll-triggered animations and hover effects
- **SEO Optimized** - Meta tags and semantic HTML for better search engine visibility
- **Fast Loading** - Optimized code and minimal dependencies
- **Accessible** - Proper ARIA labels and keyboard navigation support

## 📋 Sections

1. **Hero Section** - Professional introduction with CTA buttons
2. **About Me** - Professional summary and background
3. **Key Skills & Expertise** - Categorized skill cards with icons
4. **Professional Experience** - Timeline-based experience showcase
5. **Education** - Academic qualifications
6. **Certifications** - Professional certifications and development
7. **Awards & Recognition** - Achievements and accolades
8. **Volunteership & Leadership** - Community involvement
9. **Languages** - Language proficiency with progress bars
10. **Contact** - Contact information and form
11. **Footer** - Social links and copyright

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables, flexbox, and grid
- **JavaScript (Vanilla)** - Interactivity and animations
- **Font Awesome** - Icons
- **Google Fonts (Inter)** - Typography

## 📁 File Structure

```
sat-portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # All styling and responsive design
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## 🚀 Getting Started

### Local Development

1. **Clone or download** this repository
2. **Open** `index.html` in your web browser
   - You can simply double-click the file, or
   - Use a local server (recommended for better performance):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```
3. **Navigate** to `http://localhost:8000` in your browser

### No Build Process Required

This is a static website with no build process. Simply open `index.html` or deploy the files as-is.

## 🌐 Deployment Options

### Option 1: GitHub Pages (Free & Easy)

1. **Create a GitHub repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/sat-portfolio.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click **Settings** → **Pages**
   - Under **Source**, select **main** branch and **/ (root)** folder
   - Click **Save**
   - Your site will be live at: `https://yourusername.github.io/sat-portfolio`

### Option 2: Netlify (Recommended)

1. **Sign up** at [netlify.com](https://www.netlify.com) (free account)

2. **Deploy via Drag & Drop**
   - Log in to Netlify
   - Drag and drop your project folder onto the Netlify dashboard
   - Your site will be live instantly with a random URL
   - You can customize the domain name in settings

3. **Deploy via Git** (for continuous deployment)
   - Connect your GitHub repository
   - Netlify will automatically deploy on every push

### Option 3: Vercel

1. **Sign up** at [vercel.com](https://vercel.com)

2. **Import your project**
   - Click **New Project**
   - Import from GitHub or upload your folder
   - Deploy instantly

### Option 4: Traditional Web Hosting

1. **Upload files** via FTP/SFTP to your web hosting provider
2. **Upload these files** to the public HTML directory:
   - `index.html`
   - `styles.css`
   - `script.js`
3. **Access** your site via your domain name

## ✏️ Customization

### Update Contact Information

Edit the contact section in `index.html`:
- Phone number
- Email address
- LinkedIn URL

### Change Colors

Modify CSS variables in `styles.css`:
```css
:root {
    --primary-color: #1a365d;      /* Dark Navy */
    --secondary-color: #2c5282;    /* Medium Blue */
    --accent-color: #3182ce;       /* Bright Blue */
    /* ... */
}
```

### Add Resume Download

1. Place your resume PDF in the project folder
2. Update the download button in `script.js`:
   ```javascript
   window.open('path/to/your-resume.pdf', '_blank');
   ```

### Update Content

All content is in `index.html`. Simply edit the relevant sections:
- Hero section
- About me
- Experience details
- Skills
- Certifications
- etc.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Future Enhancements

The website is designed to be easily extensible. You can add:
- **Projects Portfolio** - Showcase logistics projects or dashboards
- **Blog Section** - Share industry insights
- **Testimonials** - Client or colleague recommendations
- **Interactive Resume** - Enhanced resume viewer
- **Dark Mode Toggle** - User preference for dark/light theme
- **Multi-language Support** - Language switcher

## 📄 License

This portfolio template is free to use and modify for personal or commercial purposes.

## 📧 Contact

For questions or suggestions about this portfolio:
- **Email**: satta02122002@gmail.com
- **LinkedIn**: [linkedin.com/in/sat-logistics](https://linkedin.com/in/sat-logistics)

---

**Built with ❤️ for Supply Chain & Logistics Professionals**
