# WEDE5020 Website Project - Tapstone Plumbing Solutions

**Student:** Nqobani Ngwenya  
**Student Number:** ST10457588  
**Subject:** WEDE5020 - Website Development  
**Project:** Part 1 & Part 2 Complete  
**Date:** September 2026

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Target Organisation](#target-organisation)
3. [File Structure](#file-structure)
4. [Features](#features)
5. [Setup Instructions](#setup-instructions)
6. [Responsive Design](#responsive-design)
7. [Browser Testing](#browser-testing)
8. [Screenshot Evidence](#screenshot-evidence)
9. [References](#references)

---

## Project Overview

This project delivers a professional, responsive website for **Tapstone Plumbing Solutions (Pty) Ltd**, a plumbing contractor operating in Randburg and Benoni, Gauteng.

The website includes five fully functional pages:
- **Home** - Hero section, service highlights, trust indicators, CTAs
- **About Us** - Company history, mission/vision, team profiles, certifications
- **Services** - Detailed service descriptions (emergency repairs, geysers, renovations, compliance)
- **Enquiry** - Quote request form with service selection and validation
- **Contact** - Contact details, two location maps, contact form

---

## Target Organisation

**Name:** Tapstone Plumbing Solutions (Pty) Ltd  
**Industry:** Plumbing Services  
**Locations:** Randburg and Benoni, Gauteng, South Africa  
**Established:** 2018  
**Registration:** PIRB License No: 12345

### Why This Organisation?

Tapstone represents a typical small South African trades business that needs a professional online presence to:
- Generate qualified leads through enquiry forms
- Establish credibility with PIRB certification display
- Provide service information to reduce phone enquiry time
- Improve local SEO visibility for plumbing searches

---

## File Structure

```
wede5020-complete/
│
├── index.html              # Homepage
├── about.html              # About Us page
├── services.html           # Services page
├── enquiry.html            # Enquiry/Quote form page
├── contact.html            # Contact page with maps
│
├── css/
│   └── styles.css          # Main stylesheet (24KB)
│
├── js/
│   └── main.js             # JavaScript for interactivity
│
├── images/                 # Image assets folder
├── documents/              # Proposal documents
└── content/                # Text content files
```

---

## Features

### HTML5
- Semantic markup (`<header>`, `<nav>`, `<main>`, `<footer>`, `<article>`, `<section>`)
- Proper heading hierarchy (H1 → H2 → H3)
- Accessible forms with labels and ARIA attributes
- Breadcrumb navigation on interior pages
- Meta descriptions for SEO

### CSS3
- **CSS Reset** for cross-browser consistency
- **CSS Custom Properties** (variables) for colours, fonts, spacing
- **Flexbox** for header, navigation, and component layouts
- **CSS Grid** for services, team, values, and footer layouts
- **Responsive Typography** using rem units
- **Hover, Focus, Active states** for interactive elements
- **Transitions and transforms** for smooth animations
- **Media Queries** for tablet (1024px) and mobile (768px, 480px)

### JavaScript (ES6+)
- Mobile menu toggle functionality
- Dynamic year in footer
- Form validation and submission handling
- Smooth scroll for anchor links
- Active navigation link highlighting
- Form input validation on blur
- Scroll-triggered animations with IntersectionObserver
- Console welcome message

---

## Setup Instructions

### To View Locally

1. Download and extract the repository zip file
2. Navigate to the `wede5020-complete` folder
3. Double-click `index.html` to open in your default browser
4. Navigate through all pages using the menu

### File Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server required - runs directly from file system
- Internet connection required for Google Fonts

---

## Responsive Design

### Breakpoints

| Breakpoint | Width | Layout Changes |
|------------|-------|----------------|
| Desktop | 1025px+ | 4-column grids, full navigation |
| Tablet | 769px - 1024px | 2-column grids, condensed spacing |
| Mobile | 481px - 768px | Single-column grids, hamburger menu |
| Small Mobile | ≤480px | Reduced font sizes, minimal padding |

### Mobile-First Features

- Hamburger menu replaces horizontal navigation
- All grids collapse to single column
- Buttons stack vertically on CTAs
- Form rows become single-column
- Font sizes scale down for readability
- Touch-friendly button sizes (minimum 44px height)

### Responsive Units Used

- **rem** for font sizes (accessibility - respects user browser settings)
- **%** for widths (fluid layouts)
- **vw/vh** avoided for better control
- **em** for component-specific spacing

---

## Browser Testing

### Tested Browsers

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 127+ | ✓ Fully Tested |
| Firefox | 128+ | ✓ Tested |
| Safari | 17+ | ✓ Tested |
| Edge | 127+ | ✓ Tested |

### Testing Methodology

1. Open each page in browser
2. Test all navigation links
3. Test mobile menu toggle
4. Test form validation
5. Resize window to test responsive breakpoints
6. Verify all interactive elements work

### Known Limitations

- Forms do not send emails (requires Part 3 backend)
- Maps are OpenStreetMap embeds (static, not interactive)
- Images are placeholders (to be replaced with actual photos)

---

## Screenshot Evidence

### Desktop (1280px)

All five pages tested at 1280px width:

1. **Homepage** - Hero section, 4-column service grid, trust indicators
2. **About Us** - Two-column layout, team grid, certifications
3. **Services** - Service detail sections with alternating layouts
4. **Enquiry** - Two-column form with info sidebar
5. **Contact** - Contact details with two location maps

### Tablet (768px)

- Navigation converts to hamburger menu
- Grids reduce to 2 columns
- Spacing reduced proportionally

### Mobile (390px)

- Single-column layout throughout
- Hamburger menu active
- Buttons full-width
- Form inputs stack vertically
- Footer columns stack

### How to Capture Your Own Screenshots

1. Open Chrome DevTools (F12)
2. Click device toggle (Ctrl+Shift+M)
3. Select device or enter custom dimensions
4. Use three-dot menu → "Capture screenshot"

---

## References

### Pricing Research

1. Afrihost. (2026). Domain Registration Pricing. Available at: https://www.afrihost.com/domains

2. Xneelo. (2026). Web Hosting Review. SME South Africa. Available at: https://smesouthafrica.co.za/brands/xneelo-web-hosting-review/

3. New Perspective Studio. (2025). What is the Cost of Creating a Website in South Africa? Available at: https://www.newperspectivestudio.co.za/wp/what-is-the-cost-of-creating-a-website-in-south-africa/

### Industry Standards

4. Water Research Commission. (2018). Compliance of Plumbing Products in South Africa. Report No. 1702-1-081.

5. Plumbing Industry Registration Board (PIRB). (2026). Registration Requirements. Available at: https://www.pirb.co.za/registration/

### Technical Documentation

6. MDN Web Docs. (2026). CSS Layout. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout

7. Web Content Accessibility Guidelines (WCAG) 2.1. (2018). W3C Recommendation.

---

## Part 3 Preview

The following enhancements are planned for Part 3:

- Backend form handling (PHP/Node.js)
- Email notifications for enquiries
- Image gallery with lightbox
- Google Analytics integration
- Performance optimisation (image compression, minification)
- Deployment to live hosting

---

## Contact

For questions about this project, contact:

**Nqobani Ngwenya**  
Student Number: ST10457588  
Email: st10457588@student.email

---

**Last Updated:** 18 September 2026
