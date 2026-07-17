---
name: Richard Soluções
colors:
  surface: '#10131a'
  surface-dim: '#10131a'
  surface-bright: '#363941'
  surface-container-lowest: '#0b0e15'
  surface-container-low: '#191b23'
  surface-container: '#1d2027'
  surface-container-high: '#272a31'
  surface-container-highest: '#32353c'
  on-surface: '#e1e2ec'
  on-surface-variant: '#c2c6d6'
  inverse-surface: '#e1e2ec'
  inverse-on-surface: '#2e3038'
  outline: '#8c909f'
  outline-variant: '#424754'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e6a'
  primary-container: '#4d8eff'
  on-primary-container: '#00285d'
  inverse-primary: '#005ac2'
  secondary: '#b7c8e1'
  on-secondary: '#213145'
  secondary-container: '#3a4a5f'
  on-secondary-container: '#a9bad3'
  tertiary: '#ffb786'
  on-tertiary: '#502400'
  tertiary-container: '#df7412'
  on-tertiary-container: '#461f00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#ffdcc6'
  tertiary-fixed-dim: '#ffb786'
  on-tertiary-fixed: '#311400'
  on-tertiary-fixed-variant: '#723600'
  background: '#10131a'
  on-background: '#e1e2ec'
  surface-variant: '#32353c'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
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
  unit: 8px
  container-max-width: 1280px
  gutter: 24px
  section-padding-desktop: 80px
  section-padding-mobile: 48px
---

## Brand & Style
The design system is built to project authority, reliability, and local accessibility for a high-end technology solutions provider. The brand personality is grounded and professional, avoiding the coldness of "big tech" in favor of a trustworthy, person-led service model.

The visual style is **Corporate Modern with a Focus on Depth**. It utilizes a "Deep Dark" theme that prioritizes legibility and a premium feel. The aesthetic relies on structured layouts, generous whitespace (to prevent information density overwhelm), and subtle tactile cues that make the interface feel responsive and high-quality.

## Colors
The palette is centered on a "Deep Night" foundation to establish an immediate sense of premium professionalism. 

- **Primary:** A vibrant Tech Blue (#3b82f6) used for calls-to-action, active states, and brand iconography.
- **Surface Palette:** Backgrounds use a tiered navy scale. The base layer is #0f172a, while elevated components (cards, modals) use #1e293b to create depth without relying on heavy shadows.
- **Functional Colors:** Success, warning, and error states should be desaturated to maintain the dark-mode harmony while remaining clearly identifiable.

## Typography
This design system utilizes **Inter** for all roles to ensure maximum legibility and a systematic, modern feel. The type scale is generous to accommodate the "approachable" brand personality.

- **Headlines:** Use Bold and Semi-Bold weights with slight negative letter-spacing to create a "tight" professional look for technical headings.
- **Body:** Standard body text is set at 16px to ensure accessibility. For longer service descriptions, use Body-LG (18px) to increase the premium "editorial" feel.
- **Labels:** Use Medium weight and slight tracking for overline text or small metadata labels to ensure they remain legible against dark backgrounds.

## Layout & Spacing
The layout follows a **Fluid 12-Column Grid** for desktop and a **4-Column Grid** for mobile. 

- **Whitespace:** Use aggressive vertical spacing (80px+ between major sections) to convey a sense of "breathing room" and luxury.
- **Alignment:** Content should be primarily left-aligned to maintain a grounded, professional reading rhythm. 
- **Container:** Main content is capped at 1280px to prevent excessive line lengths on ultra-wide monitors.
- **Rhythm:** All spacing (padding, margins, gaps) must be multiples of the 8px base unit.

## Elevation & Depth
In this dark-themed system, depth is communicated through **Tonal Layering** and **Subtle Outlines** rather than heavy shadows.

- **Level 0 (Base):** #0f172a.
- **Level 1 (Cards/Surface):** #1e293b. These surfaces should have a 1px border of #334155 (Slate 700) to define edges.
- **Level 2 (Dropdowns/Popovers):** #1e293b with a "Soft Ambient Shadow" (0px 10px 30px rgba(0,0,0,0.5)) to lift the element significantly from the page.
- **Interactive States:** On hover, cards should slightly brighten their background or intensify their border color to provide tactile feedback.

## Shapes
The shape language is **Rounded**, leaning towards a friendly but structured aesthetic. 

- **Standard Components:** Buttons, input fields, and small UI widgets use a 0.5rem (8px) radius.
- **Large Components:** Service cards and main containers use a 1rem (16px) radius to soften the overall appearance of the tech-heavy content.
- **Icons:** Use icons with rounded terminals (e.g., Lucide or Phosphor Icons in "Regular" or "Medium" weight) to match the UI's curvature.

## Components

### Buttons
Buttons are the primary tactile element.
- **Primary:** Solid Blue (#3b82f6) with White text. Large padding (12px 24px) and 8px rounded corners.
- **Secondary:** Transparent background with a 1px border (#334155) and White text.
- **Hover States:** Primary buttons should shift to a slightly lighter blue; Secondary buttons should gain a subtle background tint (#1e293b).

### Cards
Cards are the primary container for services and technical solutions.
- Background: #1e293b.
- Border: 1px solid #334155.
- Padding: 32px (generous) to allow icons and headings to breathe.

### Input Fields
- Background: #0f172a (sunken look).
- Border: 1px solid #334155.
- Focus State: Border color changes to #3b82f6 with a subtle outer glow.

### Chips/Tags
Used for service categories or technical skills. 
- Appearance: Subtle navy background (#334155) with #94a3b8 text. Fully rounded (pill-shaped).

### Lists
For technical specifications, use "Bullet-less" lists with Primary Blue icons (checkmarks or carets) to guide the eye without adding visual clutter.