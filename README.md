# Vamshikrishna - Portfolio Website

A clean, modern, and responsive personal portfolio website showcasing my skills and projects as a Full Stack Developer.

## 🌟 Features

- **Modern Design**: Clean, minimalist interface with smooth animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: CSS animations and scroll-triggered effects
- **Interactive Elements**: Hover effects, parallax scrolling, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Resume Download**: Integrated resume download functionality
- **Performance Optimized**: Fast loading with efficient CSS and JavaScript

## 🚀 Live Demo

[View Live Portfolio](https://your-portfolio-url.com) <!-- Replace with your actual URL -->

## 📱 Screenshots

![Portfolio Screenshot](screenshots/portfolio-desktop.png) <!-- Add your screenshots -->

## 🛠️ Built With

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with flexbox and grid
- **Vanilla JavaScript** - Interactive functionality
- **Responsive Design** - Mobile-first approach

### Key Technologies & Features Used:

- CSS Grid & Flexbox for layouts
- CSS Animations & Transitions
- Intersection Observer API for scroll animations
- Smooth scrolling navigation
- Backdrop filters for modern glass effects
- CSS Custom Properties (variables)

## 📋 Sections

1. **Hero Section** - Introduction with call-to-action
2. **About Me** - Personal introduction and background
3. **Skills** - Technical skills organized by category
4. **Projects** - Showcase of 6 full-stack projects
5. **Resume** - Downloadable resume section
6. **Contact** - Contact information and form

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Basic knowledge of HTML/CSS/JavaScript (for customization)

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/portfolio-website.git
```

2. Navigate to the project directory
```bash
cd portfolio-website
```

3. Open `index.html` in your browser or serve with a local server
```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

4. Open your browser and visit `http://localhost:8000`

## 🎨 Customization

### Personal Information

Update the following sections with your information:

1. **Hero Section**: Change name and tagline
2. **About Section**: Update personal description
3. **Skills Section**: Modify skill categories and technologies
4. **Projects Section**: Add your actual projects
5. **Contact Section**: Update email and phone number

### Colors & Styling

The website uses CSS custom properties for easy theme customization. Main colors:

```css
:root {
  --primary-color: #2563eb;
  --secondary-color: #667eea;
  --text-color: #333;
  --bg-color: #f8fafc;
}
```

### Adding Projects

To add a new project, copy the project card structure:

```html
<div class="project-card">
    <div class="project-image">🎯</div>
    <div class="project-content">
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-description">Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link">Live Demo</a>
            <a href="#" class="project-link">GitHub</a>
        </div>
    </div>
</div>
```

## 📁 Project Structure

```
portfolio-website/
│
├── index.html          # Main HTML file
├── README.md           # Project documentation
├── screenshots/        # Portfolio screenshots
│   └── portfolio-desktop.png
└── assets/            # Additional assets (if any)
    ├── images/
    └── documents/
        └── resume.pdf
```

## 🔧 Configuration

### Contact Form

The contact form currently uses JavaScript for basic validation and simulation. To make it functional:

1. **Backend Integration**: Connect to a backend service (Node.js, PHP, etc.)
2. **Email Service**: Integrate with services like EmailJS, Formspree, or Netlify Forms
3. **Database**: Store messages in a database if needed

Example with EmailJS:
```javascript
// Add EmailJS script to head
<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>

// Update handleSubmit function
function handleSubmit(event) {
    event.preventDefault();
    emailjs.sendForm('your_service_id', 'your_template_id', event.target)
        .then(() => {
            alert('Message sent successfully!');
        });
}
```

### Resume Download

Replace the `generateResume()` function with actual file download:

```javascript
function generateResume() {
    const link = document.createElement('a');
    link.href = 'assets/documents/resume.pdf';
    link.download = 'Vamshikrishna_Resume.pdf';
    link.click();
}

## 📞 Contact

**Vamshikrishna**
- Phone: [9441692994](tel:9441692994)
- Email: vamshikrishna558@gmail.com


