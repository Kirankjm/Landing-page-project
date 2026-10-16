# TechNova Landing Page

A modern, fully responsive landing page for a fictional technology company called TechNova. This project demonstrates professional web development practices using HTML, CSS, and JavaScript.

## Features

### Core Features
- **Responsive Design**: Fully responsive layout that works seamlessly on mobile, tablet, and desktop devices
- **Smooth Scrolling**: Smooth scroll navigation with section highlight animation
- **Scroll-to-Top Button**: Convenient button that appears after scrolling down
- **Parallax Effect**: Subtle parallax effect on hero section
- **Mobile Hamburger Menu**: Functional mobile navigation menu with smooth transitions and body scroll lock
- **Scroll Animations**: Multiple animation types (fade-in, slide-in, scale-in) triggered as elements enter viewport
- **Staggered Animations**: Cards and sections animate with staggered delays for visual appeal
- **Interactive Elements**: Hover effects on buttons, cards, and navigation links
- **Button Ripple Effect**: Click ripple animation on CTA and submit buttons
- **Header Scroll Effect**: Dynamic header shadow and background on scroll
- **Active Navigation**: Navigation links highlight based on current scroll position
- **Contact Form**: Functional contact form with validation

### Sections
1. **Header**: Fixed navigation bar with logo and menu links
2. **Hero Section**: Eye-catching hero with headline, subtext, and CTA button
3. **About Section**: Company information and mission
4. **Services Section**: Grid of 6 service cards with icons and descriptions
5. **Testimonials Section**: 3 client testimonials with author information
6. **Contact Section**: Contact information and a functional contact form
7. **Footer**: Quick links, social media links, and copyright information

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox and Grid layouts
- **JavaScript (ES6+)**: Interactive functionality and animations
- **No Frameworks**: Pure vanilla JavaScript and CSS for optimal performance

## Project Structure

```
landing-page-project/
├── index.html          # Main HTML file with all sections
├── styles.css          # Complete styling with responsive design
├── script.js           # JavaScript for interactivity and animations
└── README.md           # Project documentation
```

## Getting Started

### Prerequisites
- A modern web browser (Chrome,Edge)
- A code editor (optional, for customization)

### Installation

1. Clone or download this repository to your local machine
2. Navigate to the project directory
3. Open `index.html` in your web browser

### Running Locally

Simply open the `index.html` file in any modern web browser. No build process or server required.

For a better development experience, you can use a local server:

**Using Python:**
```bash
python -m http.server 8000
```

**Using Node.js (with serve):**
```bash
npx serve -s . -l 8000
```

**Using VS Code Live Server:**
- Install the Live Server extension
- Right-click on `index.html`
- Select "Open with Live Server"

## Features Breakdown

### Responsive Design
- Mobile-first approach with comprehensive media queries
- Breakpoints at 1024px (tablet), 768px (mobile), 480px (small mobile), and 360px (extra small mobile)
- Flexible grid layouts that adapt to screen size
- Optimized typography and spacing for different devices
- Fluid font sizes using relative units
- Touch-friendly interface on mobile devices

### Smooth Scrolling & Animations
- Smooth scroll navigation with header offset
- Section highlight animation on navigation click
- Scroll-to-top button with smooth animation
- Parallax effect on hero section
- Intersection Observer for performance-efficient scroll animations
- Multiple animation types: fadeInUp, slideInLeft, slideInRight, scaleIn
- Staggered animation delays for visual appeal
- Button ripple effect on click
- Header shadow and background change on scroll
- Active navigation link highlighting

### Mobile Menu
- Hamburger icon with smooth transform animation
- Full-screen overlay on mobile devices
- Auto-closes on link click
- Auto-closes when clicking outside menu
- Body scroll lock when menu is open
- Smooth slide-in transition

### Mobile Menu
- Hamburger icon that transforms to X when active
- Smooth slide-in animation
- Auto-closes when clicking navigation links
- Full-screen overlay on mobile devices

### Animations
- Hero section fade-in on page load
- Scroll-triggered fade-in animations for sections and cards
- Hover effects on buttons (lift and shadow)
- Card hover effects with smooth transitions
- Navigation link underline animation

### Contact Form
- Input validation (name, email, message)
- Form submission handling
- Success/error feedback
- Reset after successful submission

## Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
- Primary color: `#2563eb` (blue)
- Hero gradient: `#667eea` to `#764ba2`
- Background colors for sections

### Modifying Content
Edit the HTML in `index.html`:
- Company name and logo
- Hero headline and subtext
- Service cards
- Testimonials
- Contact information

### Adding New Sections
1. Add a new `<section>` in `index.html`
2. Add corresponding CSS in `styles.css`
3. Update navigation links if needed

## Deployment

### GitHub Pages
1. Create a new GitHub repository named `landing-page-project`
2. Upload all project files
3. Go to repository Settings > Pages
4. Select the main branch as source
5. Your site will be available at `https://yourusername.github.io/landing-page-project/`

### Vercel
1. Sign up at [vercel.com](https://vercel.com)
2. Install Vercel CLI: `npm i -g vercel`
3. Run `vercel` in the project directory
4. Follow the prompts to deploy

## Browser Compatibility

- Chrome (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized CSS with no external dependencies
- Minimal JavaScript for fast load times
- No heavy frameworks or libraries
- Responsive images and optimized animations

## Future Enhancements

Potential improvements for future versions:
- Add dark mode toggle
- Implement blog section
- Add portfolio/projects showcase
- Integrate with backend API for form submission
- Add analytics tracking
- Implement lazy loading for images
- Add accessibility features (ARIA labels, keyboard navigation)

## License

This project is open source and available for educational purposes.

## Author

Created as a demonstration of modern web development practices.

## Support

For questions or issues, please open an issue in the GitHub repository.

---

**Note**: This is a fictional company created for demonstration purposes. Any resemblance to real companies is coincidental.
