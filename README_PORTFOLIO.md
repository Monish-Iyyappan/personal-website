# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript.

## Files

- **index.html** - Main website structure
- **style.css** - Styling and responsive design
- **script.js** - Interactive features and animations

## Quick Start

1. **Open locally**: Simply open `index.html` in your web browser
2. **Customize content**: Edit the text in `index.html` with your information
3. **Update links**: Replace placeholder links in the Contact section

## How to Customize

### Basic Changes (Edit in index.html)

1. **Your Name & Title**
   - Find: `<h1>Hi, I'm [Your Name]</h1>`
   - Replace with your actual name

2. **About Section**
   - Edit the text under the "About Me" section with your bio

3. **Projects**
   - Modify the three project cards with your actual projects
   - Update tags to reflect your tech stack

4. **Skills**
   - Update the three skill categories with your proficiencies

5. **Contact Links**
   - Replace `your.email@example.com` with your email
   - Update GitHub, LinkedIn, and Twitter URLs

### Color Customization (Edit in style.css)

Find the `:root` section at the top of `style.css`:

```css
:root {
    --primary-color: #2563eb;      /* Main blue - change this */
    --secondary-color: #1e40af;    /* Darker blue - change this */
    --text-color: #1f2937;         /* Text color */
    --light-bg: #f9fafb;           /* Light background */
}
```

Change the hex codes to your preferred colors.

## Deployment Options

### Free Options:

1. **GitHub Pages** (Recommended)
   - Push files to a GitHub repository
   - Go to Settings → Pages → Select main branch
   - Your site will be live at `username.github.io/repo-name`

2. **Netlify**
   - Drag and drop your folder at https://netlify.com
   - Instant live hosting

3. **Vercel**
   - Connect your GitHub repo at https://vercel.com
   - Automatic deployments on updates

4. **Firebase Hosting**
   - Sign up at https://firebase.google.com
   - Free tier includes hosting

### How to Deploy to GitHub Pages:

```bash
# Initialize git (if not already done)
git init

# Add files
git add .
git commit -m "Initial commit: Personal portfolio"

# Create a new repository on GitHub
# Then push:
git remote add origin https://github.com/yourusername/portfolio.git
git branch -M main
git push -u origin main

# Enable GitHub Pages in repository settings
```

## Features

✨ **Responsive Design** - Works on desktop, tablet, and mobile
✨ **Smooth Animations** - Fade-in effects and transitions
✨ **Modern Design** - Clean, professional look
✨ **Easy to Customize** - Simple HTML structure
✨ **No Dependencies** - Pure HTML, CSS, and JavaScript
✨ **SEO Friendly** - Proper semantic HTML

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Additional Features You Can Add

- Blog section
- Resume/CV download
- Dark mode toggle
- Contact form (using services like Formspree)
- Image gallery
- Testimonials section

## Tips

- Add a professional profile photo to the hero section
- Keep project descriptions concise and impactful
- Include links to live demos or GitHub repos for projects
- Update your portfolio regularly with new projects
- Use meaningful section titles that match your brand

## Support

For questions or improvements, feel free to edit the files directly or research web development tutorials for more advanced customizations.

---

Happy building! 🚀
