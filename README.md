# Greater Portland Roleplay Website

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 📋 Overview

The official website for **Greater Portland Roleplay**, a premium Roblox roleplay community featuring realistic law enforcement, emergency services, and civilian operations in a detailed Maple County environment. This website serves as the central hub for community information, department details, and recruitment.

## 🌟 Features

### Core Functionality

- **Responsive Design**: Fully responsive layout optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional interface with smooth animations and transitions
- **Custom 404 Page**: Branded error page with helpful navigation and interactive elements
- **Department Showcase**: Dedicated pages for each law enforcement and emergency service department
- **Dynamic Logo Loading**: Automatic fallback system for department logos with emoji alternatives
- **Performance Optimized**: Fast loading times with optimized assets and efficient code structure

### Department Pages

- **Maine State Police (MSP)** - State-wide law enforcement operations
- **Greater Portland Law Enforcement (GPLE)** - Local community policing
- **Greater Portland Fire & EMS (GPFEMS)** - Emergency medical and fire services
- **Maine Warden Service (MWS)** - Fish and wildlife law enforcement
- **Maine Department of Marine Resources (MDMR)** - Marine patrol and fisheries
- **Greater Portland Civilian Operations (CivOps)** - Business and civilian roleplay

## 🚀 Technologies Used

- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Advanced styling with flexbox, grid, and custom properties
- **JavaScript**: Dynamic content loading and interactive functionality
- **Google Fonts**: Poppins font family for consistent typography
- **Modern Browser APIs**: Optimized for current web standards

## 📁 Project Structure

```
greaterportweb-main/
├── assets/
│   ├── bg.png                 # Main background image
│   ├── logo.svg              # Primary logo
│   └── logos/                # Department-specific logos
│       ├── civops-logo.png
│       ├── gpfems-logo.png
│       ├── gple-logo.png
│       ├── mdmr-logo.png
│       ├── msp-logo.png
│       └── mws-logo.png
├── departments/
│   ├── index.html            # Department overview page
│   ├── civops/
│   ├── gpfems/
│   ├── gple/
│   ├── mdmr/
│   ├── msp/
│   └── mws/
├── index.html                # Homepage
├── 404.html                  # Custom 404 error page
├── CNAME                     # GitHub Pages custom domain
└── README.md                 # Project documentation
```

## 🎨 Design System

### Color Palette

- **Primary Brand**: `#00004D` (Deep Navy Blue)
- **Text Light**: `#FFFFFF` (White)
- **Department Colors**:
  - MSP: `#4A90E2` (Blue)
  - GPLE: `#C2BDB8` (Silver)
  - GPFEMS: `#B80017` (Red)
  - MWS: `#63BE98` (Green)
  - MDMR: `#FFFFFF` (White)
  - CivOps: `#50B9C7` (Teal)

### Typography

- **Primary Font**: Poppins (Google Fonts)
- **Weights Used**: 400 (Regular), 600 (Semi-bold), 700 (Bold)

### Layout Principles

- **Mobile-First Design**: Responsive breakpoints at 768px
- **Modern CSS Grid**: Flexible department card layouts
- **Backdrop Blur Effects**: Glass-morphism design elements
- **Consistent Spacing**: 1rem-based spacing system

## 🛠️ Development

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor or IDE
- Basic knowledge of HTML, CSS, and JavaScript

### Local Development

1. Clone or download the repository
2. Open `index.html` in your preferred web browser
3. No build process required - pure HTML, CSS, and JavaScript

### File Organization

- All styles are embedded in `<style>` tags within each HTML file
- JavaScript functionality is embedded in `<script>` tags
- Assets are organized in the `/assets/` directory
- Each department has its own subdirectory with dedicated styling

## 🌐 Deployment

This website is designed for static hosting and can be deployed on:

- **GitHub Pages** (current deployment method)
- **Netlify**
- **Vercel**
- **AWS S3 + CloudFront**
- Any static file hosting service

The `CNAME` file is configured for custom domain deployment on GitHub Pages.

## 📱 Browser Compatibility

- **Chrome**: 90+
- **Firefox**: 88+
- **Safari**: 14+
- **Edge**: 90+
- **Mobile Browsers**: iOS Safari 14+, Chrome Mobile 90+

## 🔗 External Links

- **Discord Server**: `https://discord.gg/greaterport`
- **Roblox Community**: `https://www.roblox.com/communities/737918569/Greater-Portland-Roleplay`
- **CivOps Discord**: `https://discord.com/invite/d29Qy4tDXg`

## 📄 License

This project is licensed under the CC BY-NC License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

This is a community project for Greater Portland Roleplay. If you're a member of the community and would like to contribute:

1. Contact the development team through Discord
2. Follow the established coding standards and design patterns
3. Test thoroughly across different browsers and devices
4. Maintain the professional appearance and functionality

## 📞 Support

For technical issues or questions about the website:

- Join our [Discord Server](https://discord.gg/greaterport)
- Contact the development team directly through Discord

## 🙏 Credits & Acknowledgments

This project was made possible through the collaborative efforts of:

### **Development Team**

- **[@hyperphantom08](https://github.com/hyperphantom08)** - Design Implementation & Project Funding
- **[@leemo-jeemo](https://github.com/leemo-jeemo)** - Frontend Development & Development Manager

### **AI Development Assistance**

- **[Claude](https://claude.ai)** - Code optimization, documentation, and feature development
- **[ChatGPT](https://openai.com/chatgpt)** - Development consultation and problem-solving support

### **Special Thanks**

- Greater Portland Roleplay community members for feedback and testing
- All department leaders for providing content and requirements
- Beta testers who helped identify and resolve issues

## 🔄 Version History

- **v1.0**: Initial release with full department pages and responsive design
- **v2.0**: Publishing of the [departments](https://greaterport.org/departments) subpage
- **v3.0**: Major UI/UX overhaul with improved design system and enhanced department pages (consolidated v2.1.1-v2.1.3 fixes)
- **v3.1**: Added custom 404 error page with:
  - Branded design matching site aesthetics
  - Interactive elements and smooth animations
  - White accent color scheme with professional styling
  - Helpful navigation options (Return Home, Go Back, Get Help)
  - Mobile-responsive design with glass-morphism effects
  - Consistent navbar and footer matching other pages
- **v3.1.2**: Bug fixes and asset path corrections for hosted environments
- **v3.1.3**: Updated Maine Department of Marine Resources Discord invite link

---

**Greater Portland Roleplay** - _Professional. Realistic. Community-Driven._
