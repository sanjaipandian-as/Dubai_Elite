---
name: Dubai Elite Aesthetic
colors:
  surface: '#fff8f2'
  surface-dim: '#e4d8c8'
  surface-bright: '#fff8f2'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fef2e1'
  surface-container: '#f8ecdc'
  surface-container-high: '#f3e6d6'
  surface-container-highest: '#ede1d1'
  on-surface: '#201b11'
  on-surface-variant: '#504533'
  inverse-surface: '#363025'
  inverse-on-surface: '#fbefde'
  outline: '#827560'
  outline-variant: '#d4c4ac'
  surface-tint: '#7a5900'
  primary: '#7a5900'
  on-primary: '#ffffff'
  primary-container: '#f4b400'
  on-primary-container: '#654800'
  inverse-primary: '#fdbc13'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dfe0e0'
  on-secondary-container: '#616363'
  tertiary: '#5c5f60'
  on-tertiary: '#ffffff'
  tertiary-container: '#bdbfc0'
  on-tertiary-container: '#4b4e4f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdea3'
  primary-fixed-dim: '#fdbc13'
  on-primary-fixed: '#261900'
  on-primary-fixed-variant: '#5d4200'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e1e3e4'
  tertiary-fixed-dim: '#c5c7c8'
  on-tertiary-fixed: '#191c1d'
  on-tertiary-fixed-variant: '#454748'
  background: '#fff8f2'
  on-background: '#201b11'
  surface-variant: '#ede1d1'
typography:
  h1:
    fontFamily: Noto Serif
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h3:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.02em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.15em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-x: 64px
  section-padding: 120px
---

## Brand & Style

The design system is engineered to evoke exclusivity, architectural grandeur, and the high-octane luxury of the Dubai property market. The brand personality is authoritative yet welcoming, mirroring the experience of a private concierge. The target audience includes high-net-worth individuals who value precision, space, and prestige.

The visual style is a hybrid of **High-End Minimalism** and **Glassmorphism**. It prioritizes "cinematic presentation" where the UI recedes to let architectural photography take center stage. The emotional response should be one of "aspirational calm"—expansive layouts that feel expensive and meticulously curated. Smooth micro-interactions and subtle golden glows reinforce a sense of digital craftsmanship.

## Colors

The palette is rooted in the contrast between "Desert Gold" and "Modern Marble." 

- **Primary (#F4B400):** A sophisticated Luxury Golden Yellow used exclusively for high-impact moments: call-to-actions, active states, and premium highlights.
- **Backgrounds (#FFFFFF, #F8F9FA):** Pure White is used for primary canvas areas to maximize the sense of light. Soft Light Gray provides subtle structural variance for sectioning without closing in the space.
- **Typography & Accents (#1A1A1A):** A Deep Charcoal that provides the necessary weight and authority to the elegant serif headings. 
- **Interactive State:** Hover states on gold elements should incorporate a subtle radial glow (inner-source lighting) rather than simple darkening.

## Typography

This design system utilizes a high-contrast typographic pairing to signal luxury.

- **Headlines:** Uses **Noto Serif** for a timeless, editorial feel. The high stroke contrast of this serif mimics premium print magazines. Headings should use tight tracking to maintain a modern, "locked-in" appearance.
- **Body:** Uses **Inter** for its neutral, utilitarian clarity. To achieve the "Elite" aesthetic, body text is given generous line height and slightly increased letter spacing to prevent the interface from feeling "busy."
- **Labels:** Small labels and metadata (e.g., square footage, bed/bath counts) should always be in uppercase with wide tracking to act as architectural annotations.

## Layout & Spacing

The layout philosophy follows a **Fixed-Fluid Hybrid Grid**. Content is housed within a generous maximum width to maintain readability on ultra-wide displays, surrounded by expansive margins.

- **Rhythm:** A strict 8px base unit drives all spacing.
- **Whitespace:** Emphasize vertical "breathing room." Section headers should be separated by at least 120px to evoke the scale of a luxury villa.
- **Grid:** A 12-column system with wide 32px gutters. Elements like property galleries should break the grid occasionally to create a dynamic, cinematic flow.

## Elevation & Depth

Depth in this design system is achieved through **Glassmorphism** and **Ambient Lighting** rather than traditional heavy shadows.

- **Surfaces:** Use backdrop-blur (12px to 20px) with a semi-transparent white fill (opacity 70-80%) for navigation bars and floating filters. This creates a "frosted glass" effect that allows property imagery to bleed through.
- **Shadows:** Use extremely diffused, low-opacity shadows (Color: #1A1A1A at 5-8% opacity) with large blur radii (30px+) to create a soft, elevated lift.
- **The "Gold Glow":** Floating buttons or active property cards should utilize a subtle golden outer-glow filter (`drop-shadow: 0 0 15px rgba(244, 180, 0, 0.3)`) to simulate the reflection of light on precious metal.

## Shapes

The design system employs **Soft** geometry. While harsh 90-degree corners feel too brutalist, overly circular shapes feel too casual.

- **Standard Radius:** A 4px (0.25rem) radius is used for buttons and inputs to maintain a crisp, professional edge.
- **Container Radius:** Larger components like property cards or modal windows use an 8px or 12px radius to soften the cinematic frames.
- **Imagery:** Architectural photos should remain sharp or use the standard container radius; never use "pill" shapes for primary content.

## Components

- **Property Cards:** Feature full-bleed imagery with a glassmorphic information overlay at the bottom. On hover, the image should subtly scale (1.05x) while the golden accent border activates.
- **Floating Buttons:** Primary CTAs (e.g., "Book a Viewing") should be floating "Action Orbs" or sleek glass pills with a golden gradient border.
- **Interactive Filters:** A horizontal glass bar that sticks to the top of the viewport during scroll, utilizing uppercase labels and minimal icons.
- **Inputs:** Ultra-minimalist. Bottom-border only by default, transitioning to a full golden outline on focus.
- **Status Chips:** Small, high-contrast badges (e.g., "Sold," "Exclusive") using the `label-caps` typography and the Deep Charcoal background with White text.
- **Navigation:** A transparent-to-frosted-glass transition header that hides on scroll-down and reveals on scroll-up to maximize screen real estate for imagery.