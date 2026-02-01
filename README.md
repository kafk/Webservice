# Darko Apps Website

A modern, playful website for Darko Apps - an iOS app and web development studio based in Croatia.

## Features

### Interactive Pricing Calculators
- **iOS App Calculator** - Configure app features and get instant pricing (starting at €2,499)
- **Website Calculator** - Build custom website quotes (starting at €999)
- Toggle-based feature selection with live price updates
- Bundle discounts (5% for 3+ features, 10% for 5+ features)
- Timeline estimates based on selected features

### Contact Form Modal
- Beautiful popup form triggered by CTA buttons
- Fields: Name, Email, Project Type, Budget Range, Message
- Success confirmation with animation
- Closes on backdrop click or Escape key

### FAQ Section
- 8 common questions with accordion-style answers
- Covers pricing, timelines, revisions, support, payments, and more
- Smooth open/close animations

### Design
- Playful, colorful design with custom CSS variables
- Animated floating background shapes
- Responsive layout for all screen sizes
- Google Fonts: Nunito & Fredoka
- Sticky navigation bar

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Flexbox, Grid, animations
- **Vanilla JavaScript** - No dependencies

## Sections

1. **Hero** - Main headline with CTAs
2. **Calculator Selector** - Choose between App or Website pricing
3. **App Calculator** - iOS app feature builder
4. **Website Calculator** - Website feature builder
5. **Fun Facts** - Quick stats with animations
6. **Services** - Design, App Dev, Web Dev, Support
7. **FAQ** - Common questions answered
8. **CTA** - Final call-to-action
9. **Footer** - Links and copyright

## Getting Started

Simply open `index.html` in a browser - no build process required.

```bash
# Clone the repository
git clone https://github.com/kafk/Webservice.git

# Open in browser
open index.html
```

## Customization

### Colors
Edit the CSS variables in `:root` to change the color scheme:

```css
:root {
    --purple: #7c3aed;
    --pink: #ec4899;
    --orange: #f97316;
    --yellow: #facc15;
    /* ... */
}
```

### Pricing
Update the `data-price` attributes on option items and base price variables in JavaScript:

```javascript
const appBasePrice = 2499;
const websiteBasePrice = 999;
```

### Contact Form
The form currently logs to console. To send emails, integrate with:
- [Formspree](https://formspree.io/)
- [Netlify Forms](https://www.netlify.com/products/forms/)
- Your own backend API

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2025 Darko Apps. All rights reserved.

---

Made with ❤️ in Croatia
