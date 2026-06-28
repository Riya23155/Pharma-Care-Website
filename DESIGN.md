---
name: Clinical Clarity
colors:
  surface: '#f8f9fd'
  surface-dim: '#d8dadd'
  surface-bright: '#f8f9fd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f7'
  surface-container: '#eceef1'
  surface-container-high: '#e6e8ec'
  surface-container-highest: '#e1e2e6'
  on-surface: '#191c1f'
  on-surface-variant: '#424752'
  inverse-surface: '#2e3134'
  inverse-on-surface: '#eff1f4'
  outline: '#727783'
  outline-variant: '#c2c6d4'
  surface-tint: '#005db6'
  primary: '#00478d'
  on-primary: '#ffffff'
  primary-container: '#005eb8'
  on-primary-container: '#c8daff'
  inverse-primary: '#a9c7ff'
  secondary: '#006d33'
  on-secondary: '#ffffff'
  secondary-container: '#75f999'
  on-secondary-container: '#007236'
  tertiary: '#42484f'
  on-tertiary: '#ffffff'
  tertiary-container: '#596067'
  on-tertiary-container: '#d4dae2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#a9c7ff'
  on-primary-fixed: '#001b3d'
  on-primary-fixed-variant: '#00468c'
  secondary-fixed: '#78fc9c'
  secondary-fixed-dim: '#5adf82'
  on-secondary-fixed: '#00210b'
  on-secondary-fixed-variant: '#005225'
  tertiary-fixed: '#dde3eb'
  tertiary-fixed-dim: '#c1c7cf'
  on-tertiary-fixed: '#161c22'
  on-tertiary-fixed-variant: '#41474e'
  background: '#f8f9fd'
  on-background: '#191c1f'
  surface-variant: '#e1e2e6'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
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
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The design system is built on the pillars of **reliability, accessibility, and hygiene**. It targets a diverse demographic ranging from young parents to the elderly, requiring a UI that feels both technologically advanced and deeply human. 

The aesthetic is **Corporate Modern with a Soft Edge**. It utilizes a systematic approach to white space to reduce cognitive load, ensuring that critical medical information is never obscured by decorative elements. The emotional response is one of calm confidence—moving away from the sterile coldness of traditional hospitals toward a welcoming, efficient pharmacy experience.

## Colors
The palette is rooted in medical authority. 

- **Primary Medical Blue (#005EB8):** Used for navigation, primary actions, and branding to establish immediate trust and recognition.
- **Health Mint (#00A651):** Reserved for positive health outcomes, success states, and health-related callouts.
- **Surface & Backgrounds:** The interface relies heavily on white (#FFFFFF) and a very light cool gray (#F8FAFC) to maintain a "clinical" level of cleanliness.
- **System States:** Error states use a soft coral (#D32F2F), while info states utilize a lighter tint of the primary blue.

## Typography
This design system utilizes **Inter** for its exceptional legibility in both digital and print contexts. 

- **Hierarchy:** Strong contrast between bold headlines and regular body text ensures users can scan for dosage or medication names quickly.
- **Scale:** On mobile devices, `headline-xl` and `headline-lg` should downscale by 20% to ensure titles fit comfortably on screen.
- **Legibility:** Line heights are intentionally generous (1.5x for body) to assist users with visual impairments or those reading under stress.

## Layout & Spacing
The layout follows a **Fluid Grid** system with a focus on "breathability." 

- **Desktop:** 12-column grid with 24px gutters. Max content width is 1280px.
- **Tablet:** 8-column grid with 24px gutters.
- **Mobile:** 4-column grid with 16px margins.
- **Rhythm:** All spacing (padding, margins) must be multiples of 8px. Use 24px (md) as the standard padding for cards and containers to ensure information doesn't feel cramped.

## Elevation & Depth
To convey friendliness and approachability, this design system avoids harsh lines. Instead, it uses **Ambient Shadows** and **Tonal Layers**.

- **Level 1 (Surface):** Default background (#FFFFFF or #F8FAFC).
- **Level 2 (Cards):** Soft, diffused shadow (0px 4px 12px rgba(0, 0, 0, 0.05)) to separate interactive content from the background.
- **Level 3 (Modals/Dropdowns):** Deeper shadow (0px 12px 24px rgba(0, 0, 0, 0.1)) to indicate high-priority interaction.
- **Active States:** Subtle inner shadows or 1px strokes in Primary Blue are used for focused input fields.

## Shapes
A **Rounded (0.5rem)** approach is applied across the system to evoke a "soft-tech" feel. 

- **Buttons & Inputs:** Use the base `0.5rem` (8px) radius.
- **Large Cards:** Use `rounded-lg` (1rem / 16px) for major layout containers like medication overviews.
- **Pills/Chips:** Always use a fully rounded radius (Pill-shaped) for status indicators or category tags.

## Components

### Buttons
- **Primary:** Solid #005EB8 with white text. High-contrast, rounded corners.
- **Secondary:** White background with #005EB8 border and text.
- **Prescription Upload:** A unique "Action Card" style button—large, dashed border, featuring an icon and descriptive subtext to guide the user through a critical path.

### Product Cards
Medication cards feature a clean white background, a Level 2 shadow, and a clear "Add to Cart" or "Refill" button. The price is displayed in Primary Blue, while the drug name uses `headline-sm`.

### Health Alert Banners
Sticky banners at the top of the viewport or within sections. 
- **Urgent:** Pale red background with bold red text.
- **Informational:** Light Mint background with #00A651 text. 
Always include a clear dismiss "X" or "Learn More" link.

### Input Fields
Generous padding (12px) and a clear label above the field. Inactive state has a light gray border; Active state has a 2px Primary Blue border.

### Lists
Healthcare listings (e.g., pharmacy locations) use 16px vertical padding between items with a light divider line (#E2E8F0) and chevron indicators to suggest interactivity.