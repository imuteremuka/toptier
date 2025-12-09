# Top-Tier Solutions Car Wash Website

A modern, responsive website for Top-Tier Solutions car care business in Cape Town, South Africa. This website showcases the car wash services, pricing, and contact information.

## Features

- **Responsive Design**: Works on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean and professional design with smooth animations
- **Service Showcase**: Display various car wash and detailing services
- **Pricing Section**: Clear pricing for different service packages
- **Contact Form**: Easy way for customers to get in touch
- **Interactive Elements**: Hover effects, smooth scrolling, and mobile navigation

## Technologies Used

- HTML5
- CSS3 (with CSS Variables for easy theming)
- JavaScript (Vanilla JS - no dependencies)
- Font Awesome Icons
- Google Fonts (implicitly through system fonts)

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone [repository-url]
   ```

2. Navigate to the project directory:
   ```bash
   cd AquaCarWash
   ```

3. Open `index.html` in your web browser to view the website locally.

## File Structure

```
AquaCarWash/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Main stylesheet
├── js/
│   └── script.js      # JavaScript functionality
└── images/            # Website images (create this folder and add your images)
```

## Adding Images

1. Create an `images` folder in the project root.
2. Add the following images to the `images` folder:
   - `hero-bg.jpg` - Hero section background
   - `about-bg.jpg` - About section background
   - Any additional service or gallery images

## Customization

### Colors

You can easily customize the color scheme by updating the CSS variables in the `:root` selector in `css/style.css`:

```css
:root {
    --primary-color: #3498db;      /* Main brand color */
    --secondary-color: #2c3e50;    /* Dark color for text and accents */
    --accent-color: #e74c3c;       /* Accent color for special elements */
    --light-color: #ecf0f1;        /* Light background color */
    --dark-color: #2c3e50;         /* Dark text color */
    --text-color: #333;            /* Main text color */
    --text-light: #7f8c8d;         /* Light text color */
}
```

### Content

Update the content in `index.html` to match your business details, services, and pricing.

## Browser Support

The website is tested and works on all modern browsers including:
- Google Chrome
- Mozilla Firefox
- Safari
- Microsoft Edge
- Mobile Safari (iOS)
- Chrome for Android

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For any questions or support, please contact [your-email@example.com](mailto:your-email@example.com)
