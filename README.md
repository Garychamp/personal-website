# Gary Hoare - Personal Website

![Website Status](https://img.shields.io/badge/website-online-brightgreen?style=for-the-badge&logo=googlechrome&logoColor=white) ![HTML](https://img.shields.io/badge/HTML-E34C26?style=for-the-badge&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

A modern, responsive personal portfolio website built with vanilla HTML, CSS, and JavaScript. Showcasing front-end development skills with a focus on clean code and sleek user interfaces.

## 🌐 Live Demo

**Visit the live website:** [https://garychamp.github.io/MyMainWebsite](https://garychamp.github.io/MyMainWebsite)

The site is automatically deployed to GitHub Pages with every push to the main branch.

## 📋 Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Local Development](#local-development)
- [Deployment](#deployment)
- [File Descriptions](#file-descriptions)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## ✨ Features

- **Responsive Design**: Fully responsive layout that works seamlessly across desktop, tablet, and mobile devices
- **Background Video**: Engaging background video with mobile optimization and accessibility controls
- **Smooth Navigation**: Intuitive navigation bar with dropdown menus for easy access to different sections
- **Portfolio Showcase**: Dedicated projects page displaying front-end development work
- **About Section**: Personal introduction and professional background
- **Connect Page**: Multiple ways to get in touch (GitHub, Email)
- **Accessibility**: ARIA labels, semantic HTML, and keyboard navigation support
- **Performance Optimized**: Multiple video format support for better browser compatibility and loading times

## 🗂️ Project Structure

```
personal-website/
├── index.html              # Homepage with hero section
├── about.html              # About page with personal information
├── projects.html           # Portfolio projects showcase
├── connect.html            # Connect/contact page
├── stylesheet.css          # Main CSS styling
├── javascript.js           # Interactive functionality
├── DEPLOYMENT.md           # Deployment documentation
├── Media/                  # Media assets directory
│   ├── background.webm     # Background video (WebM format)
│   ├── background.mp4      # Background video (MP4 format)
│   ├── background-mobile.webm
│   ├── background-mobile.mp4
│   └── background.jpg      # Fallback poster image
└── .github/
    └── workflows/
        └── deploy.yml      # GitHub Actions deployment workflow
```

## 🛠️ Technology Stack

- **HTML5**: Semantic markup and modern HTML structure
- **CSS3**: Custom styling with responsive design and animations
- **JavaScript (Vanilla)**: No framework dependencies - pure JavaScript for interactivity
- **GitHub Pages**: Static site hosting and automatic deployment
- **GitHub Actions**: CI/CD pipeline for automatic deployment

## 🚀 Getting Started

### Prerequisites

- Git
- A modern web browser
- (Optional) Python or Node.js for local server

### Installation

1. **Clone the repository:**
   ```bash
git clone https://github.com/Garychamp/personal-website.git
cd personal-website
```

2. **Open in a browser:**
   - Simply open `index.html` in your web browser, or
   - Use a local development server (see Local Development section)

## 💻 Local Development

### Using Python (Built-in)

```bash
# Python 3.x
python -m http.server 8000

# Python 2.x
python -m SimpleHTTPServer 8000
```

Then visit: `http://localhost:8000`

### Using Node.js

```bash
# Using http-server
npx http-server

# Using Live Server (VS Code Extension)
# Install "Live Server" extension in VS Code
# Right-click on index.html and select "Open with Live Server"
```

### Using VS Code Live Server

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"
4. Your browser will automatically open and update on file changes

## 📦 Deployment

This project uses **GitHub Actions** for automatic deployment to GitHub Pages.

### Automatic Deployment

Any push to the `main` branch triggers automatic deployment:
1. GitHub Actions workflow runs
2. Changes are built and deployed
3. Website updates in 1-2 minutes

### Manual Deployment

You can also trigger deployment manually from the Actions tab in the GitHub repository.

### Deployment Configuration

The deployment is configured in `.github/workflows/deploy.yml` and:
- Triggers on push to `main` branch
- Deploys all static files (HTML, CSS, JS, Media)
- Uses GitHub Pages for hosting
- Serves from `https://garychamp.github.io/MyMainWebsite`

For detailed deployment information, see [DEPLOYMENT.md](./DEPLOYMENT.md).

## 📄 File Descriptions

| File | Purpose |
|------|---------|
| `index.html` | Homepage with hero section and tagline |
| `about.html` | Personal information and professional background |
| `projects.html` | Portfolio showcase of development projects |
| `connect.html` | Contact information and social links |
| `stylesheet.css` | All CSS styling and responsive design |
| `javascript.js` | Interactive features (video controls, navigation, animations) |
| `DEPLOYMENT.md` | Deployment documentation and status |

## 🔄 Built with The Odin Project

This website was created as a learning project following [The Odin Project](https://www.theodinproject.com/) curriculum, applying lessons in:
- HTML semantic structure
- CSS layout and styling
- JavaScript DOM manipulation
- Responsive web design
- Git and GitHub workflows

## 🤝 Contributing

This is a personal portfolio project. However, if you have suggestions for improvements or find bugs, feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the MIT License. You are free to use, modify, and distribute this code, but please include a reference to the original repository.

## 📧 Contact

**Gary Hoare**

- **GitHub**: [@Garychamp](https://github.com/Garychamp)
- **Email**: [garyhoare18@gmail.com](mailto:garyhoare18@gmail.com)
- **Website**: [https://garychamp.github.io/MyMainWebsite](https://garychamp.github.io/MyMainWebsite)

---

**Last Updated:** 2026-03-16 14:11:11  
**Status:** Actively Maintained ✅

*Created following The Odin Project curriculum. Deployed to GitHub Pages with automatic CI/CD via GitHub Actions.*