# My Personal Blog

A modern, responsive personal blog built with Tailwind CSS and deployed on GitHub Pages.

## 🌐 Live Site

Visit the blog at: **[https://pengjianbo0.github.io](https://pengjianbo0.github.io)**

## ✨ Features

- **Dark Theme**: Eye-friendly dark color scheme with custom gradient backgrounds
- **Responsive Design**: Fully responsive layout that works on mobile, tablet, and desktop
- **Card-Based Layout**: Modern card design for article previews
- **Custom Fonts**: 
  - Playfair Display for elegant headings
  - Inter for clean, readable body text
- **Smooth Animations**: Hover effects and smooth scrolling
- **Zero Build Process**: Uses Tailwind CSS Play CDN - no local build required

## 🎨 Customization

### Changing Content

To customize the blog content, edit the `index.html` file:

1. **Update Site Title**: Change the text in the header section (around line 68)
2. **Modify Hero Section**: Edit the welcome message and description (lines 79-95)
3. **Add/Edit Articles**: Modify the article cards in the Articles section (starting around line 103)
4. **Update About Section**: Personalize the About section (around line 290)
5. **Social Links**: Update social media URLs in the footer (around line 309)

### Changing Colors

The color palette is defined in the Tailwind config (lines 21-36). Key colors:
- `primary`: Main accent color (currently cyan-blue)
- `dark.bg`: Main background color
- `dark.surface`: Card and surface background
- `dark.card`: Border and subtle elements
- `dark.text`: Primary text color
- `dark.muted`: Secondary text color

### Changing Fonts

To use different fonts:
1. Update the Google Fonts link (around line 13)
2. Modify the font families in the Tailwind config (lines 37-40)

## 📝 Adding New Articles

To add a new article card, copy one of the existing article blocks (lines 103-132) and modify:
- The gradient background color (`bg-gradient-to-br from-X to-Y`)
- The category tag and color
- The date
- The article title
- The description
- The link URL (currently set to `#`)

## 🚀 Deployment

This site is automatically deployed to GitHub Pages:
1. Any changes pushed to the `main` branch will be automatically published
2. The site will be available at `https://pengjianbo0.github.io`
3. GitHub Pages typically deploys changes within a few minutes

## 🛠️ Technology Stack

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via Play CDN)
- **Google Fonts**: Playfair Display & Inter
- **GitHub Pages**: Free hosting platform

## 📱 Browser Support

This blog works on all modern browsers including:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

Feel free to use this template for your own personal blog. No attribution required.

## 🤝 Contributing

This is a personal blog, but suggestions and improvements are welcome! Feel free to open an issue or submit a pull request.