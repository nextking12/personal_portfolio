# Jay King's Personal Portfolio 🚀

A modern, responsive personal portfolio website showcasing skills, projects, and professional information. Built with vanilla HTML, CSS, and JavaScript for optimal performance and simplicity.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Navigation**: Mobile-friendly hamburger menu with smooth scrolling
- **Contact Form**: Functional contact form with client-side validation
- **Social Links**: Direct links to LinkedIn and GitHub profiles
- **Performance Optimized**: Fast loading with minimal dependencies
- **GitHub Pages Ready**: Automated deployment with GitHub Actions

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Fonts**: Google Fonts (Inter)
- **Deployment**: GitHub Pages
- **CI/CD**: GitHub Actions

## 📁 Project Structure

```
personal_portfolio/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
├── .github/
│   └── workflows/
│       └── static.yml  # GitHub Pages deployment
└── .idea/              # IDE configuration files
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Basic understanding of HTML/CSS/JavaScript (for customization)

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/nextking12/personal_portfolio.git
   cd personal_portfolio
   ```

2. **Open in browser**
   - Simply open `index.html` in your preferred web browser
   - Or use a local server for better development experience:
   
   **Using Python (if installed):**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```
   
   **Using Node.js (if installed):**
   ```bash
   npx serve .
   ```
   
   **Using VS Code Live Server:**
   - Install Live Server extension
   - Right-click on `index.html` and select "Open with Live Server"

3. **View the site**
   - Open your browser and navigate to `http://localhost:8000` (or the port shown)

## 🎨 Customization

### Personal Information

1. **Update personal details** in `index.html`:
   - Name and title
   - About section content
   - Skills tags
   - Contact information
   - Social media links

2. **Add your projects** by uncommenting and filling the project card templates in the projects section

### Styling

1. **Colors**: Modify the CSS variables or color values in `styles.css`
2. **Fonts**: Change the Google Fonts import in `index.html` and update font-family in CSS
3. **Layout**: Adjust spacing, sizes, and layout in `styles.css`

### Functionality

1. **Contact Form**: Currently shows an alert - integrate with a backend service or email API
2. **Projects**: Add real project data and links
3. **Analytics**: Add Google Analytics or other tracking if needed

## 📱 Sections Overview

- **Navigation**: Fixed header with smooth scroll navigation
- **Hero**: Introduction with call-to-action buttons
- **About**: Personal description and skills showcase
- **Projects**: Featured projects grid (ready for content)
- **Contact**: Contact form and social links
- **Footer**: Copyright information

## 🚀 Deployment

This portfolio is set up for automatic deployment to GitHub Pages:

1. **Push to main branch** - GitHub Actions will automatically deploy
2. **Manual deployment** - Go to Actions tab and run the workflow manually
3. **Custom domain** - Add a `CNAME` file for custom domain setup

### GitHub Pages Setup

1. Go to repository Settings
2. Navigate to Pages section
3. Select "GitHub Actions" as the source
4. The workflow will handle the rest!

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

While this is a personal portfolio, suggestions and improvements are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Contact

**Jay King**
- LinkedIn: [edward-king-jr-385114251](https://www.linkedin.com/in/edward-king-jr-385114251)
- GitHub: [@nextking12](https://www.github.com/nextking12)
- Portfolio: [Live Site](https://nextking12.github.io/personal_portfolio/)

---

⭐ **Star this repo if you found it helpful!**
