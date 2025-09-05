# Ved Darji - Portfolio Website

A modern, responsive portfolio website showcasing AI/ML expertise and automation skills. Built with HTML, CSS, and JavaScript.

## 🚀 Features

- **Responsive Design**: Mobile-first approach with smooth animations
- **Modern UI/UX**: Clean, professional design with interactive elements
- **Smooth Scrolling**: Seamless navigation between sections
- **Interactive Elements**: Hover effects, animations, and form validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation

## 📁 File Structure

```
Portfolio Site/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # This file
└── profile-image.jpg   # Your profile image (add your image here)
```

## 🛠️ Setup Instructions

### 1. Add Your Profile Image
- Place your profile image in the root directory
- Rename it to `profile-image.jpg`
- Recommended dimensions: 400x500px or similar aspect ratio
- Supported formats: JPG, PNG, WebP

### 2. Customize Content
- Open `index.html` and update the following:
  - Personal information (name, location, contact details)
  - Social media links (GitHub, LinkedIn, Twitter)
  - Project descriptions and technologies
  - Experience details
  - Skills and expertise

### 3. Update Social Links
Replace the placeholder social media links in `index.html`:
```html
<a href="YOUR_GITHUB_URL" class="social-link"><i class="fab fa-github"></i></a>
<a href="YOUR_LINKEDIN_URL" class="social-link"><i class="fab fa-linkedin"></i></a>
<a href="YOUR_TWITTER_URL" class="social-link"><i class="fab fa-twitter"></i></a>
```

### 4. Customize Colors (Optional)
Edit `styles.css` to change the color scheme:
```css
:root {
    --primary-color: #2563eb;      /* Main blue color */
    --secondary-color: #1d4ed8;    /* Darker blue for hover */
    --text-color: #1e293b;         /* Main text color */
    --text-light: #64748b;         /* Light text color */
    --background-light: #f8fafc;   /* Light background */
}
```

## 🌐 Deployment

### Option 1: GitHub Pages
1. Create a new GitHub repository
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

### Option 2: Netlify
1. Drag and drop the project folder to [Netlify](https://netlify.com)
2. Your site will be deployed automatically
3. Customize the domain if needed

### Option 3: Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts to deploy

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🎨 Customization Guide

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Add JavaScript functionality in `script.js` if needed

### Modifying Animations
- Edit animation durations in `script.js`
- Modify CSS transitions in `styles.css`
- Adjust intersection observer options

### Changing Fonts
- Update Google Fonts link in `index.html`
- Modify font-family in `styles.css`

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Content Sections

1. **Hero Section**: Introduction and profile image
2. **About**: Personal description and statistics
3. **Skills**: Technical skills organized by category
4. **Experience**: Professional timeline
5. **Projects**: Portfolio showcase
6. **Contact**: Contact information and form

## 🚀 Performance Tips

- Optimize images (compress, use WebP format)
- Minify CSS and JavaScript for production
- Enable gzip compression on your server
- Use a CDN for external resources

## 📞 Support

For questions or customization help:
- Email: darjived36@gmail.com
- GitHub: [Your GitHub Profile]

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: Remember to replace placeholder content with your actual information and add your profile image before deploying!
