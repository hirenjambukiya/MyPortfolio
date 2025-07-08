# Hiren's Portfolio Website

A modern, responsive portfolio website built with HTML5, CSS3, Bootstrap 5, and JavaScript. Features a clean design with smooth animations, dark/light mode toggle, and fully responsive layout.

## 🚀 Features

### Core Features
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean design with soft shadows, rounded cards, and hover animations
- **Smooth Scrolling**: Seamless navigation between sections
- **Sticky Navigation**: Collapsible navbar that stays at the top
- **Scroll Animations**: AOS (Animate On Scroll) library integration

### Interactive Features
- **Typing Animation**: Animated text effect in the hero section
- **Dark/Light Mode Toggle**: Switch between themes with persistent storage
- **Back-to-Top Button**: Smooth scroll to top functionality
- **Contact Form**: Functional contact form with validation
- **Download CV Button**: Simulated CV download functionality
- **Hover Effects**: Interactive elements with smooth transitions

### Sections
1. **Hero Section**: Introduction with animated typing effect
2. **About Section**: Profile information with statistics
3. **Skills Section**: Technical skills organized by category
4. **Services Section**: Three main service offerings
5. **Portfolio Section**: Project showcase with hover effects
6. **Contact Section**: Contact information and form
7. **Footer**: Social links and copyright information

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS variables and animations
- **Bootstrap 5**: Responsive grid system and components
- **Font Awesome**: Icons throughout the website
- **AOS Library**: Scroll animations
- **Vanilla JavaScript**: Interactive functionality

## 📁 File Structure

```
PortfolioWithCursor/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Quick Start

1. **Clone or Download**: Get the files to your local machine
2. **Open in Browser**: Simply open `index.html` in any modern web browser
3. **No Build Process**: This is a static website - no compilation needed!

## 🎨 Customization

### Personal Information
Edit the following in `index.html`:

```html
<!-- Hero Section -->
<h1>Hi, I'm <span class="text-primary">Your Name</span></h1>
<h2 class="h3 mb-4"><span class="typing-text"></span></h2>

<!-- Contact Information -->
<div class="contact-item mb-3">
    <i class="fas fa-envelope text-primary me-3"></i>
    <span>your.email@example.com</span>
</div>
```

### Skills and Technologies
Update the skills section in `index.html`:

```html
<div class="skill-badges">
    <span class="badge bg-primary me-2 mb-2">Your Skill 1</span>
    <span class="badge bg-primary me-2 mb-2">Your Skill 2</span>
</div>
```

### Portfolio Projects
Modify the portfolio section:

```html
<div class="portfolio-content">
    <h5>Your Project Name</h5>
    <p>Project description</p>
    <div class="portfolio-tags">
        <span class="badge bg-primary">Technology Used</span>
    </div>
</div>
```

### Colors and Theme
Customize colors in `styles.css`:

```css
:root {
    --primary-color: #007bff;    /* Main brand color */
    --info-color: #17a2b8;       /* Secondary color */
    --success-color: #28a745;    /* Success color */
    --warning-color: #ffc107;    /* Warning color */
}
```

## 📱 Responsive Breakpoints

- **Mobile**: < 576px
- **Tablet**: 576px - 768px
- **Desktop**: > 768px

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## 🔧 Advanced Customization

### Adding New Sections
1. Add the HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Add navigation link in the navbar
4. Update JavaScript if needed

### Modifying Animations
Edit the AOS initialization in `script.js`:

```javascript
AOS.init({
    duration: 1000,        // Animation duration
    easing: 'ease-in-out', // Animation easing
    once: true,            // Animate only once
    mirror: false          // Mirror animation on scroll up
});
```

### Custom Typing Animation
Modify the titles array in `script.js`:

```javascript
const titles = [
    'Your Title 1',
    'Your Title 2',
    'Your Title 3'
];
```

## 📧 Contact Form

The contact form includes:
- Name validation
- Email validation
- Message validation
- Success/error notifications
- Form reset after submission

To make it functional, replace the simulated submission with actual backend integration.

## 🌙 Dark Mode

The dark mode feature:
- Toggles between light and dark themes
- Persists user preference in localStorage
- Automatically applies saved theme on page load
- Smooth transitions between themes

## 📊 Performance Features

- **Throttled Scroll Events**: Optimized scroll handling
- **Lazy Loading**: Images and animations load efficiently
- **CSS Variables**: Efficient theme switching
- **Minimal Dependencies**: Only essential external libraries

## 🚀 Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop the folder to Netlify
2. Or connect your GitHub repository
3. Automatic deployment on push

### Vercel
1. Import your GitHub repository
2. Automatic deployment and preview URLs

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you find any bugs or have suggestions, please open an issue.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Bootstrap**: For the responsive framework
- **Font Awesome**: For the beautiful icons
- **AOS Library**: For scroll animations
- **Unsplash**: For placeholder images (if used)

---

**Made with ❤️ by Hiren**

For questions or support, feel free to reach out! 