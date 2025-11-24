# Danish Political Analysis Presentation

## Overview

An interactive web presentation analyzing Danish democracy and voter behavior, focusing on the 2025 municipal elections. Built with the **Democratic Clarity** design system - a comprehensive framework balancing academic credibility with modern visual storytelling.

🔗 **[View Live Presentation](https://ston1ee.github.io/presentation-design-system/)**

---

## Project Purpose

This presentation was created for **Samfundsfag A** (Social Science A-level) at Danish STX gymnasium level, comparing:

- **København** (Copenhagen) - SF victory under Line Barfod
- **Næstved** - Venstre (V) victory

Using political science theories including:
- 🏛️ Michigan Model (Funnel of Causality)
- 📊 Downs' Rational Choice Theory
- 🌍 Lipset & Rokkan's Cleavage Theory
- 📰 McCombs & Shaw's Agenda-Setting Theory
- 🔄 Inglehart's Value Shift Theory

---

## Features

### Interactive Presentation
- ⌨️ **Keyboard Navigation** - Arrow keys, Space, Home, End
- 👆 **Touch Support** - Swipe left/right on mobile
- 🖱️ **Click Navigation** - Click left/right sides of screen
- 📊 **Animated Statistics** - Count-up effects on key data
- 🎨 **Hover Effects** - Interactive cards and buttons

### Design System
- 🎨 **Complete Color Palette** - Democratic Blue, Parliament Red, semantic colors
- 🔤 **Typography System** - Inter + Playfair Display
- 📦 **Component Library** - Cards, tables, tags, quotes, spectrum visualizer
- ♿ **WCAG AA Compliant** - Full accessibility support
- 📱 **Fully Responsive** - Mobile, tablet, desktop optimized

---

## Quick Start

### View Online
Simply visit: **[https://ston1ee.github.io/presentation-design-system/](https://ston1ee.github.io/presentation-design-system/)**

### Run Locally

```bash
# Clone the repository
git clone https://github.com/ston1ee/presentation-design-system.git

# Navigate to directory
cd presentation-design-system

# Open in browser
open index.html
# Or use a local server:
python -m http.server 8000
# Then visit: http://localhost:8000
```

---

## File Structure

```
presentation-design-system/
├── index.html              # Main presentation (14 slides)
├── DESIGN_SYSTEM.md        # Complete design system documentation
└── README.md               # This file
```

---

## Design System Documentation

For detailed design system specifications, see **[DESIGN_SYSTEM.md](./DESIGN_SYSTEM.md)**

Includes:
- 🎨 Color palette with hex codes
- 🔤 Typography scale and specifications
- 📊 Spacing system (4px base unit)
- 📦 Component library with code examples
- ✨ Animation & interaction patterns
- ♿ Accessibility standards (WCAG 2.1 AA)
- 📱 Responsive design breakpoints
- ✅ Do's and Don'ts for implementation

---

## Navigation Controls

### Keyboard
- **→ or Space** - Next slide
- **←** - Previous slide
- **Home** - First slide
- **End** - Last slide

### Mouse
- Click **right side** of screen - Next slide
- Click **left side** of screen - Previous slide
- Click **navigation arrows** - Navigate

### Touch (Mobile/Tablet)
- **Swipe left** - Next slide
- **Swipe right** - Previous slide

---

## Slide Overview

1. **Title Slide** - Introduction
2. **Kommunalt Selvstyre** - Municipal governance structure
3. **Case Study** - København & Næstved comparison
4. **Agenda-Setting Theory** - Media influence
5. **Social Media Impact** - Meta policy changes, TikTok campaigns
6. **Personalization** - Candidate-focused politics
7. **Rational Choice** - Downs' median voter theory
8. **Cleavage Theory** - Urban-rural divide
9. **Michigan Model** - Funnel of causality
10. **Dealignment** - Weakening party identification
11. **Folketingsvalg 2026** - Upcoming parliamentary election
12. **KV vs FV** - Municipal vs. parliamentary elections
13. **Theory Summary** - Comprehensive theoretical overview
14. **Conclusion** - Key findings and takeaways

---

## Technologies Used

- **HTML5** - Semantic structure
- **CSS3** - Custom properties, Grid, Flexbox, Animations
- **Vanilla JavaScript** - No frameworks, pure ES6+
- **Google Fonts** - Inter & Playfair Display
- **Intersection Observer API** - Scroll-triggered animations

---

## Browser Support

✅ **Fully Supported:**
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

⚠️ **Partial Support:**
- Safari 12-13 (limited CSS features)
- IE 11 (basic functionality only)

---

## Accessibility Features

- ♿ **WCAG 2.1 AA Compliant**
- ⌨️ **Full keyboard navigation**
- 👁️ **High contrast ratios** (4.5:1 minimum)
- 🗣️ **Screen reader support** with ARIA labels
- 🎯 **Focus indicators** on all interactive elements
- 📱 **Touch targets** minimum 44x44px

---

## Customization

### Change Colors
Edit CSS variables in `index.html`:

```css
:root {
  --democratic-blue: #1E3A8A;
  --parliament-red: #DC2626;
  /* ... other colors */
}
```

### Add Slides

```html
<div class="slide">
  <h2>Your Slide Title</h2>
  <div class="data-card">
    <p>Your content here</p>
  </div>
</div>
```

Update `totalSlides` variable in JavaScript section.

### Modify Typography

Change Google Fonts import or adjust type scale:

```css
h1 { font-size: 48px; /* Adjust as needed */ }
```

---

## Performance

- ⚡ **Lightweight** - ~40KB HTML (no external dependencies)
- 🚀 **Fast Load** - Inline styles, minimal requests
- 📱 **Mobile Optimized** - Responsive images, efficient animations
- ♻️ **No Build Process** - Works directly in browser

---

## License

This project is open source and available for educational purposes.

---

## Author

**Created by:** ston1ee  
**Course:** Samfundsfag A  
**Institution:** Danish STX Gymnasium  
**Date:** November 2025

---

## Acknowledgments

- Political theory frameworks from Campbell, Downs, Lipset, Rokkan, McCombs, Shaw, and Inglehart
- Danish political data from Altinget, DR, and Danske Kommuner
- Design inspiration from Material Design and Tailwind CSS
- Typography from Inter (Rasmus Andersson) and Playfair Display (Claus Eggers Sørensen)

---

## Contributing

Contributions welcome! Please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -am 'Add new feature'`)
4. Push to branch (`git push origin feature/improvement`)
5. Open a Pull Request

---

## Contact

- **GitHub:** [@ston1ee](https://github.com/ston1ee)
- **Repository:** [presentation-design-system](https://github.com/ston1ee/presentation-design-system)
- **Issues:** [Submit an issue](https://github.com/ston1ee/presentation-design-system/issues)

---

**Last Updated:** November 24, 2025  
**Version:** 1.0.0