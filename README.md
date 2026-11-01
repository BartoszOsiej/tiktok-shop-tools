# TikTok Shop Tools

**Vise — TikTok Shop profit calculator & market intelligence.**  
Know your real profit. Built by Hartwell Labs.

![TikTok Shop Tools Screenshot](https://via.placeholder.com/800x400/0a0e14/ffffff?text=TikTok+Shop+Tools+Dashboard)

---

## 📊 Core Features

- **Profit Calculator**: Real-time TikTok Shop profit calculation with fee breakdown
- **Market Intelligence**: Data-driven insights for TikTok Shop sellers
- **Fee Transparency**: Complete breakdown of fees, commissions, and profit margins
- **Responsive Design**: Works seamlessly from mobile to desktop

---

## 🎨 Design & Animations

The application features subtle but polished animations:

- **Sticky header** with blur effect and color scheme switcher (dark/light mode)
- **Smooth page transitions** using `scroll-behavior: smooth`
- **Hover micro-interactions** on buttons and interactive elements
- **Animated gradient accents** on the calculator card and hero section
- **Staggered entrance animations** for content sections
- **SVG stroke animations** in the logo

Key animation details:

```css
/* Example: Header sticky transition */
header {
  transition: background .3s ease, border-color .3s ease;
}

/* Calculator card hover */
.calculator-card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,.4);
}

/* Eyebrow badge entrance */
.hero .eyebrow {
  animation: fadeInUp .5s ease-out;
}

/* SVG logo animation */
.logo svg path,
.logo svg polyline {
  stroke: var(--accent);
  stroke-dasharray: 20;
  stroke-dashoffset: 20;
  animation: drawLogo .8s ease-out forwards;
}
```

---

## 🚀 Quick Start

```bash
# No installation needed - pure HTML/CSS/JS
open index.html
```

Or serve locally:

```bash
npx serve
# or
python -m http.server
# Then visit http://localhost:8080
```

---

## 📦 Tech Stack

- **HTML5** with semantic markup
- **CSS3** with CSS variables, media queries, and subtle animations
- **Inter** font from Google Fonts
- **Responsive** design with mobile-first approach
- **No JavaScript runtime** needed - pure static site

---

## 📱 Responsive Breakpoints

| Width | Layout Changes |
| ----- | -------------- |
| > 720px | Full navigation menu displayed |
| 640px | Calculator card reduced padding |
| < 640px | Navigation hidden, simplified layout |

---

## 🔧 Development

```bash
# View the project structure
ls -la

# No build step - edit index.html and styles directly
# CSS is inline in <style> tag, no preprocessor needed
```

---

## 📄 License

MIT License - see LICENSE file for details.

---

## 🤝 Connect

- **Built by**: Hartwell Labs
- **Project**: Vise - TikTok Shop profit intelligence
- **Related**: [hartwell-labs.pl](https://hartwell-labs.pl)

---

## 🙏 Credits

- **Fonts**: Google Fonts - Inter
- **Icons**: Custom SVG logo
- **Inspiration**: E-commerce analytics tools, TikShop seller community