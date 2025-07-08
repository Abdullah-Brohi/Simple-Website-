# TechCorp Website

A modern, responsive multi-page website built with pure HTML, CSS, and JavaScript. This project showcases a professional business website with clean design, smooth animations, and interactive elements.

## 🚀 Features

- **Multi-page Navigation**: 4 main pages (Home, About, Services, Contact)
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean design with gradient backgrounds and card layouts
- **Interactive Elements**: Smooth animations, hover effects, and transitions
- **Working Contact Form**: Form validation with success messages
- **Single Page Application**: Fast navigation without page reloads
- **Cross-browser Compatible**: Works on all modern browsers
- **No Dependencies**: Pure HTML, CSS, and JavaScript - no frameworks required

## 📋 Table of Contents

- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Features Overview](#features-overview)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Demo

![Website Preview](https://via.placeholder.com/800x400/667eea/ffffff?text=TechCorp+Website+Preview)

*Replace this placeholder with actual screenshots of your website*

## 🛠️ Installation

### Method 1: Direct Download
1. Download the `index.html` file
2. Open it in your web browser
3. That's it! The website will load immediately

### Method 2: Clone Repository
```bash
git clone https://github.com/yourusername/techcorp-website.git
cd techcorp-website
```

### Method 3: Local Web Server
```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have it installed)
npx serve .
```

Then open `http://localhost:8000` in your browser.

## 💻 Usage

### Running the Website
1. Open `index.html` in any modern web browser
2. Navigate between pages using the navigation menu
3. Fill out the contact form to see form validation in action
4. Resize your browser window to see the responsive design

### Customization
The website is built with clean, well-commented code that's easy to modify:

- **Colors**: Update the CSS variables in the `<style>` section
- **Content**: Edit the HTML content within each page section
- **Styling**: Modify the CSS classes to change the appearance
- **Functionality**: Add or modify JavaScript functions as needed

## 📁 Project Structure

```
techcorp-website/
│
├── index.html          # Main HTML file containing all pages
├── README.md           # This file
└── assets/            # (Optional) Folder for images/media
    └── screenshots/   # Website screenshots
```

## 🎨 Features Overview

### Home Page
- Hero section with call-to-action button
- Feature cards highlighting key benefits
- Smooth animations and transitions

### About Page
- Company story and mission
- Core values and team information
- Professional card-based layout

### Services Page
- Detailed service offerings
- Feature lists for each service
- Organized grid layout

### Contact Page
- Contact information cards
- Working contact form with validation
- Success message feedback

### Technical Features
- **Responsive Navigation**: Mobile-friendly menu
- **Form Validation**: Client-side form validation
- **Smooth Animations**: CSS keyframes and transitions
- **Interactive Elements**: Hover effects and button animations
- **Modern Design**: Gradient backgrounds and card layouts

## 🎨 Customization Guide

### Changing Colors
Update the gradient colors in the CSS:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Adding New Pages
1. Create a new page div with class `page`
2. Add navigation link in the header
3. Update the `showPage()` function
4. Add page title to the `titles` object

### Modifying Content
- Edit HTML content directly in the page sections
- Update form fields in the contact form
- Modify card content and styling

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🔧 Development

### Prerequisites
- Any modern web browser
- Text editor (VS Code, Sublime Text, etc.)

### Making Changes
1. Edit the `index.html` file
2. Refresh your browser to see changes
3. Test on different screen sizes
4. Ensure all interactive elements work properly

### Adding Features
- **New animations**: Add CSS keyframes
- **More pages**: Follow the existing page structure
- **Enhanced forms**: Add more validation or fields
- **External APIs**: Integrate with third-party services

## 📄 Code Overview

### HTML Structure
- Semantic HTML5 elements
- Clean, organized page sections
- Accessible form elements

### CSS Features
- Flexbox and Grid layouts
- CSS animations and transitions
- Responsive design with media queries
- Modern styling techniques

### JavaScript Functionality
- Page navigation system
- Form validation and submission
- Interactive animations
- Event handling

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 🙏 Acknowledgments

- Design inspiration from modern web design trends
- Color palette from contemporary UI design
- Icons and styling concepts from Material Design principles


**Made with ❤️ for the open source community**
