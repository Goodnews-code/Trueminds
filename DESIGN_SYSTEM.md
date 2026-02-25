# Chuks Kitchen - Design System

This design system defines the core colors, typography, and reusable styles for the Chuks Kitchen project. These tokens ensure consistency across all pages and components.

## 1. Colors

We use a warm, appetizing color palette centered around orange, complemented by clean neutrals and distinct accents.

### Primary Colors
- **Brand Orange (Primary):** `#FF7A18` - Used for primary buttons, logos, active states, and highlights.
- **Brand Orange Hover:** `#ff922b` - Used for hover states on primary buttons.
- **Light Orange (Surface):** `#FFE1C4` - Used for icon backgrounds and subtle highlights.

### Neutral Colors
- **White (Background):** `#ffffff` - Primary page background and card backgrounds.
- **Off-White (Surface Light):** `#F9FAFB` - Used for input backgrounds and secondary surfaces.
- **Border Light:** `#F3F4F6` - Used for subtle borders and dividers.
- **Border Dark:** `#E5E7EB` - Used for input borders and stronger dividers.

### Text Colors
- **Text Base (Dark Gray):** `#1F2937` - Main text color for body copy and headings.
- **Text Black:** `#000000` - Used for strong titles and emphasized text.
- **Text Secondary:** `#4B5563` - Used for form labels and secondary information.
- **Text Muted:** `#6B7280` - Used for descriptions, placeholders, and subtle text.
- **Text Icon/Disabled:** `#9CA3AF` - Used for input icons and disabled states.

### Accent Colors
- **Action Blue:** `#1E88E5` - Used for links and outline buttons.
- **Action Blue Hover:** `#64B5F6` - Used for link hover states.
- **Footer Brown:** `#6D4C41` - Used for the main footer background.
- **Scroll Top Blue:** `#0081FE` - Used for the scroll-to-top button.
- **Scroll Top Blue Hover:** `#1A5FBA` - Used for the scroll-to-top button hover state.

---

## 2. Typography

The project utilizes Google Fonts to establish a distinct hierarchy.

### Font Families
- **Base Font (Body):** `"Inter", sans-serif` - Used for main body text, descriptions, and UI elements.
- **Heading Font:** `"Jost", sans-serif` - Used for section titles, hero headings, and footer headings.
- **Secondary/Utility Font:** `"Poppins", sans-serif` - Used for small links, bottom bars, and functional text.
- **Display/Logo Font:** `"Island Moments", cursive` - Used exclusively for the brand logo to give a handwritten, authentic feel.

### Font Weights
- **Regular:** `400`
- **Medium:** `500` (Default body weight)
- **Semi-Bold:** `600`
- **Bold:** `700`

---

## 3. Styles & Effects

### Border Radius (Corners)
- **Small (`8px`):** Inputs, standard buttons, dropdowns.
- **Medium (`10px` - `12px`):** Feature icons, search bars.
- **Large (`16px` - `20px`):** Cards, category containers, modals.
- **Circular (`50%`):** Scroll to top button, profile avatars.

### Shadows (Elevation)
- **Small Elevation:** `0 4px 12px rgba(0, 0, 0, 0.05)` - Used for secondary cards.
- **Medium Elevation:** `0 4px 15px rgba(0, 0, 0, 0.08)` - Used for primary feature/special cards.
- **Large Elevation:** `0 10px 25px rgba(0, 0, 0, 0.1)` - Used for floating elements like the main search bar.

---

## 4. CSS Variables (Implementation)

To apply this design system moving forward, you can add these CSS Custom Properties to the `:root` pseudo-class in your `css/style.css` file:

```css
:root {
  /* Colors */
  --color-primary: #FF7A18;
  --color-primary-hover: #ff922b;
  --color-primary-light: #FFE1C4;
  
  --color-bg-white: #ffffff;
  --color-bg-offwhite: #F9FAFB;
  
  --color-border-light: #F3F4F6;
  --color-border-dark: #E5E7EB;
  
  --color-text-base: #1F2937;
  --color-text-black: #000000;
  --color-text-secondary: #4B5563;
  --color-text-muted: #6B7280;
  --color-text-icon: #9CA3AF;
  
  --color-accent-blue: #1E88E5;
  --color-accent-blue-hover: #64B5F6;
  --color-footer-bg: #6D4C41;

  /* Typography */
  --font-family-base: "Inter", sans-serif;
  --font-family-heading: "Jost", sans-serif;
  --font-family-secondary: "Poppins", sans-serif;
  --font-family-logo: "Island Moments", cursive;

  /* Border Radius */
  --radius-sm: 8px;
  --radius-md: 12px;
  --radius-lg: 16px;
  --radius-xl: 20px;

  /* Shadows */
  --shadow-sm: 0 4px 12px rgba(0, 0, 0, 0.05);
  --shadow-md: 0 4px 15px rgba(0, 0, 0, 0.08);
  --shadow-lg: 0 10px 25px rgba(0, 0, 0, 0.1);
}
```
