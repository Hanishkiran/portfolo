# Product Manager Portfolio Website

A modern, professional portfolio website designed to showcase your Product Manager experience and help you land interviews at top tech companies, government digital agencies, and data-driven product teams.

## 🚀 Features

- **Modern, Clean Design**: Professional blue/navy color scheme with minimalist aesthetic
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Case Studies**: Detailed case study pages for each major project
- **Easy Navigation**: Intuitive navigation with smooth scrolling
- **Performance Optimized**: Fast loading times and smooth animations

## 📁 Project Structure

```
.
├── index.html              # Landing page with hero, highlights, and case studies
├── about.html              # About page with your story and background
├── contact.html            # Contact page with form and contact info
├── case-studies/          # Case study pages
│   ├── gic-eagle.html
│   ├── govtech-cybersecurity.html
│   ├── affinidi-gaming.html
│   ├── returnontalent.html
│   └── greenchain.html
├── css/
│   └── styles.css         # Main stylesheet with all styling
├── js/
│   └── main.js            # JavaScript for navigation and interactivity
└── README.md              # This file
```

## 🎨 Customization Guide

### 1. Update Personal Information

**Contact Information** (`contact.html`):
- Update email address
- Update LinkedIn profile URL
- Update location if needed

**LinkedIn Links** (all pages):
- Search for `https://linkedin.com/in/yourprofile` and replace with your actual LinkedIn URL

### 2. Add Your Professional Headshot

Replace the placeholder in:
- `index.html` (hero section)
- `about.html` (about section)

Replace the `<div class="profile-placeholder">` with:
```html
<img src="assets/your-headshot.jpg" alt="Hanish Kiran" class="profile-image">
```

Then add this CSS to `css/styles.css`:
```css
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    box-shadow: 0 10px 30px rgba(30, 58, 138, 0.2);
}
```

### 3. Update Case Study Content

Each case study page in `case-studies/` can be customized with:
- More specific metrics
- Additional screenshots/images
- More detailed technical information
- Links to live products or demos

### 4. Add Images/Screenshots

Create an `assets/` folder and add:
- Your professional headshot
- Case study screenshots
- Project images
- Any other visual assets

Then reference them in your HTML files.

### 5. Customize Colors (Optional)

The color scheme is defined in `css/styles.css` at the top in the `:root` section:
```css
:root {
    --primary-blue: #1e3a8a;
    --navy: #0f172a;
    --charcoal: #1e293b;
    /* ... */
}
```

### 6. Set Up Contact Form

The contact form in `contact.html` currently shows an alert. To make it functional:

**Option 1: Use a form service** (recommended for static hosting):
- Formspree
- Netlify Forms
- Google Forms

**Option 2: Add backend integration**:
- Connect to your email service
- Use a serverless function (AWS Lambda, Vercel Functions, etc.)

## 🌐 Deployment

### Option 1: GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select your branch and folder
4. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 2: Netlify
1. Drag and drop your project folder to [Netlify Drop](https://app.netlify.com/drop)
2. Your site will be live instantly with a free URL
3. You can add a custom domain later

### Option 3: Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts

### Option 4: Any Static Hosting
Since this is a static website (HTML, CSS, JS), it can be hosted on any static hosting service.

## 📝 Content Updates

### Adding New Case Studies
1. Create a new HTML file in `case-studies/` folder
2. Use one of the existing case studies as a template
3. Add a link to it in `index.html` in the case studies grid

### Updating Skills
Edit the skills section in `index.html` to add or remove skills.

### Updating Career Highlights
Edit the highlights section in `index.html` to update your achievements.

## 🔧 Technical Details

- **No Build Process Required**: Pure HTML, CSS, and JavaScript
- **No Dependencies**: Works out of the box
- **Modern CSS**: Uses CSS Grid, Flexbox, and CSS Variables
- **Responsive Design**: Mobile-first approach with breakpoints at 768px and 480px
- **Smooth Animations**: CSS transitions and JavaScript for interactivity

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🎯 Next Steps

1. **Add Your Headshot**: Replace placeholder with your professional photo
2. **Update Contact Info**: Add your email and LinkedIn URL
3. **Customize Content**: Add more specific details to case studies
4. **Add Images**: Include screenshots and visuals from your projects
5. **Test on Mobile**: Ensure everything looks good on mobile devices
6. **Deploy**: Choose a hosting option and go live!

## 💡 Tips for Success

- **Keep it Updated**: Regularly update your portfolio with new projects and achievements
- **Use Real Metrics**: Quantify your impact with specific numbers and percentages
- **Tell Stories**: Each case study should tell a compelling story about your process and results
- **Be Authentic**: Show your unique approach and personality
- **Optimize Images**: Compress images before adding them to keep load times fast

## 📧 Support

If you need help customizing or deploying your portfolio, feel free to reach out or refer to the code comments in the HTML and CSS files.

---

**Good luck with your job search!** 🚀

