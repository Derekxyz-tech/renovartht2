# RenovArt - Professional Renovation Services Website

A modern, responsive, and professional website for RenovArt, a premier renovation firm based in Port au Prince, Haiti. This website showcases their services, portfolio, and provides a way for potential clients to get in touch.

## Features

- **Fully Responsive Design**: Looks great on all devices (desktops, tablets, and mobile phones)
- **Modern UI/UX**: Clean and professional design with smooth animations
- **Service Showcase**: Highlighting various renovation services
- **Portfolio Gallery**: Display of past projects with filtering capabilities
- **Testimonials**: Client testimonials to build trust
- **Contact Form**: Easy way for potential clients to get in touch
- **SEO Optimized**: Built with search engine optimization in mind
- **Fast Loading**: Optimized for performance

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- JavaScript (Vanilla JS)
- Font Awesome Icons
- Google Fonts

## Setup and Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/renovart-ht2.git
   cd renovart-ht2
   ```

2. **Open in Browser**
   - Simply open the `index.html` file in your preferred web browser
   - Or use a local server like Live Server in VS Code

3. **Customization**
   - Update the content in `index.html` to match your business details
   - Replace the images in the `images` folder with your own
   - Customize colors and styles in `css/style.css`
   - Update the contact form submission in `js/main.js` to point to your backend

## File Structure

```
renovart-ht2/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── main.js         # Main JavaScript file
└── images/             # Directory for all images
    ├── logo.png        # Company logo
    ├── hero-bg.jpg     # Hero section background
    ├── about.jpg       # About section image
    ├── portfolio/      # Portfolio images
    └── clients/        # Client images for testimonials
```

## Customization

### Colors
You can customize the color scheme by modifying these CSS variables in the `:root` selector in `css/style.css`:

```css
:root {
    --primary-color: #e67e22;    /* Main brand color (orange) */
    --secondary-color: #2c3e50;  /* Dark blue for headings */
    --accent-color: #e74c3c;     /* Red for accents and hover states */
    --text-color: #333;          /* Main text color */
    --light-gray: #f8f9fa;       /* Light background color */
    --dark-gray: #343a40;        /* Dark background color */
    --white: #ffffff;            /* White color */
}
```

### Fonts
The website uses Poppins from Google Fonts. You can change this by updating the font import in the `<head>` section of `index.html` and the `font-family` property in the `body` CSS rule.

### Images
Replace the placeholder images in the `images` folder with your own. Make sure to maintain the same file names or update the references in the HTML.

## SEO Optimization

The website includes the following SEO optimizations:
- Semantic HTML5 markup
- Meta descriptions and viewport settings
- Alt text for images
- Structured data (Schema.org) can be added as needed
- Mobile-friendly design
- Fast loading times

## Contact Form

The contact form is currently set up with a simple JavaScript alert on submission. To make it functional, you'll need to:

1. Set up a backend service (like Formspree, Netlify Forms, or a custom PHP/Node.js server)
2. Update the form's `action` attribute and add any required fields
3. Update the form submission handler in `js/main.js`

## Browser Support

The website is tested and works on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile Safari and Chrome for iOS and Android

## License

This project is open source and available under the [MIT License](LICENSE).

## Credits

- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for the Poppins font
- [Unsplash](https://unsplash.com/) for placeholder images (replace with your own)

## Support

For support, please contact your web developer or open an issue in the GitHub repository.

---

© 2025 RenovArt. All rights reserved.
