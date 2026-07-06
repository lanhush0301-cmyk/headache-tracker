---
name: Vibrant Health Narrative
colors:
  surface: '#f8f9fc'
  surface-dim: '#d9dadd'
  surface-bright: '#f8f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3f6'
  surface-container: '#edeef1'
  surface-container-high: '#e7e8eb'
  surface-container-highest: '#e1e2e5'
  on-surface: '#191c1e'
  on-surface-variant: '#484554'
  inverse-surface: '#2e3133'
  inverse-on-surface: '#f0f1f4'
  outline: '#787585'
  outline-variant: '#c9c4d6'
  surface-tint: '#5d47cd'
  primary: '#5a44cb'
  on-primary: '#ffffff'
  primary-container: '#735fe5'
  on-primary-container: '#fffbff'
  inverse-primary: '#c8bfff'
  secondary: '#884a6c'
  on-secondary: '#ffffff'
  secondary-container: '#fdb0d7'
  on-secondary-container: '#7a3f60'
  tertiary: '#296659'
  on-tertiary: '#ffffff'
  tertiary-container: '#447f71'
  on-tertiary-container: '#f4fffa'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5deff'
  primary-fixed-dim: '#c8bfff'
  on-primary-fixed: '#190064'
  on-primary-fixed-variant: '#442ab5'
  secondary-fixed: '#ffd8e9'
  secondary-fixed-dim: '#fdb0d7'
  on-secondary-fixed: '#380627'
  on-secondary-fixed-variant: '#6c3354'
  tertiary-fixed: '#b1efde'
  tertiary-fixed-dim: '#96d2c2'
  on-tertiary-fixed: '#00201a'
  on-tertiary-fixed-variant: '#0c5044'
  background: '#f8f9fc'
  on-background: '#191c1e'
  surface-variant: '#e1e2e5'
typography:
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
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
  sm: 12px
  md: 20px
  lg: 32px
  xl: 48px
  container-padding: 24px
  gutter: 16px
---

## Brand & Style

This design system is built on a foundation of **optimistic professionalism**. It balances the clinical reliability required of a health tracking application with a "cute" and approachable aesthetic that reduces the anxiety often associated with personal data monitoring.

The style is a fusion of **Modern Minimalism** and **Tactile Softness**. It utilizes generous whitespace and a clean light background to ensure data density remains readable, while introducing warmth through large radii, playful elevations, and a vibrant pastel palette. The goal is to evoke a sense of encouragement, making the act of health tracking feel less like a chore and more like a rewarding daily ritual.

## Colors

The palette is anchored by a **Bright Friendly Purple** as the primary brand color, used for primary actions and active states. It replaces traditional corporate blues with a more youthful and energetic hue. 

- **Primary (#8B78FF):** Used for CTA buttons, progress indicators, and core brand elements.
- **Secondary / Pastel Accents:** Soft Pink (#FFB2D9), Mint Green (#B4F2E1), and Sky Blue (#AEE2FF) are utilized for categorizing health metrics (e.g., Pink for heart/cardio, Green for nutrition, Blue for sleep).
- **Surface & Background:** The UI sits on a very light gray (#F8F9FC) to allow white cards to pop with subtle elevation.
- **Success/Warning/Error:** Use the Mint Green for success, a soft peach for warnings, and a brighter coral for errors to maintain the "cute" aesthetic without losing functional clarity.

## Typography

This design system uses **Plus Jakarta Sans** for all levels of the hierarchy. Its soft, rounded terminals and modern geometric construction perfectly complement the "friendly and professional" brand narrative.

- **Headlines:** Use heavy weights (Bold 700) with slight negative letter spacing to create a strong, confident visual anchor.
- **Body Text:** Use Medium (500) for standard readability, ensuring that text never feels too thin or "clinical."
- **Data Points:** For numeric health data (steps, bpm), use the Headline-LG style to make progress easily scannable at a glance.

## Layout & Spacing

The layout follows a **fluid, container-based model** with a strong emphasis on whitespace to prevent the UI from feeling cluttered despite the vibrant colors.

- **Mobile:** A single-column layout with 24px side margins. 
- **Grid:** Use a soft 8px grid system for all internal component spacing and padding.
- **Cards:** Content is grouped into cards with 20px (md) internal padding to ensure high legibility.
- **Stacking:** Use the `lg` spacing (32px) between major functional sections to create clear mental breaks for the user.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layering and Playful Shadows**. 

- **Level 0 (Background):** The neutral light gray base.
- **Level 1 (Cards):** Pure white backgrounds with a soft, diffused shadow. Shadows should have a slight tint of the Primary Purple (e.g., `rgba(139, 120, 255, 0.08)`) rather than pure black to keep the UI "clean" and "airy."
- **Level 2 (Interactive):** Floating Action Buttons (FABs) and active selection states use a more pronounced shadow with a 4px-8px Y-offset to appear "squishy" and tappable.
- **Interactive States:** When a card is pressed, it should subtly shrink (scale: 0.98) and its shadow should decrease in blur, simulating a physical press.

## Shapes

The shape language is defined by **Extreme Radii**. 

- **Standard Components:** Buttons, input fields, and small cards use a 16px (rounded-lg) radius.
- **Containers:** Main dashboard cards and modal sheets use a 24px (rounded-xl) radius.
- **Chips & Tags:** These are fully pill-shaped to provide a distinct visual contrast against the more structural cards.
- **Progress Bars:** Ends should be fully rounded to maintain the soft, friendly aesthetic.

## Components

### Buttons
Primary buttons use the Bright Purple background with white text. They should have a minimum height of 56px for easy touch targets. Secondary buttons use a light version of the purple (10% opacity) with purple text.

### Cards
Health data cards should use a white background. Top-level summary cards can use the pastel secondary colors as a full background with dark-tinted text for maximum "cuteness" and categorization.

### Progress Indicators
Use thick, 8px-12px strokes for ring charts and linear bars. These should always have rounded caps. The "track" of the progress bar should be a very faint version of the "fill" color.

### Inputs & Selectors
Input fields use a light gray border that disappears on focus, replaced by a 2px purple stroke. Segmented controllers (e.g., Day/Week/Month toggles) should use a "sliding pill" animation for the active state.

### Chips
Used for filtering or habit labels. They should be colorful but low-contrast (Pastel background + Darker text of the same hue) to avoid competing with primary buttons.