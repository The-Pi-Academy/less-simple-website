# Less Simple Website

A more advanced web project from The Pi Academy, building upon basic HTML/CSS concepts with enhanced functionality and modern web development practices.

## 📋 Project Overview

This project represents an evolution from simple static websites to a more feature-rich web application. It demonstrates intermediate web development concepts including responsive design, interactive JavaScript functionality, and proper project organization.

## 🏗️ Project Structure

```
less-simple-website/
├── hosting/                    # Hosting configuration and deployment files
├── web/                       # Main web application directory
│   ├── assets/               # Static assets
│   │   ├── css/             # Stylesheets
│   │   ├── js/              # JavaScript files
│   │   └── images/          # Image assets
│   ├── index.html           # Main homepage
│   └── [other HTML files]   # Additional pages
├── .gitignore              # Git ignore rules
└── README.md               # Project documentation
```

## 🚀 Features

Based on the project structure, this website likely includes:

- **Responsive Design**: Modern CSS layouts that work across different devices
- **Interactive Elements**: JavaScript-powered user interactions
- **Multi-page Navigation**: Organized content across multiple HTML pages
- **Optimized Assets**: Proper organization of CSS, JavaScript, and images
- **Deployment Ready**: Hosting configuration for easy deployment

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Advanced styling, layouts, and responsive design
- **JavaScript**: Interactive functionality and dynamic content
- **Static Hosting**: Configured for deployment on various hosting platforms

## 📦 Installation & Setup

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor or IDE (VS Code, Sublime Text, etc.)
- Basic understanding of HTML, CSS, and JavaScript

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/The-Pi-Academy/less-simple-website.git
   cd less-simple-website
   ```

2. **Navigate to the web directory**
   ```bash
   cd web
   ```

3. **Open in browser**
   - Open `index.html` directly in your browser, or
   - Use a local development server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

4. **Access the website**
   - Direct file: `file:///path/to/web/index.html`
   - Local server: `http://localhost:8000`

## 🌐 Deployment

### GitHub Pages
The project includes hosting configuration for easy deployment:

1. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to Pages section
   - Select source branch (usually `main` or `gh-pages`)
   - Choose `/web` folder if applicable

2. **Custom Domain** (Optional)
   - Add a `CNAME` file to the web directory
   - Configure DNS settings with your domain provider

### Other Hosting Platforms
This project can be deployed on various static hosting services:
- **Netlify**: Drag and drop the `web` folder
- **Vercel**: Connect your GitHub repository
- **Firebase Hosting**: Use Firebase CLI
- **Surge.sh**: Deploy with `surge web/`

## 📚 Learning Objectives

This project helps students understand:

1. **Project Organization**: Proper file and folder structure
2. **Responsive Web Design**: Creating layouts that work on all devices
3. **JavaScript Integration**: Adding interactivity to web pages
4. **Asset Management**: Organizing and optimizing web resources
5. **Deployment Process**: Publishing websites to the internet
6. **Version Control**: Using Git for project management

## 🎯 Key Concepts Demonstrated

- **Semantic HTML**: Using appropriate HTML elements for content structure
- **CSS Flexbox/Grid**: Modern layout techniques
- **JavaScript DOM Manipulation**: Dynamic content updates
- **Mobile-First Design**: Responsive design principles
- **Performance Optimization**: Efficient loading and rendering
- **Accessibility**: Web standards for inclusive design

## 🔧 Development Guidelines

### Code Style
- Use consistent indentation (2 or 4 spaces)
- Follow semantic HTML practices
- Organize CSS with logical grouping
- Comment complex JavaScript functions
- Use meaningful variable and function names

### File Organization
- Keep HTML files in the root of `web/`
- Place all CSS files in `assets/css/`
- Store JavaScript files in `assets/js/`
- Organize images in `assets/images/`

### Best Practices
- Validate HTML and CSS
- Test across different browsers
- Optimize images for web
- Minimize HTTP requests
- Use external stylesheets and scripts

## 🚀 Advanced Features

Depending on the specific implementation, this project may include:

- **CSS Animations**: Smooth transitions and effects
- **JavaScript Frameworks**: Integration with libraries like jQuery
- **Form Handling**: Contact forms or user input processing
- **API Integration**: Fetching data from external services
- **Local Storage**: Saving user preferences
- **Progressive Enhancement**: Graceful degradation for older browsers

## 🤝 Contributing

This is an educational project from The Pi Academy. To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 Assignment Ideas

Students can extend this project by:

- Adding new pages with consistent navigation
- Implementing a contact form with validation
- Creating a photo gallery with lightbox functionality
- Adding a blog section with multiple posts
- Integrating social media links and sharing buttons
- Implementing dark/light theme toggle
- Adding search functionality
- Creating a responsive navigation menu

## 🐛 Troubleshooting

### Common Issues

**CSS not loading**
- Check file paths in HTML link tags
- Ensure CSS files are in the correct directory
- Verify no syntax errors in CSS files

**JavaScript not working**
- Check browser console for errors
- Ensure script tags are properly placed
- Verify JavaScript file paths

**Images not displaying**
- Check image file paths
- Ensure images are in the assets/images directory
- Verify image file extensions match

## 📖 Resources

- [MDN Web Docs](https://developer.mozilla.org/) - Comprehensive web development documentation
- [W3C HTML Validator](https://validator.w3.org/) - HTML validation tool
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) - CSS validation tool
- [Can I Use](https://caniuse.com/) - Browser compatibility reference
- [Google PageSpeed Insights](https://pagespeed.web.dev/) - Performance analysis

## 📄 License

This project is created for educational purposes as part of The Pi Academy curriculum. Please refer to the repository license for specific terms.

## 🙋‍♀️ Support

For questions about this project:
- Open an issue in the GitHub repository
- Contact The Pi Academy instructors
- Review the learning materials provided in class

---

**The Pi Academy** - Empowering students with practical web development skills
