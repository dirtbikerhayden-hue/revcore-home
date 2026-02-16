# RevCore — Contractor Growth Agency Website

A premium, SEO-optimized multi-page website for RevCore, a growth systems agency serving home service contractors across the United States.

## Overview

RevCore helps contractors who refuse to compete on price generate qualified leads, book more in-home appointments, and close premium jobs on autopilot. This website serves as the primary digital presence for research and sales enablement.

## Site Structure

```
revcore-website/
├── index.html                          # Homepage
├── css/
│   └── styles.css                      # Global stylesheet
├── js/
│   └── main.js                         # Global JavaScript
├── pages/
│   ├── services.html                   # Services overview
│   ├── lead-generation.html            # Lead generation service detail
│   ├── seo-organic-traffic.html        # SEO & organic traffic service detail
│   ├── automation-systems.html         # Automation systems service detail
│   ├── how-it-works.html               # Process / how it works
│   ├── case-studies.html               # Case studies & results
│   ├── industries.html                 # Industries served
│   ├── about.html                      # About RevCore
│   ├── faq.html                        # Frequently asked questions
│   ├── blog.html                       # Blog listing
│   ├── contact.html                    # Contact / book a call
│   ├── privacy-policy.html             # Privacy policy
│   └── terms-of-service.html           # Terms of service
└── README.md
```

**Total: 14 pages** (1 homepage + 13 subpages)

## Features

- **Fully responsive** — Mobile-first design that works on all devices
- **SEO optimized** — Unique meta titles, descriptions, canonical URLs, Open Graph tags, and structured data (JSON-LD) on every page
- **Breadcrumb navigation** — For SEO and user experience on all subpages
- **Scroll animations** — IntersectionObserver-based fade-up, slide, and stagger reveals
- **Interactive FAQ** — Accordion with smooth open/close animations
- **Glassmorphic navigation** — Frosted glass effect with scroll-aware behavior
- **Dropdown menus** — Desktop navigation with hover-activated service dropdowns
- **Mobile menu** — Full slide-out menu with overlay
- **Internal linking** — Comprehensive cross-linking between all pages for SEO authority
- **Consistent design system** — Shared CSS variables, components, and patterns
- **Booking integration** — LeadConnector/GoHighLevel calendar embed on contact page
- **Performance optimized** — No frameworks, minimal dependencies, CSS-only animations

## Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, Grid, Flexbox, animations
- **Vanilla JavaScript** — IntersectionObserver, smooth scroll, mobile menu
- **Google Fonts** — Inter (400-900 weights)
- **No build tools required** — Pure static site, deploy anywhere

## Deployment

This is a static website with no build step required. Deploy to any static hosting:

### GitHub Pages
1. Push this repo to GitHub
2. Go to Settings → Pages
3. Select the branch and root folder
4. Your site will be live at `https://yourusername.github.io/revcore-website/`

### Netlify / Vercel
1. Connect your GitHub repository
2. No build command needed
3. Publish directory: `/` (root)

### Custom Domain
Update all canonical URLs in the `<head>` of each page from `https://www.revcore.io/` to your actual domain.

## Customization

### Colors
All colors are defined as CSS custom properties in `css/styles.css`:
```css
--accent: #ff7a1a;        /* Primary orange */
--bg-main: #ffffff;        /* White background */
--bg-light: #f8fafc;       /* Light gray sections */
--text-main: #0f172a;      /* Dark text */
--text-muted: #64748b;     /* Muted text */
```

### Booking Calendar
The contact page uses a LeadConnector embed. Replace the iframe `src` URL in `pages/contact.html` with your own booking widget URL.

### Logo
The logo is loaded from an external URL. Replace the `src` attribute on all `.nav-logo-icon` images across all pages with your own logo URL or local file path.

## License

All rights reserved. This website is proprietary to RevCore.
