# 🚀 e-golio - Coming Soon Page

A premium, elegant coming soon landing page for an upcoming ecommerce platform.

## ✨ Features

- **Modern Design** - Clean, minimalist aesthetic with luxury styling
- **Countdown Timer** - Dynamic countdown to launch date
- **Email Subscription** - Notify me form for launch announcements
- **Responsive Layout** - Fully responsive across all devices
- **Smooth Animations** - Elegant fade-up animations and transitions
- **Dark Mode Ready** - Built with CSS custom properties for theming
- **Accessibility** - Proper ARIA labels and keyboard navigation support

## 🎨 Design Highlights

- **Typography** - Cormorant Garamond (display), Sora (body), JetBrains Mono (monospace)
- **Color Palette** - Gold foil accents with heritage teal
- **Ambient Effects** - Subtle background gradients with grain overlay
- **Card Interactions** - Hover effects with smooth transitions

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, flexbox, grid, animations
- **Vanilla JavaScript** - No external dependencies
- **Google Fonts** - Typography

## 📦 Installation

Simply clone the repository and open `index.html` in your browser:

```bash
git clone https://github.com/HridoyVaraby/e-golio-comingsoon.git
cd e-golio-comingsoon
```

No build process required!

## 🚀 Usage

### Customizing Countdown Timer

Edit the countdown duration in `index.html`:

```javascript
const launchDate = new Date();
launchDate.setDate(launchDate.getDate() + 30); // Change 30 to your desired days
launchDate.setHours(0, 0, 0, 0);
```

### Updating Contact Info

Find and replace:
- `info@e-golio.com` in the contact link
- Social media URLs in the footer

### Email Form Integration

The current form simulates submission. To integrate with a real service:

```javascript
form.addEventListener('submit', function(e) {
  e.preventDefault();
  const email = emailInput.value;

  // Replace with your email service API (e.g., Formspree, EmailJS)
  fetch('YOUR_API_ENDPOINT', {
    method: 'POST',
    body: JSON.stringify({ email }),
    headers: { 'Content-Type': 'application/json' }
  })
  .then(response => {
    // Handle success
  });
});
```

## 📱 Preview

- Desktop: Full experience with 4-column countdown
- Tablet: Responsive with adjusted spacing
- Mobile: 2-column countdown, stacked layout

## ♿ Accessibility

- Proper heading hierarchy
- ARIA labels for interactive elements
- Keyboard navigation support
- Reduced motion support for users who prefer it
- High contrast text ratios

## 🎨 Customization

### Colors

Edit CSS custom properties in `:root`:

```css
--accent-foil: #b8860b;
--accent-heritage: #0d9488;
--bg-deep: #fafafa;
--text-primary: #1a1a1a;
```

### Fonts

Replace Google Fonts URLs with your preferred fonts in the `<head>` section.

## 📄 License

This project is proprietary. All rights reserved.

## 👤 Author

**Hridoy Varaby**
- GitHub: [@HridoyVaraby](https://github.com/HridoyVaraby)

## 🌐 Links

- Website: [www.e-golio.com](https://www.e-golio.com)
- Email: [info@e-golio.com](mailto:info@e-golio.com)

---

Made with ❤️ for the e-glio launch
