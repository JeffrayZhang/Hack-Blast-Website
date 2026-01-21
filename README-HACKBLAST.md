# Hack Blast Website

The Ultimate Hackathon Experience - A modern, responsive website built with Bootstrap and custom styling.

## 🚀 Features

- **Responsive Design**: Looks great on all devices
- **Smooth Animations**: Built with AOS (Animate On Scroll)
- **Modern UI**: Clean and professional Bootstrap-based design
- **Single Page Application**: Smooth scrolling navigation
- **Contact Form**: Ready for integration with backend
- **Fully Customizable**: Easy to modify colors, content, and sections

## 📋 Sections

- **Hero**: Eye-catching landing section with call-to-action
- **About**: Information about the hackathon
- **Stats**: Impressive numbers (participants, projects, prizes, mentors)
- **Schedule**: Detailed event timeline
- **Prizes**: Showcase of awards and prizes
- **Sponsors**: Space for sponsor logos and information
- **FAQ**: Common questions and answers
- **Contact**: Contact form and information

## 🛠️ Setup

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd Hack-Blast-Website
   ```

2. **Install dependencies** (optional, for development server)
   ```bash
   npm install
   ```

3. **Run development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   Navigate to `http://localhost:5173` (or the port shown in terminal)

5. **Build for production**
   ```bash
   npm run build
   ```

## 🎨 Customization

### Colors
Edit `/assets/css/main.css` to change the color scheme:
```css
:root {
  --accent-color: #ff6b35; /* Change this to your brand color */
}
```

### Images
Replace placeholder images in `/public/images/`:
- `hero-bg.jpg` - Hero section background (1920x1080px recommended)
- `about.jpg` - About section image (800x600px recommended)

Find free high-quality images at:
- [Unsplash](https://unsplash.com/)
- [Pexels](https://pexels.com/)

### Content
Edit `index.html` directly to update:
- Event details (date, location, schedule)
- Prize information
- FAQ content
- Social media links
- Contact information

### Navigation
Update the header section in `index.html`:
```html
<nav id="navmenu" class="navmenu">
  <ul>
    <li><a href="#hero">Home</a></li>
    <!-- Add or remove menu items -->
  </ul>
</nav>
```

## 📱 Social Media Links

Update social media links in the header and footer:
```html
<div class="header-social-links">
  <a href="YOUR_TWITTER_URL" class="twitter"><i class="bi bi-twitter-x"></i></a>
  <a href="YOUR_INSTAGRAM_URL" class="instagram"><i class="bi bi-instagram"></i></a>
  <a href="YOUR_LINKEDIN_URL" class="linkedin"><i class="bi bi-linkedin"></i></a>
  <a href="YOUR_DISCORD_URL" class="discord"><i class="bi bi-discord"></i></a>
</div>
```

## 📧 Contact Form

The contact form requires backend integration. Options:
1. **Formspree**: Simple form backend (https://formspree.io/)
2. **Netlify Forms**: If hosting on Netlify
3. **Custom Backend**: Build your own with Node.js, PHP, etc.

Update the form action in `index.html`:
```html
<form action="YOUR_FORM_ENDPOINT" method="post" class="php-email-form">
```

## 🚀 Deployment

### GitHub Pages
1. Push to GitHub
2. Go to Settings > Pages
3. Select branch and save

### Netlify
1. Connect your GitHub repository
2. Deploy automatically on push

### Vercel
1. Import your GitHub repository
2. Deploy with zero configuration

## 🎯 To-Do Before Launch

- [ ] Replace placeholder images with real images
- [ ] Update event date and location
- [ ] Add sponsor logos
- [ ] Configure contact form backend
- [ ] Add real social media links
- [ ] Test on mobile devices
- [ ] Add favicon
- [ ] Set up analytics (Google Analytics, etc.)
- [ ] Update meta descriptions for SEO

## 📄 Technologies Used

- **HTML5**: Structure
- **CSS3**: Styling with custom properties
- **Bootstrap 5.3.3**: Responsive framework
- **Bootstrap Icons**: Icon library
- **AOS**: Scroll animations
- **PureCounter**: Animated counters
- **JavaScript**: Interactivity
- **Vite**: Development server and build tool

## 📝 License

This project is based on the Kelly Bootstrap template. Customize freely for your hackathon!

## 🤝 Contributing

Feel free to fork and submit pull requests to improve the website!

## 💡 Tips

- Use high-quality images for better visual impact
- Keep content concise and engaging
- Test across different browsers and devices
- Optimize images for web (compress them)
- Add meta tags for better SEO
- Consider adding a registration form
- Update the title and meta descriptions in index.html
- Add Google Analytics or similar for tracking

## 📞 Support

For questions or issues, please open an issue on GitHub or contact the team.

---

Built with ❤️ for Hack Blast
