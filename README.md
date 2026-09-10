# DevFlux Portfolio

A modern, dark-themed DevOps engineer portfolio website showcasing skills, projects, and journey in the world of DevOps and Cloud infrastructure.

## Live Demo

🌐 **[devflux-portfolio](https://abhiabhi1019.github.io/devflux-portfolio)**

## Features

- 🎨 **Dark Mode Design** - Professional dark theme with purple accent colors
- 📱 **Fully Responsive** - Optimized for desktop, tablet, and mobile devices
- ⚡ **Fast & Lightweight** - Pure HTML, CSS, and JavaScript (no frameworks)
- 🎯 **Smooth Animations** - Scroll-based animations and transitions
- 💻 **Terminal Widget** - Interactive terminal-style hero section
- 📊 **Stats Animation** - Animated counter for key metrics
- 🔗 **GitHub Integration** - Direct links to DevOps projects

## Sections

1. **Hero** - Introduction with animated terminal
2. **About** - Personal overview and statistics
3. **Skills** - Technical skills organized by category
4. **Projects** - Featured DevOps projects from GitHub
5. **Journey** - DevOps learning timeline
6. **Resume** - Download placeholder
7. **Contact** - Social links and contact information

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Fonts**: Inter, JetBrains Mono (Google Fonts)
- **Icons**: Custom SVG icons
- **Hosting**: GitHub Pages

## DevOps Skills Highlighted

- ☁️ **Cloud**: AWS (EC2, S3, VPC, IAM)
- 🐳 **Containerization**: Docker, Docker Compose, Kubernetes
- 🔄 **CI/CD**: Jenkins, GitHub Actions
- 🐧 **Linux**: Ubuntu, CentOS, Shell Scripting
- 🛠️ **Version Control**: Git, GitHub
- 💻 **Programming**: Python, Bash, YAML

## Featured Projects

| Project | Description | Tech Stack |
|---------|-------------|------------|
| LAMP Stacks | EC2 + WordPress deployment | AWS, Linux, Apache, MySQL, PHP |
| Docker Multi-Stage | Node.js + Nginx reverse proxy | Docker, Node.js, Nginx |
| CI/CD Pipeline | Jenkins automation | Jenkins, Docker, Python |
| Magento DevOps | Full Docker + Jenkins workflow | PHP, Docker, Jenkins |

## Local Development

### Prerequisites

- A modern web browser
- Python 3 (for local server)

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Abhiabhi1019/devflux-portfolio.git
   cd devflux-portfolio
   ```

2. Start a local server:
   ```bash
   python3 -m http.server 8000
   ```

3. Open in browser:
   ```
   http://localhost:8000
   ```

## Deployment

This portfolio is automatically deployed to GitHub Pages using GitHub Actions.

### CI/CD Pipeline

```
git push → GitHub Actions → GitHub Pages → Live Website
```

The deployment workflow:
1. Code is pushed to `main` branch
2. GitHub Actions triggers the build
3. Static files are uploaded as artifacts
4. Deployed to GitHub Pages

## Project Structure

```
devflux-portfolio/
├── index.html              # Main HTML file
├── style.css               # Styles with dark theme
├── script.js               # JavaScript for interactivity
├── README.md               # Project documentation
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions deployment
├── assets/
│   ├── images/             # Profile photos, icons
│   └── resume/             # Resume PDF
└── projects/               # Project-specific files
```

## Customization

### Colors

Modify the CSS custom properties in `style.css`:

```css
:root {
    --accent-primary: #8b5cf6;    /* Main purple */
    --accent-secondary: #a78bfa;  /* Light purple */
    --bg-primary: #0a0a0f;        /* Dark background */
}
```

### Content

- Edit `index.html` to update personal information
- Modify project cards in the Projects section
- Update skills in the Skills section
- Add your resume PDF to `assets/resume/`

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

## Performance

- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)
- **First Contentful Paint**: < 1s
- **Total Blocking Time**: < 100ms

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## Author

**Abhijith CM**
- GitHub: [@Abhiabhi1019](https://github.com/Abhiabhi1019)
- LinkedIn: [Abhijith CM](https://linkedin.com/in/abhijith-cm)

## License

This project is open source and available under the [MIT License](LICENSE).

---

Built with ❤️ using HTML, CSS, and JavaScript | Deployed with GitHub Actions