---
name: Artisanal Excellence
colors:
  surface: '#faf9f7'
  surface-dim: '#dadad8'
  surface-bright: '#faf9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeec'
  surface-container-high: '#e9e8e6'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1b'
  on-surface-variant: '#44474c'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#75777d'
  outline-variant: '#c5c6cd'
  surface-tint: '#545f72'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#111c2c'
  on-primary-container: '#798498'
  inverse-primary: '#bcc7dd'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#171c20'
  on-tertiary-container: '#7f848a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e3f9'
  primary-fixed-dim: '#bcc7dd'
  on-primary-fixed: '#111c2c'
  on-primary-fixed-variant: '#3d4759'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#dfe3e9'
  tertiary-fixed-dim: '#c2c7cd'
  on-tertiary-fixed: '#171c20'
  on-tertiary-fixed-variant: '#42474c'
  background: '#faf9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e3e2e0'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  section-gap: 120px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

The brand personality is prestigious, meticulous, and curated, designed to appeal to high-end interior designers and luxury homeowners. The visual language evokes the feeling of walking through a quiet, high-end gallery where every detail is intentional. 

This design system utilizes a blend of **Minimalism** and **Modern Editorial** styles. It prioritizes vast amounts of whitespace to emphasize the quality of the finishes, using typography and high-contrast color blocking as the primary decorative elements. The goal is to create a digital environment that feels as tactile and permanent as the premium materials the brand provides.

## Colors

The palette is derived directly from the brand’s signature mark, balancing the depth of the night sky with the warmth of precious metals.

- **Primary (Midnight Navy):** Used for primary text, navigation backgrounds, and structural elements to provide a grounded, authoritative foundation.
- **Secondary (Champagne Gold):** Reserved for accents, highlights, and primary calls to action. It should be used sparingly to maintain its "precious" quality.
- **Tertiary (Slate Grey):** Employed for secondary text and borders, softening the transition between the deep navy and the highlights.
- **Neutral (Alabaster):** A warm off-white used for the primary background to avoid the clinical feel of pure white, adding a layer of sophisticated comfort.

## Typography

The typographic hierarchy relies on the contrast between a classical Serif and a technical Sans-Serif.

- **Headlines:** Use **Playfair Display**. It provides a high-contrast, editorial feel that communicates luxury and history. Large display sizes should use a slight negative letter spacing to feel more "locked in."
- **Body & Interface:** Use **Manrope**. Its geometric but legible structure provides a modern, functional counterpoint to the serif headings. 
- **Labels:** Small labels and overlines should always be set in uppercase Manrope with increased letter spacing to enhance the "architectural" feel of the layout.

## Layout & Spacing

The layout follows a **Fixed Grid** model to ensure the composition of images and text remains harmonious and intentional across large screens.

- **Grid:** A 12-column grid is used for desktop, 8-column for tablet, and 4-column for mobile.
- **Rhythm:** We utilize a generous spacing scale. Section headers should be preceded by significant "breathing room" (120px+) to allow the user to mentally reset between different product categories or stories.
- **Alignment:** Content should predominantly be left-aligned to maintain a clean, structured vertical axis, though hero sections may utilize centered typography for dramatic effect.

## Elevation & Depth

To maintain a premium, flat-lay aesthetic, this design system avoids heavy drop shadows. Depth is instead communicated through:

- **Tonal Layering:** Surfaces are separated by subtle shifts in background color (e.g., Alabaster to a very light Slate) rather than shadows.
- **Fine Lines:** 1px borders in Gold or light Slate are used to define boundaries between content blocks.
- **Backdrop Blurs:** On overlays (like navigation menus or modals), a high-density backdrop blur is used to create a sense of "frosted glass," allowing the rich colors of product photography to bleed through without distracting from the text.

## Shapes

The shape language is **Soft (Level 1)**. 

Luxury finishing is often about precision. Therefore, we use a very small radius (4px) on buttons and containers to take the "edge" off the digital screen while maintaining a sharp, professional, and architectural silhouette. Large imagery and hero containers should remain perfectly sharp (0px) to mimic the edges of a physical sample or stone slab.

## Components

### Buttons
- **Primary:** Solid Midnight Navy with White text. No border.
- **Secondary:** Transparent background with a 1px Gold border and Gold text.
- **Interaction:** On hover, primary buttons shift to a slightly lighter navy; secondary buttons fill with a faint gold tint.

### Cards
- **Product Cards:** Full-bleed imagery with a thin 1px interior border. Typography should be placed below the image in the neutral Alabaster area to keep the focus on the finish.
- **Feature Cards:** Use the primary color for the background with Gold typography for high-impact brand messaging.

### Input Fields
- Inputs should be minimalist, consisting of a single 1px bottom border in Slate. The label should float above the line in uppercase Manrope.

### Lists & Navigation
- Navigation items should use the `label-md` style. The "active" state is indicated by a small, centered gold dot beneath the text rather than a bold weight change, maintaining the visual weight of the header.

### Chips & Tags
- Used for material properties (e.g., "Eco-friendly," "Hand-polished"). These should have a light Slate background with Midnight Navy text and 0px roundedness to resemble architectural labels.