# Eos Advisors – Static Site

A static HTML site for **Eos Advisors**, a boutique advisory firm based in Nepal ([eos.com.np](https://www.eos.com.np)).

---

## Quick Start

Serve the site locally with a single command, no install required:

```bash
npx serve static_site
```

Then open [http://localhost:3000](http://localhost:3000) in your browser.

> **Note:** You need [Node.js](https://nodejs.org/) (v14+) installed. `npx` ships with npm by default.

---

## Project Structure

```
eos-site/
├── static_site/               # Root of the static site
│   ├── index.html              # Homepage
│   ├── custom-fixes.css        # Custom CSS overrides
│   ├── site_map.json           # Site map / page index
│   │
│   ├── sectors/                # Sectors page
│   │   └── index.html
│   │
│   ├── services/               # Sector detail pages
│   │   ├── healthcare/
│   │   ├── hospitality-tourism/
│   │   ├── renewable-energy/
│   │   └── telecommunications/
│   │
│   ├── services-eos/           # Services overview page
│   │   └── index.html
│   │
│   ├── works/                  # Service detail pages
│   │   ├── private-business-consulting/
│   │   ├── equity-advisory/
│   │   ├── development-consulting/
│   │   └── investment-advisory/
│   │
│   ├── experience/             # Experience page
│   │   └── index.html
│   │
│   ├── our-eos/                # About Us section
│   │   ├── index.html
│   │   └── about-eos/
│   │
│   ├── contact-us/             # Contact page
│   │   └── index.html
│   │
│   ├── wp-content/             # WordPress-origin assets
│   │   ├── plugins/            # Plugin CSS/JS
│   │   ├── themes/             # Theme CSS/JS/images
│   │   └── uploads/            # Media uploads
│   │
│   └── wp-includes/            # WordPress core assets
│       ├── css/
│       └── js/
│
└── README.md
```

Each page directory contains its own `index.html`, so clean URLs work out of the box (e.g. `/contact-us` serves `contact-us/index.html`).
