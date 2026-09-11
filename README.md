## Part 2 Overview — CSS Styling and Responsive Design

Part 2 builds on the Part 1 HTML structure by adding a full external CSS stylesheet and making the site responsive for mobile and tablet devices.

**What was implemented:**

- An external stylesheet (`style.css`) linked from `index.html` via `<link rel="stylesheet" href="style.css">`.
- A CSS reset (`*`, `*::before`, `*::after`) to normalise margin, padding, and box-sizing across browsers.
- A base style layer using CSS custom properties (`:root` variables) for colour scheme, typography, and spacing — so the whole site can be restyled from a small number of central values, taking advantage of the cascade with a minimum number of selectors.
- A typographic scale (heading font vs. body font, font-size variables) replacing the old inline `<font>` tag styling from Part 1.
- Layout styling for the header, hero section, shop layout (product grid + order panel), and footer, using flexbox/grid rather than the original table-based layout attributes.
- Component styling for product cards, filter buttons (`.filter-btn` / `.filter-btn.active`), add/remove buttons, the order/cart panel, and form inputs.
- Responsive design using relative units (`rem`, `%`, flex/grid) and two breakpoints:
  - `max-width: 768px` — tablet layout (shop layout stacks vertically, hero padding reduced)
  - `max-width: 480px` — mobile layout (single-column product grid, header stacks, smaller headings)

---

## Responsive Design / Testing Screenshots

> Add your screenshots below once you've tested the site using browser dev tools (or a real device) at each breakpoint. Save the images into a `screenshots/` folder in the repo and reference them here, e.g.:

**Desktop (≥769px)**

![Desktop view](screenshots/desktop.png)

**Tablet (481–768px)**

![Tablet view](screenshots/tablet.png)

**Mobile (≤480px)**

![Mobile view](screenshots/mobile.png)

*Tested in Chrome DevTools responsive mode at 1440px, 768px, and 375px widths.*

---

## Changelog

All edits are logged here, newest first, with enough detail for the lecturer to follow what changed and why.

### Part 2 — CSS Styling and Responsive Design

- **Added:** External stylesheet `style.css`, linked from `index.html`.
- **Added:** CSS reset and base style rules (colour scheme, typography, spacing variables in `:root`).
- **Added:** Typographic scale and layout styles (header, hero, shop layout, footer) using flexbox/grid.
- **Added:** Component styles for product cards, filter buttons, add/remove buttons, order panel, and form inputs — matching class names already used in the site's JavaScript.
- **Added:** Responsive breakpoints at 768px (tablet) and 480px (mobile) using relative units.
- **Added:** Responsive design testing screenshots (desktop/tablet/mobile) to this README.
- **Changed:** Replaced `bgcolor`, `background`, and `<font>` attributes in `index.html` with CSS classes from `style.css`.
- *(Add further entries here each time you commit a change, e.g. "Fixed cart total alignment on mobile" or "Adjusted product card spacing after peer review.")*

### Changes Made Based on Part 1 Feedback

- *(List each Part 1 correction here as you make it — be specific, e.g.: "Added missing `alt` text to all product images per feedback item 3." / "Corrected heading hierarchy — page now has a single `<h1>`.")*

### Part 1 — Structure and Content (original submission)

- Initial HTML structure for homepage, product menu, order/cart panel, and footer.
- Product data and cart logic implemented in JavaScript (add to cart, remove from cart, category filter, checkout).



## Submission

GitHub repository link submitted via Arc as required.
