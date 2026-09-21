# WEDE5020 — Portfolio of Evidence, Part 1

**Student:** Garnette
**Module:** WEDE5020 — Web Development
**Submission:** Part 1 (research, planning and basic HTML structure)
**Client (Proposal 1, built site):** Tapstone Plumbing Solutions (Pty) Ltd — Randburg and Benoni, Gauteng
**Client (Proposal 2, paper only):** Second Chance Animal Haven — NPO 087-654-NPO, Krugersdorp

> Both organisations are **fictional teaching cases**. All prices, statistics, regulatory
> requirements, hosting costs and legal references are taken from real, published South
> African sources, listed under **References** below.

---

## 1. What is in this repository

| Path | Description |
| --- | --- |
| `index.html` | Homepage — hero image, introduction, call to action, service summary, water-loss statistics, testimonials |
| `about.html` | Company history, milestone timeline, mission and vision, team, registrations and cover |
| `services.html` | Six service lines with indicative pricing and a supplied-and-installed price table |
| `enquiry.html` | Structured quote-request form (service, suburb, property type, branch, urgency, POPIA consent) |
| `contact.html` | Two locations, two embedded maps, trading-hours tables and a general contact form |
| `css/style.css` | Single stylesheet — design tokens plus eleven commented sections |
| `js/main.js` | Mobile navigation toggle, footer year, form-validation feedback |
| `images/` | Photographic assets (`hero-plumber.jpg`, `team-photo.jpg`, `leak-detection.jpg`, `solar-geyser.jpg`) |
| `documents/` | Sitemaps, low-fidelity wireframes and the Part 1 proposal document |
| `content/` | Source text and copy drafts |
| `README.md` | This file |

### Naming conventions

* All file and folder names are lowercase and hyphen-separated (`hero-plumber.jpg`, `wireframe-1-homepage.png`).
* One page per top-level task, named after its purpose (`enquiry.html`, not `form2.html`).
* Images are named subject-first so they sort meaningfully.
* CSS classes use a block-element pattern (`.service-card`, `.service-card__price`).

---

## 2. Sitemap

```
index.html (Home)
├── about.html (About Us)        → Our story · Milestones · Mission & vision · Team · Credentials
├── services.html (Services)     → Emergency · Leak detection · Geysers & solar ·
│                                   Drains & CCTV · Bathrooms · Compliance certificates
├── enquiry.html (Enquiry)       → Quote request form
└── contact.html (Contact)       → Randburg head office (map) · Benoni branch (map) · General form
```

Visual versions: `documents/sitemap-tapstone.png` and `documents/sitemap-second-chance.png`.

Wireframes: `documents/wireframe-1-homepage.png`, `wireframe-2-inner-page.png`,
`wireframe-3-enquiry.png`, `wireframe-4-contact.png`, `wireframe-5-npo-homepage.png`.

---

## 3. Technical notes

* Semantic HTML5 — `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<address>`, `<footer>`; `lang="en-ZA"`.
* Mobile-first CSS with breakpoints at 960px and 760px; custom properties for the palette and type scale.
* Vanilla JavaScript only (ES6). No frameworks, no build step — every page opens directly in a browser.
* Accessibility: skip-to-content link, `aria-expanded` on the navigation toggle, `aria-live` form messages,
  visible focus states, alternative text on every image, WCAG 2.1 AA contrast, `prefers-reduced-motion` support.
* Maps are lazily loaded OpenStreetMap `embed.html` iframes, so no API key or paid tier is required.
* Forms use `action="#"` in Part 1 — the server-side mail handler is scheduled for Part 3.
* Every HTML, CSS and JS file is commented to explain structure and intent (brief item 5.6).

### Cross-browser testing

Tested at 1280×900 and 390×840 in Chromium, and reviewed in Chrome, Edge, Firefox and Safari.
Markup validated with the W3C Markup Validation Service.

### Colour and type

| Role | Hex |
| --- | --- |
| Navy (primary) | `#0F2A3D` |
| Deep navy | `#0A1E2D` |
| Water teal | `#1E7A8C` |
| Copper accent | `#C4703A` |
| Sand | `#F6F4F0` |
| Ink (body text) | `#1B2733` |

Headings: Bricolage Grotesque (600/800). Body: Satoshi (400/500/700). Both are open-licensed.

---

## 4. Asset and licensing credits

* **Typefaces** — Bricolage Grotesque via Google Fonts (SIL Open Font License 1.1) and Satoshi via Fontshare, both free for commercial use.
* **Maps** — OpenStreetMap, © OpenStreetMap contributors, Open Database License.
* **Photographs** — generated for this project and therefore free of third-party rights. Where stock imagery is substituted later, Unsplash-licensed images will be used and credited.
* **Icons** — inline SVG drawn for this project; no icon font is loaded.

---

## 5. References

Harvard style. All sources accessed 27 August 2026. These are the references used in the
Part 1 proposal document (`documents/WEDE5020-Part1-Project-Proposals.docx`) together with the
general sources consulted while completing Part 1.

Afrihost. (2026) *Domain registration and pricing.* Available at: https://www.afrihost.com/domains

Bunnypants. (2026) *How much does web design cost in South Africa? 2026 price guide.* Available at: https://www.bunnypants.co.za/how-much-does-web-design-cost-in-south-africa/

Department of Social Development. (n.d.) *About the NPO Directorate.* Available at: https://www.dsd.gov.za/index.php/npo/about-us

Google. (n.d.) *Google Fonts: frequently asked questions.* Available at: https://fonts.google.com/faq

Institute of Plumbing South Africa. (n.d.) *Industry news: unregistered plumbers and the informal sector.* Available at: https://www.iopsa.org/news/10752826

Leaflet. (n.d.) *Leaflet: an open-source JavaScript library for mobile-friendly interactive maps.* Available at: https://leafletjs.com/

MyBroadband. (2025) *The cheapest .CO.ZA domain prices in South Africa.* Available at: https://mybroadband.co.za/news/cloud-hosting/589029-cheapest-co-za-domain-prices.html

New Perspective Studio. (2026) *What is the cost of creating a website in South Africa?* Available at: https://www.newperspectivestudio.co.za/wp/what-is-the-cost-of-creating-a-website-in-south-africa/

Our City News. (2025) *Joburg by numbers 2025.* Available at: https://ourcitynews.co.za/joburg-by-numbers-2025/

Plumbing Industry Registration Board. (n.d.) *Registration requirements.* Available at: https://www.pirb.co.za/registration/

Plumbing Industry Registration Board. (n.d.) *What is the plumber's code of conduct?* Available at: https://www.pirb.co.za/Support/what-is-the-plumbers-code-of-conduct/

Republic of South Africa. (1997) *Nonprofit Organisations Act 71 of 1997.* Available at: https://www.gov.za/documents/nonprofit-organisations-act

SIL International. (n.d.) *SIL Open Font License, version 1.1.* Available at: https://github.com/googlefonts/googlefonts-project-template/blob/main/OFL.txt

SME South Africa. (n.d.) *Xneelo web hosting review and pricing.* Available at: https://smesouthafrica.co.za/brands/xneelo-web-hosting-review/

South African Revenue Service. (n.d.) *Application for Section 18A approval.* Available at: https://www.sars.gov.za/businesses-and-employers/tax-exempt-institutions/application-for-section-18a/

Switch2OSM. (n.d.) *Getting started with Leaflet.* Available at: https://switch2osm.org/using-tiles/getting-started-with-leaflet/

Unsplash. (n.d.) *Unsplash licence.* Available at: https://unsplash.com/license

Water Research Commission. (2008) *The state of plumbing in South Africa, Report 1702/1/08.* Available at: https://www.wrc.org.za/wp-content/uploads/mdocs/1702-1-081.pdf

World Wide Web Consortium. (n.d.) *Markup validation service.* Available at: https://validator.w3.org/

---

# WEDE5020 � Portfolio of Evidence, Part 1 & Part 2

**Student:** Garnette
**Module:** WEDE5020 � Web Development
**Submission:** Part 2 (responsive styling refinements, accessibility pass, component enhancements)
**Client (Proposal 1, built site):** Tapstone Plumbing Solutions (Pty) Ltd � Randburg and Benoni, Gauteng
**Client (Proposal 2, paper only):** Second Chance Animal Haven � NPO 087-654-NPO, Krugersdorp

> Both organisations are **fictional teaching cases**. All prices, statistics, regulatory
> requirements, hosting costs and legal references are taken from real, published South
> African sources, listed under **References** below.

---

## 1. What is in this repository

| Path | Description |
| --- | --- |
| `index.html` | Homepage � hero section, introduction, call to action, service summary, water-loss statistics, emergency badge |
| `about.html` | Company history, milestone timeline, mission & vision, team profile cards, credentials & insurance data table |
| `services.html` | Six service lines with indicative pricing and a supplied-and-installed price table |
| `enquiry.html` | Structured quote-request form (service selection, suburb, property type, branch, urgency, POPIA consent) |
| `contact.html` | Two physical locations, two embedded OpenStreetMap maps, trading-hours tables and general contact form |
| `css/style.css` | Single consolidated stylesheet � design tokens, base resets, global components, page components, and banner contrast fixes |
| `js/main.js` | Mobile navigation toggle, dynamic footer year update, form-validation feedback |
| `images/` | Photographic assets (`hero-plumber.jpg`, `team-photo.jpg`, `leak-detection.jpg`, `solar-geyser.jpg`) |
| `documents/` | Sitemaps, low-fidelity wireframe diagrams, and Part 1 proposal documents |
| `content/` | Source text and copy drafts |
| `README.md` | This documentation file |

### Naming conventions

* All file and folder names are lowercase and hyphen-separated (`hero-plumber.jpg`, `wireframe-1-homepage.png`).
* One page per top-level task, named after its purpose (`enquiry.html`, not `form2.html`).
* Images are named subject-first so they sort meaningfully in media directories.
* CSS classes follow a consistent block-element structure (`.team-member`, `.team-member .role`, `.table-responsive`).

---

## 2. Sitemap
