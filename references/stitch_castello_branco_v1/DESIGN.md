---
name: Elite Investigation System
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#59413f'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#8c706e'
  outline-variant: '#e0bfbb'
  surface-tint: '#ae2f2c'
  primary: '#76000a'
  on-primary: '#ffffff'
  primary-container: '#981e1e'
  on-primary-container: '#ffaaa2'
  inverse-primary: '#ffb3ac'
  secondary: '#7c5800'
  on-secondary: '#ffffff'
  secondary-container: '#fdca6a'
  on-secondary-container: '#765300'
  tertiary: '#730b05'
  on-tertiary: '#ffffff'
  tertiary-container: '#942519'
  on-tertiary-container: '#ffab9e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb3ac'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#8d1517'
  secondary-fixed: '#ffdea8'
  secondary-fixed-dim: '#f1bf60'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5e4200'
  tertiary-fixed: '#ffdad4'
  tertiary-fixed-dim: '#ffb4a8'
  on-tertiary-fixed: '#410000'
  on-tertiary-fixed-variant: '#891d12'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  headline-xl:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  section-gap: 80px
  container-max: 1200px
  gutter: 24px
  margin-sm: 16px
  margin-md: 32px
---

## Brand & Style

This design system is built upon a foundation of authority, discretion, and meticulous precision. It is designed to evoke a sense of high-level intelligence and institutional trust, catering to a clientele that values confidentiality and professional rigor. 

The aesthetic follows a **Corporate / Modern** direction with a focus on editorial clarity. It utilizes a structured grid and a high-contrast palette to establish clear information hierarchy. By balancing traditional serif typography with a utilitarian sans-serif, the system bridges the gap between classic investigative heritage and modern digital forensics. The visual language is intentionally sober, avoiding unnecessary flourishes to maintain a focus on facts and results.

## Colors

The color palette is anchored by a deep, authoritative red and a sophisticated gold. The primary red (#981E1E) is used for key actions and brand identifiers, conveying strength and urgency. The gold (#C4963C) acts as a premium accent, used for service highlights and calls to action that require a refined touch. 

The tertiary deep red (#660000) is reserved for footers, heavy backgrounds, or hover states to provide depth. The neutral palette relies on pure white for clarity and a near-black (#1A1A1A) for typography to ensure maximum legibility and a high-end feel. Color is used strategically to guide the eye through the structured investigation services without overwhelming the user.

## Typography

This design system employs a dual-font strategy to balance tradition and utility. **Noto Serif** is used for headlines to provide an authoritative, editorial voice reminiscent of premium legal and investigative publications. This serif face adds a layer of sophistication and "weight" to the brand's messaging.

**Inter** is the functional workhorse for body text, UI labels, and technical data. Its neutral, systematic nature ensures that complex service descriptions remain accessible and easy to digest. High-level headings often use an uppercase transformation with slight letter-spacing to emphasize the institutional character of the layout.

## Layout & Spacing

The layout follows a **Fixed Grid** model, centering content within a 1200px container for a disciplined, organized appearance. A 12-column structure is used to arrange service cards and content blocks, typically utilizing 3 or 4-column spans for modularity.

Vertical rhythm is governed by an 8px base unit. Generous section gaps (80px) are used to separate different service categories and information blocks, providing the "breathing room" necessary for a premium experience. Content is often organized into distinct horizontal bands, alternating between light backgrounds and colored "service bands" (e.g., gold or red) to create a clear narrative flow as the user scrolls.

## Elevation & Depth

Hierarchy in this design system is primarily achieved through **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows. Cards and service containers use subtle, high-blur shadows (e.g., 0px 4px 20px rgba(0,0,0,0.05)) to lift them slightly from the surface without breaking the clean, flat aesthetic.

Structural depth is created by the use of solid color blocks. For example, a gold background section acts as a "container tier" that houses white cards, creating a natural stacked effect. Borders are used sparingly, often as thin 1px lines in a slightly darker neutral or the primary red to define input fields or secondary button boundaries.

## Shapes

The shape language is **Soft (0.25rem)**, prioritizing a sharp, architectural feel that reflects professional stability. While most edges are crisp, a very slight radius is applied to buttons and cards to prevent the UI from feeling overly aggressive.

- **Primary Components:** Buttons and cards use a 4px (0.25rem) radius.
- **Icons:** Should be encased in circular or square containers with minimal rounding to maintain the "stamp" or "seal" appearance typical of official documentation.
- **Media:** Images should maintain sharp corners or the standard 4px radius to align with the grid-heavy layout.

## Components

### Buttons
Primary buttons are solid #981E1E with white text for maximum impact. Secondary buttons use a #C4963C background or an outlined style with the brand's primary colors. All buttons use uppercase labels to maintain the formal tone.

### Service Cards
Cards are the primary vehicle for investigation categories. They feature a central icon (gold or dark red), a bold serif title, and a simple "Know more" text link with a directional arrow. They utilize white backgrounds to stand out against colored section containers.

### Input Fields
Inputs are minimalist, featuring a 1px border and a subtle background tint. Focus states should be highlighted with the primary red color. Labels use the `label-lg` typographic style for clear field identification.

### Icons
Iconography must be thin-line or monoline, avoiding overly "playful" styles. Icons represent serious concepts (law, international, digital intelligence) and should be rendered in the secondary gold color to act as a visual anchor.

### Testimonial Sliders
Reviews are housed in clean, white cards with a centered layout, utilizing the gold accent for star ratings to signify quality and excellence.