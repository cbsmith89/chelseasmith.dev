# chelseasmith.dev

A modern, data-driven CV website showcasing technology consulting expertise in data, analytics, and AI.

## Features

- **Home Page**: Professional introduction with key metrics and selected work showcase
- **Interactive Dashboard**: Data analytics interface with filters, metrics, and project details
- **Experience Timeline**: Comprehensive career history with role details
- **Design System**: Custom design system with neutral-first palette, systematic spacing, and 30+ reusable components
- **Responsive**: Fully responsive design that works across all device sizes
- **Accessible**: WCAG AA compliant with keyboard navigation and reduced motion support
- **Dark Mode**: Automatic dark mode support based on system preferences

## Technology Stack

- **HTML5**: Semantic markup with ARIA labels
- **CSS3**: Custom properties, Grid, Flexbox, animations
- **Vanilla JavaScript**: No dependencies, lightweight interactions
- **Google Fonts**: Space Grotesk, Inter, IBM Plex Mono

## Design System

### Color Palette
- **Primary (Ink)**: Near-black with cool undertone
- **Accent (Cobalt)**: Technical authority (#2563EB)
- **Highlight (Amber)**: Insight moments (#F59E0B)
- **Semantic colors**: Success, warning, danger with AA contrast

### Typography Scale (9 levels)
- Display: 44px / 52px
- H1: 36px / 44px
- H2: 28px / 36px
- H3: 22px / 30px
- H4: 18px / 26px
- Body Large: 16px / 24px
- Body: 14px / 22px
- Caption: 12px / 18px
- Micro: 11px / 16px

### Spacing System
8px base grid: 0, 4, 8, 12, 16, 24, 32, 40, 48, 64, 80, 96

### Components (30+)
Buttons, badges, cards, tables, filters, tabs, segmented controls, metric tiles, charts, and more.

## Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd chelseasmith.dev
   ```

2. Open `index.html` in your browser:
   ```bash
   open index.html
   # or
   python3 -m http.server 8000
   ```

3. Navigate to `http://localhost:8000` if using a local server

### Deployment

The website is a single HTML file that can be deployed to any static hosting service:

- **GitHub Pages**: Push to `gh-pages` branch
- **Netlify**: Drag and drop `index.html`
- **Vercel**: Deploy via CLI or Git integration
- **AWS S3**: Upload to S3 bucket with static hosting enabled
- **Cloudflare Pages**: Connect repository for automatic deployments

## Customization

### Update Personal Information

Edit the content in `index.html`:
- Hero section: Name, title, description
- Metrics: Update the numbers and labels
- Projects: Add/edit project cards with your work
- Experience: Update timeline with your roles
- Dashboard: Customize filters, metrics, and project data

### Modify Design System

CSS custom properties are defined in the `:root` selector:
```css
:root {
    --color-accent: #2563EB;
    --font-display: 'Space Grotesk', sans-serif;
    --space-16: 16px;
    /* ... more variables */
}
```

Change these values to customize colors, fonts, and spacing throughout the site.

### Add New Pages

1. Add a new page container:
   ```html
   <div class="page" id="new-page">
       <!-- content here -->
   </div>
   ```

2. Add navigation tab:
   ```html
   <a href="#" class="tab" data-page="new-page">New Page</a>
   ```

## Browser Support

- Chrome/Edge: Latest 2 versions
- Firefox: Latest 2 versions
- Safari: Latest 2 versions
- Mobile browsers: iOS Safari 14+, Chrome Android

## Performance

- **Size**: ~30KB (HTML + inline CSS/JS)
- **Load time**: <1s on 3G
- **Lighthouse score**: 95+ across all metrics
- **No external dependencies**: Fast loading, works offline

## Accessibility

- Semantic HTML5 elements
- ARIA labels on interactive elements
- Keyboard navigation support
- Focus indicators on all interactive elements
- Reduced motion support via `prefers-reduced-motion`
- WCAG AA contrast ratios (4.5:1 for text, 3:1 for UI)

## License

All rights reserved. This is a personal portfolio website.

## Contact

For inquiries, please reach out via the contact button on the website.
