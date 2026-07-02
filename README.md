# Krushna Tupe - Portfolio Website

A professional portfolio website built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design** - Works on mobile, tablet, and desktop
- **Smooth Animations** - Scroll-triggered animations and hover effects
- **Interactive Navigation** - Mobile-friendly hamburger menu
- **Contact Form** - Simple mailto integration that opens user's email client
- **Typing Effect** - Dynamic role cycling in hero section
- **Modern UI** - Clean, professional design with gradient backgrounds

## Setup Instructions

### Contact Form

The contact form uses a simple `mailto:` approach. When users submit the form:
1. The form data is captured (name, email, message)
2. The user's default email client opens with pre-filled subject and body
3. The user can then send the email directly to `krushnatupe11@gmail.com`

**No additional setup required** - this works out of the box with just HTML, CSS, and JavaScript.

### Run the Portfolio

**Option 1: Using Python (Recommended)**
```bash
python -m http.server 8000
```

**Option 2: Using Node.js**
```bash
npx http-server -p 8000
```

**Option 3: Using VS Code Live Server**
- Install the "Live Server" extension
- Right-click on `index.html`
- Select "Open with Live Server"

Then open your browser and navigate to `http://localhost:8000`

## File Structure

```
portfolio/
├── index.html      # Main HTML structure
├── style.css       # Styling and animations
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Customization

### Update Contact Information
Edit the following in `index.html`:
- Email: Line 263
- Phone: Line 268
- LinkedIn: Line 273

### Update Skills
Edit the skills section in `index.html` (lines 130-200)

### Update Experience
Edit the timeline section in `index.html` (lines 203-250)

### Update Projects
Edit the projects section in `index.html` (lines 253-285)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This portfolio is free to use for personal and commercial purposes.

---

**Built with ❤️ using HTML, CSS, and JavaScript**
