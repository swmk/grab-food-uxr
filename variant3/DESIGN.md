---
name: Grab Food Redesign
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#3d4a3d'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#6d7b6c'
  outline-variant: '#bccbb9'
  surface-tint: '#006e2e'
  primary: '#006e2e'
  on-primary: '#ffffff'
  primary-container: '#00b14f'
  on-primary-container: '#003a15'
  inverse-primary: '#52e078'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#5d5f5f'
  on-tertiary: '#ffffff'
  tertiary-container: '#999a9a'
  on-tertiary-container: '#303233'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#71fe91'
  primary-fixed-dim: '#52e078'
  on-primary-fixed: '#002109'
  on-primary-fixed-variant: '#005321'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  display-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  container-margin: 16px
  gutter: 16px
---

## Brand & Style

The brand identity is built on a foundation of reliability and efficiency. It targets a diverse urban demographic that values speed without sacrificing quality. The visual language evokes a sense of "premium utility"—where every element serves a functional purpose while maintaining an appetizing aesthetic through high-quality imagery.

The design style follows a **Corporate / Modern** approach, utilizing refined layouts, significant whitespace, and a systematic hierarchy. It prioritizes clarity and high-quality food photography to drive the user experience, ensuring the interface feels transparent and frictionless. The emotional response should be one of confidence: the user knows exactly what they are ordering and when it will arrive.

## Colors

The palette is anchored by the signature Grab Green, used purposefully to signify action and success. Charcoal provides a strong grounding for typography and structural elements, while clean White dominates the background to ensure a "transparent" feel.

To meet WCAG 2.2 AA standards, the primary green is used as a brand signal and for large interactive elements. For text-based information, Charcoal and high-contrast greys are used to ensure maximum legibility. Semantic colors are reserved for status indicators (e.g., order tracking, error messages) to maintain a clean, uncluttered interface.

## Typography

This design system utilizes **Inter** for its neutral, systematic character. The hierarchy is strictly enforced to guide users through complex menus and checkout flows effortlessly. 

Display sizes are bold and tight to create impact for restaurant names and hero sections. Body copy uses generous line heights to ensure readability during quick scanning. Labels and small metadata (e.g., delivery times, ratings) utilize medium and semi-bold weights to maintain visibility at smaller scales.

## Layout & Spacing

The layout is built on an **8px grid system**, ensuring consistent vertical and horizontal rhythm. 

- **Mobile:** Uses a 4-column fluid grid with 16px side margins and 16px gutters.
- **Desktop:** Uses a 12-column fixed grid (max-width 1200px) with 24px gutters.

Spacing follows a linear scale where padding and margins are increments of 8px. This predictability reinforces the "frictionless" and "reliable" brand tone, providing a sense of structural integrity as users navigate through different views.

## Elevation & Depth

Visual depth is achieved through **Tonal Layers** and **Ambient Shadows**, avoiding heavy gradients or skeuomorphism. 

1. **Surface Level (0dp):** The main background (White), used for the primary canvas.
2. **Card Level (1dp):** Subtle 1px borders (#EEEEEE) or very soft, diffused shadows (4px blur, 4% opacity) used to group restaurant items and menu sections.
3. **Floating Level (2dp):** Used for sticky navigation bars and "Add to Basket" buttons. These feature a more pronounced but still natural shadow (12px blur, 8% opacity).
4. **Modal/Overlay Level (3dp):** High-elevation layers with background dimming to focus user attention on specific actions like food customization.

## Shapes

The shape language is consistently **Rounded**, striking a balance between modern friendliness and professional structure. 

- **Standard Elements:** 8px (0.5rem) radius for buttons, input fields, and small cards.
- **Large Containers:** 16px (1rem) radius for restaurant hero cards and promotional banners.
- **Interactive Pill Shapes:** Used exclusively for tags, category chips, and quantity selectors to distinguish them from primary action buttons.
- **Images:** All food photography must feature rounded corners (minimum 8px) to maintain the cohesive soft-modern aesthetic.

## Components

### Buttons
- **Primary:** Solid Grab Green background with White text. High-contrast and full-width for main conversion actions (e.g., "Place Order").
- **Secondary:** Charcoal outline or White background with Charcoal text for less critical actions.
- **Ghost:** No background, primary green text for utility actions (e.g., "View Details").

### Input Fields
Inputs use an 8px radius with a 1px soft-grey border. On focus, the border transitions to Charcoal or Grab Green. Error states must include both a red border and a supporting icon for accessibility.

### Cards
Restaurant and menu cards are the primary vessels for information. They feature high-quality imagery with a 1:1 or 16:9 aspect ratio. Text information is stacked below the image with clear typographic hierarchy for price, rating, and estimated time.

### Chips & Filters
Small, pill-shaped elements used for dietary preferences and cuisine types. Active states use Grab Green backgrounds; inactive states use a light-grey (#F2F2F2) background to minimize visual noise.

### Order Tracking
A specialized component utilizing a vertical or horizontal stepper. It uses the primary green to indicate progress and icons to signify milestones (e.g., "Food is being prepared," "Driver is nearby"), ensuring total transparency.