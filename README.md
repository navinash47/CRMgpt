# AI ChatBot Website

A modern, responsive AI chatbot website designed for GitHub Pages hosting. This website features a beautiful interface that showcases an AI chatbot with interactive elements and smooth animations.

## Features

- 🎨 **Modern Design**: Clean, professional interface with gradient backgrounds and smooth animations
- 📱 **Responsive**: Fully responsive design that works on all devices
- 💬 **Interactive Chat**: Functional chat interface with typing indicators and message history
- ⚡ **Smooth Animations**: CSS animations and transitions for enhanced user experience
- 🎯 **Smooth Scrolling**: Navigation with smooth scrolling to sections
- 📧 **Contact Form**: Interactive contact form with validation
- 🌐 **GitHub Pages Ready**: Optimized for GitHub Pages hosting

## Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **Features**: Showcase of AI chatbot capabilities
3. **About**: Information about the technology and statistics
4. **Contact**: Contact form and company information
5. **Footer**: Links and social media connections

## Technologies Used

- HTML5
- CSS3 (with Flexbox and Grid)
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts (Inter)

## Getting Started

### Prerequisites

- A GitHub account
- Basic knowledge of Git

### Installation

1. Clone this repository or download the files
2. Open `index.html` in your web browser to view the website locally

### Deployment to GitHub Pages

1. **Create a new repository** on GitHub
2. **Upload all files** to your repository (including the `web` folder and `.github` folder)

3. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll down to "GitHub Pages" section
   - Select "Deploy from a branch"
   - Choose "gh-pages" branch and "/ (root)" folder
   - Click "Save"

4. **Your website will be available** at: `https://yourusername.github.io/your-repo-name`

**Note**: This project uses GitHub Actions to automatically deploy from the `web` directory to the `gh-pages` branch. The workflow will run automatically when you push to the main branch.

## File Structure

```
├── web/                # Website files
│   ├── index.html      # Main HTML file
│   ├── styles.css      # CSS styles and animations
│   ├── script.js       # JavaScript functionality
│   ├── 404.html        # Custom 404 error page
│   ├── sitemap.xml     # SEO sitemap
│   └── robots.txt      # Search engine instructions
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Actions deployment workflow
└── README.md           # Project documentation
```

## Customization

### Colors
The website uses a purple gradient theme. You can customize the colors by modifying the CSS variables in `styles.css`:

```css
/* Main gradient colors */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Primary color */
color: #667eea;
```

### Content
- Update the text content in `index.html`
- Modify the chat responses in `script.js`
- Change the contact information and social links

### Features
- Add more sections by copying existing section structure
- Modify the chat functionality in `script.js`
- Add new animations in `styles.css`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Commit and push to the branch
5. Create a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you have any questions or need help with deployment, please open an issue in the repository.

---

**Note**: This is a frontend-only website. The chat functionality is simulated for demonstration purposes. For a production AI chatbot, you would need to integrate with a backend API.