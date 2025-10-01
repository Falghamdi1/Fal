# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML5, CSS3, and JavaScript.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Navigation**: Smooth scrolling between sections with active link highlighting
- **Contact Form**: Functional contact form with validation
- **Project Showcase**: Cards for displaying projects and certificates
- **Skills Section**: Visual representation of your technical skills
- **Social Links**: Easy integration with your social media profiles

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## 🎨 Customization Guide

### 1. Personal Information
Edit the following in `index.html`:

- **Name**: Replace "Your Name" throughout the file
- **Title**: Update "Full Stack Developer & Creative Problem Solver"
- **Bio**: Customize the About Me section content
- **Contact Info**: Update email, phone, and location in the contact section

### 2. Profile Photo
Replace the placeholder in the hero section:
```html
<div class="profile-placeholder">
    <!-- Replace this div with: -->
    <img src="your-photo.jpg" alt="Your Name" class="profile-image">
</div>
```

### 3. Projects & Certificates
Update the project cards in the projects section:
- Change project titles, descriptions, and technologies
- Update links to your actual projects
- Replace placeholder images with real project screenshots

### 4. Skills
Modify the skills grid in the About section:
- Add/remove skill items
- Update icons using Font Awesome classes
- Customize skill names

### 5. Social Links
Update social media links in the contact section:
```html
<a href="https://github.com/yourusername" class="social-link">
<a href="https://linkedin.com/in/yourprofile" class="social-link">
```

### 6. Resume
Add your resume:
- Upload your PDF resume file
- Update the download link in the resume section
- Or embed your resume using an iframe

### 7. Colors & Styling
Customize the color scheme in `styles.css`:
```css
:root {
    --primary-color: #2563eb;    /* Main blue color */
    --secondary-color: #1d4ed8;  /* Darker blue */
    --accent-color: #f59e0b;     /* Optional accent color */
}
```

## 🚀 Getting Started

1. **Download the files** to your computer
2. **Customize the content** following the guide above
3. **Test locally** by opening `index.html` in your browser
4. **Deploy** to your preferred hosting platform

## 🌐 Deployment Options

### GitHub Pages (Free)
1. Create a new repository on GitHub
2. Upload your files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify (Free)
1. Drag and drop your project folder to [netlify.com](https://netlify.com)
2. Your site will be live instantly with a custom URL

### Vercel (Free)
1. Connect your GitHub repository to [vercel.com](https://vercel.com)
2. Automatic deployments on every push

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 🛠️ Technical Details

- **HTML5**: Semantic markup with accessibility in mind
- **CSS3**: Flexbox and Grid layouts, CSS animations
- **JavaScript**: ES6+ features, intersection observers, form validation
- **Font Awesome**: Icons for social links and UI elements
- **Google Fonts**: Inter font family for modern typography

## 📧 Contact Form Setup

The contact form currently shows a success message. To make it functional:

1. **Use a form service** like Formspree, Netlify Forms, or EmailJS
2. **Add server-side handling** if you have backend capabilities
3. **Update the form action** in the HTML and JavaScript

Example with Formspree:
```html
<form action="https://formspree.io/f/your-form-id" method="POST">
```

## 🎯 SEO Optimization

To improve search engine visibility:

1. Update the `<title>` tag with your name
2. Add meta description and keywords
3. Include Open Graph tags for social sharing
4. Add structured data markup
5. Optimize images with alt text

## 📄 License

This template is free to use for personal and commercial projects. No attribution required, but appreciated!

## 🤝 Support

If you need help customizing your portfolio:
1. Check the comments in the code files
2. Refer to this README
3. Search for tutorials on HTML/CSS/JavaScript basics

---

**Happy coding! 🚀**