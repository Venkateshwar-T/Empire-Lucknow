# EMPIRE — Lucknow
### Contemporary Indian Dining & Late Bar

> An editorial, high-end digital experience for **EMPIRE**, a contemporary dining establishment and vinyl speakeasy located in Gomti Nagar, Lucknow, Uttar Pradesh.

---

## Overview

EMPIRE combines Awadhi culinary heritage, contemporary open fire, and cinematic hospitality into an immersive digital storefront. Designed with an editorial, magazine-style layout—rejecting generic restaurant templates—it alternates between deep midnight (`#0B0E14`) and warm ivory (`#F7F4EE`) sections, dramatic high-contrast typography, and fluid micro-interactions.

## Features

- **Editorial Split Hero**: Asymmetric typography paired with framed culinary photography, metadata badges, and seamless booking triggers.
- **Interactive Reservation Engine**:
  - Desktop: Centered modal with glassmorphism backdrop.
  - Mobile: Smooth bottom sheet with drag affordance, interactive date/time chips, party-size counter, and frontend reference confirmation (`#EMP-XXXX`).
- **Live Culinary Search & Filtering**:
  - Instant client-side search across 18 signature dishes and drinks with keyword matching (e.g., *biryani*, *paneer*, *smoked*, *tandoor*).
  - Dedicated mobile search mode with integrated close icon and smooth transitions.
- **Curated Menu Spread**: 6 distinct culinary categories (Small Plates, Tandoor, Mains, Rice & Biryani, Desserts, Drinks) with prices, tags, and tasting notes.
- **After Dark Tasting Timeline**: Interactive 4-phase sequence (`18:00`, `19:30`, `21:00`, `23:00`) showcasing the restaurant's transition into late-night vinyl bar service.
- **Editorial Review Marquee**: Infinite smooth marquee with stylized Google rating badge (`4.8 / 5`, `1,248 reviews`) and zero horizontal viewport overflow.
- **Interactive Gomti Nagar Vector Map**: Custom dark-mode SVG map tracing the Gomti River curve, Lohia Path, and Shaheed Path with a pulsing copper location pin.
- **Mobile-First Responsive Layout**:
  - Hamburger drawer navigation with numbered sections (01–07).
  - Fixed 4-tab bottom navigation (Home, Menu, Search, Reviews) with active scroll spy.
  - Fine-tuned proportions and zero horizontal scroll blowouts across all screen widths.

## Tech Stack

- **HTML5**: Semantic, accessible markup.
- **CSS3**: Custom design system, CSS variables, CSS Grid, Flexbox, responsive typography with `clamp()`.
- **Vanilla JavaScript**: Pure JS without libraries, frameworks, or bundlers.
- **Typography**: Bodoni Moda, Cormorant Garamond, Plus Jakarta Sans, Space Grotesk (via Google Fonts).

## Getting Started

No build step, Node.js, or package manager required. Simply open `index.html` in any modern web browser:

```bash
# Option 1: Double-click index.html or open via terminal
start index.html

# Option 2: Serve using any static server (e.g. Python)
python -m http.server 8000
```

---

*Fictional client presentation and demonstration website.*
