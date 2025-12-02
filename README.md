# Portfolio Website - DevOps Engineer & Python Automation Developer

A modern, responsive portfolio website showcasing skills and experience as a DevOps Engineer and Python Automation Developer.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Sections**:
  - Hero section with animated typing effect
  - About section with statistics
  - Skills categorized by technology area
  - Professional experience timeline
  - Featured projects showcase
  - Contact form
- **Performance Optimized**: Fast loading with optimized assets
- **Cross-browser Compatible**: Works on all modern browsers

## Technologies Used

- HTML5
- CSS3 (with CSS Variables and Animations)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons

## Sections

1. **Home/Hero**: Introduction with call-to-action buttons
2. **About**: Brief bio and key statistics
3. **Skills**: Technical skills organized by categories
4. **Experience**: Professional timeline with detailed descriptions
5. **Projects**: Showcase of featured projects
6. **Contact**: Contact form and information

## Customization

### Update Personal Information

1. **Edit `index.html`**:
   - Update name and title in the hero section
   - Modify about section text
   - Update experience timeline with your actual work history
   - Customize projects with your real projects
   - Add your social media links
   - Update contact information

2. **Edit `styles.css`**:
   - Modify color scheme by changing CSS variables in `:root`
   - Adjust spacing, fonts, and other design elements
   - Customize animations

3. **Edit `script.js`**:
   - Modify interactive behaviors as needed
   - Update form submission handler for your backend

### Color Customization

Update the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #0ea5e9;      /* Main theme color */
    --secondary-color: #6366f1;    /* Secondary accent */
    --dark-bg: #0f172a;            /* Background color */
    --darker-bg: #020617;          /* Darker sections */
    --light-bg: #1e293b;           /* Card backgrounds */
    --text-primary: #f8fafc;       /* Main text color */
    --text-secondary: #cbd5e1;     /* Secondary text */
}
```

## Setup Instructions

1. **Download/Clone** all files to your local machine

2. **Update your information** in `index.html`:
   - Replace placeholder text with your actual details
   - Update social media links
   - Add your email and contact info

3. **Customize styling** in `styles.css` if desired

4. **Test locally**:
   - Open `index.html` in your web browser
   - Test all links and interactions
   - Check responsiveness on different screen sizes

5. **Deploy**:
   - Upload to your web hosting service
   - Or use services like GitHub Pages, Netlify, or Vercel

## Deployment Options

### GitHub Pages
1. Create a GitHub repository
2. Push your code
3. Enable GitHub Pages in repository settings

### Netlify
1. Create account on Netlify
2. Drag and drop your folder
3. Your site is live!

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts

## Contact Form Integration

The contact form currently displays an alert. To make it functional:

1. **Use a backend service** like:
   - FormSpree
   - EmailJS
   - Netlify Forms
   - Your own backend API

2. **Example with FormSpree**:
   - Sign up at formspree.io
   - Get your form endpoint
   - Update the form action in HTML

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

- Optimize images before adding them
- Use WebP format for better compression
- Consider lazy loading for images
- Minify CSS and JS for production

## Future Enhancements

- Add a blog section
- Integrate with a CMS
- Add more animations
- Include a dark/light mode toggle
- Add project detail pages
- Integrate with GitHub API to show real projects

## License

Free to use and modify for personal and commercial projects.

## Support

For questions or issues, please reach out through the contact form on the website.

---

**Built with ❤️ by Syed**
