# Knot & Cross Collective — Official Website

Official website for **Knot & Cross Collective**, a fashion and creative collective based in Ocean View, Cape Town, South Africa.

**Live website:** https://knotandcross.co.za  
**Repository:** https://github.com/Dagg12/knotandcross

---

## Project Overview

This project is a responsive, single-page business and portfolio website created to present Knot & Cross Collective's brand, services, creative work, designer incubation platform, community programmes, and contact channels.

The website is designed for desktop, tablet, and mobile devices and is hosted directly from the repository using **GitHub Pages**.

The site does **not** use an ecommerce system, shopping cart, online payments, customer accounts, or a backend application.

---

## Technology Stack

This repository is a **static HTML/CSS/JavaScript website**.

| Technology / Service | Use |
| --- | --- |
| **HTML5** | Page structure and semantic content |
| **CSS3** | Layout, responsive design, typography, animations and visual styling |
| **Vanilla JavaScript** | Navigation, scroll animations, active-section navigation, form state and dynamic year |
| **Google Fonts** | Cormorant Garamond and DM Sans |
| **GitHub** | Source-code repository and version control |
| **GitHub Pages** | Website hosting and deployment |
| **FormSubmit** | Contact-form email forwarding |
| **WhatsApp** | Direct customer enquiry links |
| **Custom DNS** | `knotandcross.co.za` domain connection |

### No build system required

There is currently **no React, Vite, Node.js, npm, Tailwind CSS, or JavaScript framework** in this repository.

The website can be opened and maintained as a static website without installing packages or running a build command.

---

## Project Structure

```text
knotandcross/
│
├── assets/
│   ├── brand-mark.jpg
│   ├── cmt.png
│   ├── fashion-design.jpg
│   ├── designer-incubation.jpg
│   ├── community.jpg
│   ├── dress-red.jpg
│   ├── dress-yellow.jpg
│   ├── dress-white-lace.jpg
│   ├── dress-pink.jpg
│   ├── two-paths.jpg
│   ├── samantha-founder.jpg
│   └── annie-founder.jpg
│
├── css/
│   └── style.css
│
├── js/
│   └── main.js
│
├── index.html
├── 404.html
├── CNAME
├── robots.txt
├── sitemap.xml
├── LICENSE
└── README.md
```

The asset list may expand as new approved photography and project imagery are added.

---

## Website Sections

### Home
Introduces Knot & Cross Collective and presents the organisation's core offering.

### Services
Highlights:

- CMT Manufacturing
- Fashion Design & Sampling
- Designer Incubation
- Community Programmes

### Our Work
Showcases examples of fashion and garment work, including formalwear, occasion wear, bridal/special occasion pieces, and children's wear.

### Our Story
Explains the founders' journey, the meaning behind the Knot & Cross identity, and the collective's values.

### Founders
Introduces the two co-founders and their fashion design and technical expertise.

### Designer Incubation
Explains the platform's support for emerging designers through shared facilities, development, sampling, production support, and creative community.

### Community Programme
Presents the organisation's focus on practical sewing, pattern-making, garment-production skills, and community empowerment.

### Vision & Mission
Communicates the collective's long-term vision and mission.

### Contact
Provides email, WhatsApp, project enquiry, consultation, and workspace information.

---

## Design & Brand

The website uses an editorial fashion-inspired visual direction with:

- Deep wine/burgundy tones
- Cream and warm neutral backgrounds
- Rose and muted gold accents
- Serif editorial headings
- Clean sans-serif body typography
- Large fashion photography
- Responsive card and grid layouts
- Subtle hover and scroll-reveal animations

### Fonts

The stylesheet imports:

- **Cormorant Garamond** — editorial/display typography
- **DM Sans** — interface and body typography

These are loaded from Google Fonts.

---

## Responsive Design

The website includes responsive breakpoints for:

- Desktop
- Tablet
- Mobile
- Small mobile screens

The navigation changes into a mobile menu on smaller screens, while service cards, founder profiles, galleries, forms, and content sections adapt to available screen width.

---

## JavaScript Functionality

The website uses a lightweight vanilla JavaScript file at:

`js/main.js`

Current functionality includes:

- Mobile navigation toggle
- Automatic closing of the mobile navigation after selecting a link
- Scroll-based reveal animations
- Active navigation link based on the visible section
- Automatic copyright year
- Contact-form submission button state

No JavaScript framework is required.

---

## Contact Form

The project enquiry form is configured through **FormSubmit**.

Current endpoint:

```text
https://formsubmit.co/Design@knotandcross.co.za
```

The form is configured to forward website enquiries to:

**Design@knotandcross.co.za**

The first submission may require the recipient to complete FormSubmit's one-time activation/confirmation process.

FormSubmit is an external third-party service; the website itself does not contain a backend email server.

---

## WhatsApp

The website includes direct WhatsApp enquiry buttons using:

**+27 63 631 2998**

WhatsApp links are used for project enquiries, CMT enquiries, consultation requests, and general contact.

---

## Domain

The production domain is:

**https://knotandcross.co.za**

The repository contains a `CNAME` file configured for GitHub Pages:

```text
knotandcross.co.za
```

The domain DNS is managed externally and points the root domain to GitHub Pages.

---

## GitHub Pages Deployment

The site is deployed from the **main** branch using GitHub Pages.

### Deployment flow

```text
HTML / CSS / JavaScript
        │
        ▼
GitHub Repository
        │
        ▼
main branch
        │
        ▼
GitHub Pages
        │
        ▼
knotandcross.co.za
```

Because this is a static website, the repository root is published directly. There is no compilation or production build step.

To update the live website:

1. Modify the required files.
2. Test the changes locally.
3. Commit the changes.
4. Push the changes to `main`.
5. GitHub Pages publishes the updated files.

---

## Local Development

No package installation is required.

The simplest method is to open `index.html` in a browser.

For a local HTTP server, Python can be used if installed:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

This is optional. There is no required development server or build command for this project.

---

## SEO & Search Engine Files

The repository includes:

- `robots.txt`
- `sitemap.xml`
- Page metadata and description in `index.html`
- Custom page title
- Responsive viewport configuration
- Semantic section structure

These files support basic search-engine crawling and indexing.

---

## Maintenance

Future maintenance may include:

- Updating services
- Adding new portfolio work
- Updating photography
- Updating founder information
- Adding new community programmes
- Updating contact details
- Improving accessibility
- Improving SEO
- Optimising image sizes
- Updating third-party integrations
- Updating legal/privacy information

When editing the website, maintain the existing visual identity and responsive behaviour.

---

## Important Security & Content Notes

Do not commit the following to this repository:

- Passwords
- API keys
- Private access tokens
- Email passwords
- Hosting-panel credentials
- Database credentials
- Private client documents
- Confidential business information

The public repository should contain only information and assets intended to be part of the website/project.

---

## Intellectual Property & License

This project is licensed under the **Knot & Cross Collective Proprietary Software License**.

Copyright © 2026 Knot & Cross Collective. All rights reserved.

The repository's `LICENSE` file contains the applicable ownership, permitted-use, restriction, third-party-material, and portfolio-use terms.

Third-party services, libraries, fonts, images, and other externally sourced materials remain subject to their respective licenses and terms.

See [LICENSE](./LICENSE) for the full license.

---

## Client Information

**Knot & Cross Collective**  
Ocean View, Cape Town  
South Africa

**Email:** Design@knotandcross.co.za  
**WhatsApp:** +27 63 631 2998  
**Website:** https://knotandcross.co.za

---

## Project Status

**Status:** Live / Production

The website is currently deployed through GitHub Pages and served through the custom domain:

**https://knotandcross.co.za**

---

## Credits

Website design and development completed for:

**Knot & Cross Collective**

Cape Town, South Africa

© 2026 Knot & Cross Collective. All rights reserved.
