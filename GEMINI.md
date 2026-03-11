# Project Context: Orisif Medical Laboratory

## 1. Project Vision
Transform the "Karma" e-commerce template into a professional landing page and virtual catalog for **Orisif**, a medical laboratory company.

## 2. Branding & Visual Identity
- **Primary Color:** `#01766E` (Medical Teal). Replaced all instances of `#ffba00` and `#ff6c00`.
- **Logos:**
  - **Color:** `img/OrisifColor.png` (Used as Favicon and in Sticky/Mobile Navbar).
  - **White:** `img/OrisifWhite.png` (Used in Transparent Hero Navbar).
  - **Size:** Constrained to `max-width: 120px` in the header.
- **Hero Background:** `img/backgroundOrisif.png` with a 50% black overlay (`rgba(0,0,0,0.5)`).

## 3. UI/UX Modifications

### Header & Navigation
- **Transparent State:** Initially transparent with white navigation links.
- **Sticky State:** Transitions to white background with `#222222` text.
- **Interactions:** Added `text-decoration: underline` for hover and focus states on nav links.
- **Logo Toggling:** Implemented CSS logic to swap between `white-logo` and `color-logo` based on the `.is-sticky` class.

### Hero Banner (Index Page)
- **Structure:** Removed the Owl Carousel slider. It is now a **static hero section**.
- **Content:**
  - Removed the sneaker/product image.
  - Set all banner text to white (`#fff`) for visibility against the overlay.
  - **CTA Button:** Changed "Add to Bag" to "Let's be in touch" (pointing to `contact.html`).

## 4. Current Content State
- **Reversion:** While initial medical terminology was applied (e.g., "Medical Tests" instead of "Shop Category"), these changes were **reverted** back to the original template text at the user's request to ensure all internal links remained functional during the design phase.

## 5. Technical Notes
- **Styling:** Changes applied to both `scss/theme/` files and the compiled `css/main.css`.
- **Scripts:** `js/jquery.sticky.js` handles the `.is-sticky` class toggle used for the navbar transition.
- **Favicon:** Updated globally to `img/OrisifColor.png`.
