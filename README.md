# Personal Website

A modern, responsive personal portfolio website showcasing your software engineering experience. Built with vanilla HTML, CSS, and JavaScript for optimal performance and easy customization.

## ✨ Features

- **Modern Design**: Clean, professional layout inspired by contemporary web design
- **Fully Responsive**: Mobile-first design that looks great on all devices
- **Interactive Elements**: Smooth animations, hover effects, and scroll-based reveals
- **Dark Mode**: Toggle between light and dark themes
- **Accessibility**: Keyboard navigation support and semantic HTML
- **Performance Optimized**: Vanilla JavaScript, no frameworks, fast loading
- **Easy to Customize**: Well-structured code with clear sections

## 🚀 Quick Start

1. **Clone or download** this repository
2. **Customize your content** in `index.html`
3. **Run locally**:
   ```bash
   npm install
   npm start
   ```
4. **View your site** at `http://localhost:3000`

## 📝 Customization Guide

### 1. Personal Information

Update the following sections in `index.html`:

```html
<!-- Header Section -->
<h1 class="name">Your Name</h1>
<p class="title">Software Engineer</p>

<!-- Contact Information -->
<a href="mailto:your.email@example.com">your.email@example.com</a>
<a href="https://github.com/yourusername">github.com/yourusername</a>
<!-- Add LinkedIn, portfolio links, etc. -->

<!-- Location -->
<div class="location">Your City, State</div>
```

### 2. About Section

Customize your introduction in the `.intro-section`:
- Replace placeholder text with your background
- Highlight your key skills and experience
- Add your personal touch and personality

### 3. Work Experience

Update each `.job` section with:
- Company names and dates
- Job titles and responsibilities
- Key achievements and technologies used
- Add or remove job entries as needed

### 4. Technical Skills

Modify the `.skills-grid` to reflect your expertise:
- Update programming languages
- Add your frontend/backend technologies
- Include tools and cloud platforms you use
- Organize by your preferred categories

### 5. Education

Update the `.education` section with:
- Your university/institution name
- Degree and graduation year
- Relevant coursework or achievements

### 6. Projects

Add your notable projects in the `.projects-section`:
- Project names and descriptions
- Technologies used
- Links to GitHub repos and live demos
- Add more projects by copying the `.project` structure

### 7. Personal Interests

Customize the `.interests-section` to show your personality:
- Hobbies and interests outside of coding
- Community involvement
- Personal projects or contributions

## 🎨 Styling Customization

### Colors and Theme

Modify CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;        /* Main accent color */
    --primary-dark: #1d4ed8;         /* Darker accent */
    --text-primary: #1f2937;         /* Main text color */
    --text-secondary: #6b7280;       /* Secondary text */
    /* ... other variables */
}
```

### Typography

Change fonts by updating the Google Fonts import and CSS:

```css
/* In HTML head */
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">

/* In CSS */
--font-sans: 'YourFont', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
```

## 📱 Responsive Design

The website is built with mobile-first responsive design:
- **Mobile**: < 480px
- **Tablet**: 480px - 768px  
- **Desktop**: > 768px

Breakpoints are defined in the CSS media queries and can be customized as needed.

## 🌙 Dark Mode

The website includes a dark mode toggle button. Users' theme preference is automatically saved to localStorage and restored on subsequent visits.

## 🚀 Deployment Options

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify
1. Connect your GitHub repository to Netlify
2. Set build command to `npm run build` (optional)
3. Set publish directory to `/` (root)
4. Deploy automatically on git push

### Vercel
1. Connect your GitHub repository to Vercel
2. Deploy with zero configuration
3. Automatic deployments on git push

### Custom Domain
Update the `homepage` field in `package.json` with your custom domain.

## 🛠 Development

### Available Scripts

- `npm start` - Start local development server
- `npm run dev` - Start with live reload
- `npm run build` - Build for production (static site)

### File Structure

```
personal-website/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
├── package.json        # Dependencies and scripts
└── README.md          # This file
```

## 🎯 Performance Tips

- **Images**: Optimize images before adding them
- **Fonts**: Limit to 2-3 font weights maximum
- **Icons**: Font Awesome is loaded from CDN, consider self-hosting for better performance
- **JavaScript**: Code is vanilla JS for optimal performance

## 📞 Support

If you need help customizing your website:
1. Check the inline comments in the code
2. Refer to this README
3. Search for specific CSS/HTML tutorials online
4. Consider hiring a developer for complex customizations

## 📄 License

This project is licensed under the MIT License - feel free to use it for your personal website!

---

**Happy coding! 🚀**

*Don't forget to update your contact information and make this website truly yours!*
