<!-- ===========================
   Personal Portfolio Website
   =========================== -->

# Fernando Rodriguez - Portfolio Website

A modern, responsive resume and project portfolio website built with HTML, CSS, and JavaScript.

## 🌐 Website

Visit: [https://frodriguez116.github.io](https://frodriguez116.github.io)

## ✨ Features

- **Responsive Design**: Mobile-first approach with beautiful layouts across all devices
- **Modern UI**: Gradient backgrounds, smooth animations, and polished interactions
- **Resume Section**: Professional experience, skills, education, and certifications
- **Projects Showcase**: Featured projects with descriptions, technologies, and links
- **Contact Section**: Multiple ways to connect (email, LinkedIn, GitHub, Twitter)
- **Navigation**: Sticky navbar with smooth scrolling
- **Performance Optimized**: Clean, efficient code with minimal dependencies
- **Accessibility**: Semantic HTML and ARIA labels

## 📁 File Structure

```
.
├── index.html          # Main HTML file with all sections
├── styles.css          # Complete styling with responsive design
├── script.js           # Interactive functionality
├── README.md           # This file
└── resume.pdf          # (Optional) PDF resume file
```

## 🚀 Getting Started

### Prerequisites
- A web browser (Chrome, Firefox, Safari, Edge)
- Git (optional, for cloning)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Frodriguez116/Frodriguez116.github.io.git
```

2. Navigate to the directory:
```bash
cd Frodriguez116.github.io
```

3. Open `index.html` in your browser or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (with http-server)
npx http-server
```

4. Visit `http://localhost:8000` in your browser

## 🎨 Customization

### Update Personal Information

Edit the following in `index.html`:

1. **Hero Section** (around line 37-44):
   ```html
   <h1>Your Name</h1>
   <p class="tagline">Your Title | Your Expertise</p>
   <p class="bio">Your bio/description</p>
   ```

2. **Resume Section** (around line 68-157):
   - Update professional summary
   - Add your experience
   - List your technical skills
   - Add your education
   - Include your certifications

3. **Projects Section** (around line 184-277):
   - Replace project descriptions
   - Update technology tags
   - Add GitHub and demo links
   - Customize gradient colors

4. **Contact Section** (around line 285-310):
   - Update email address
   - Add your LinkedIn profile URL
   - Add your GitHub profile URL
   - Add your social media links

### Customize Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #667eea;      /* Main color */
    --secondary-color: #764ba2;    /* Gradient end color */
    --accent-color: #f093fb;       /* Accent highlights */
    --text-dark: #2c3e50;          /* Main text color */
    --text-light: #7f8c8d;         /* Secondary text */
    --bg-light: #f8f9fa;           /* Light background */
    --bg-white: #ffffff;           /* White background */
}
```

### Add Your Resume PDF

1. Place your resume PDF file in the root directory (name it `resume.pdf`)
2. The download button will automatically work

### Project Gradient Colors

Change the gradient colors in `index.html` for each project:

```html
<div class="project-image" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);"></div>
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🔧 Features Explained

### Navigation
- Sticky navbar that stays visible while scrolling
- Active link highlighting based on scroll position
- Smooth scroll to sections

### Animations
- Fade-in animations on page load
- Hover effects on cards and buttons
- Smooth transitions throughout

### Interactive Elements
- Smooth scrolling navigation
- Hover animations on project and resume cards
- Responsive button states
- External links open in new tabs

## 📈 SEO Optimization

To improve search engine visibility:

1. Update meta description in `index.html`:
```html
<meta name="description" content="Your custom description">
```

2. Add Open Graph tags:
```html
<meta property="og:title" content="Your Name - Software Engineer">
<meta property="og:description" content="Your description">
```

3. Add a `sitemap.xml` if needed

## 🚀 Deployment

### GitHub Pages (Already Configured)

Your site is automatically deployed to GitHub Pages. Just push to the `main` branch:

```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

### Other Hosting Options

- **Netlify**: Connect your GitHub repo for automatic deployment
- **Vercel**: Similar to Netlify with great performance
- **Firebase Hosting**: Google's hosting with excellent uptime
- **Traditional Hosting**: Upload files via FTP

## 🎯 Performance Tips

- Images are optimized with gradients instead of files
- CSS is minified and efficient
- JavaScript is vanilla (no heavy frameworks)
- Minimal external dependencies (only Font Awesome icons)
- Lazy loading ready for images

## 🔒 Privacy & Security

- No tracking by default
- No data collection
- Safe external links with `rel="noopener noreferrer"`
- No analytics unless you add them

## 📝 Adding a Contact Form

To add a functional contact form, you'll need:

1. Add form HTML
2. Set up a backend service (Firebase, Formspree, etc.)
3. Update the form submission handler in `script.js`

## 📚 Resources Used

- **Font Awesome Icons**: https://fontawesome.com/
- **Google Fonts**: https://fonts.google.com/
- **CSS Gradients**: Built-in browser support
- **Intersection Observer API**: For animations

## 🐛 Troubleshooting

### Links not working?
- Check the href attribute matches the section id
- Ensure all links start with `#` for internal navigation

### Styles not loading?
- Verify `styles.css` is in the same directory
- Clear browser cache (Ctrl+Shift+Delete)

### JavaScript not working?
- Check browser console for errors (F12)
- Ensure `script.js` is properly linked
- JavaScript must be enabled in browser

## 🤝 Contributing

Want to improve this template? Feel free to:
- Fork the repository
- Create a feature branch
- Submit a pull request

## 📄 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

**Fernando Rodriguez**
- GitHub: [@Frodriguez116](https://github.com/Frodriguez116)
- Email: your.email@example.com

## 📞 Support

If you have questions or issues:
1. Check the troubleshooting section
2. Review the code comments
3. Open an issue on GitHub

---

**Happy coding! 🚀**
