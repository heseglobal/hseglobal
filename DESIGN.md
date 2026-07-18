---
name: Global Trade Authority
colors:
  surface: '#111415'
  surface-dim: '#111415'
  surface-bright: '#373a3b'
  surface-container-lowest: '#0c0f10'
  surface-container-low: '#191c1d'
  surface-container: '#1d2021'
  surface-container-high: '#282a2b'
  surface-container-highest: '#323536'
  on-surface: '#e1e3e4'
  on-surface-variant: '#c5c6cd'
  inverse-surface: '#e1e3e4'
  inverse-on-surface: '#2e3132'
  outline: '#8f9097'
  outline-variant: '#45474d'
  surface-tint: '#bbc6e2'
  primary: '#bbc6e2'
  on-primary: '#263046'
  primary-container: '#1b263b'
  on-primary-container: '#828da7'
  inverse-primary: '#545e76'
  secondary: '#b9c9d3'
  on-secondary: '#23323a'
  secondary-container: '#3c4b53'
  on-secondary-container: '#abbbc5'
  tertiary: '#e9c176'
  on-tertiary: '#412d00'
  tertiary-container: '#342300'
  on-tertiary-container: '#ab8844'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#bbc6e2'
  on-primary-fixed: '#101b30'
  on-primary-fixed-variant: '#3c475d'
  secondary-fixed: '#d5e5ef'
  secondary-fixed-dim: '#b9c9d3'
  on-secondary-fixed: '#0e1d25'
  on-secondary-fixed-variant: '#3a4951'
  tertiary-fixed: '#ffdea5'
  tertiary-fixed-dim: '#e9c176'
  on-tertiary-fixed: '#261900'
  on-tertiary-fixed-variant: '#5d4201'
  background: '#111415'
  on-background: '#e1e3e4'
  surface-variant: '#323536'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Playfair Display
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
spacing:
  container-max: 1280px
  gutter: 2rem
  margin-desktop: 4rem
  margin-mobile: 1.5rem
  stack-sm: 0.5rem
  stack-md: 1.5rem
  stack-lg: 4rem
---

## Brand & Style

The design system is engineered to project **Authority, Heritage, and Global Reach**. It serves a sophisticated B2B audience in international trade where trust is the primary currency. 

The aesthetic is **Cinematic Corporate**, blending the precision of Swiss minimalism with the warmth of human-centric storytelling. Large-scale, high-fidelity photography—specifically featuring the co-founders—is used to humanize complex global logistics. The visual mood is established through heavy whitespace, editorial-grade typography, and a "prestige" finish that emphasizes quality over quantity. 

The HSE logo should be treated with architectural reverence, often placed against deep, textured backgrounds or clean cream surfaces to highlight its metallic "E" accent.

## Colors

This design system utilizes a high-contrast, prestigious palette. **Dark Navy (#1B263B)** serves as the primary canvas, providing a sense of stability and depth. **Deep Slate Grey (#2F3E46)** is used for structural differentiation and UI layering.

**Gold (#C5A059)** is a surgical accent color, reserved for critical calls to action, brand-defining iconography, and subtle borders that denote "premium" status. **Cream (#F8F9FA)** acts as the primary text color on dark surfaces and a luxurious background color for editorial sections, providing a softer, more sophisticated alternative to pure white.

## Typography

The typographic hierarchy is built on a "Dual-Tone" strategy. **Playfair Display** provides a literary, authoritative voice for headlines and display quotes, evoking the feel of high-end financial journalism. **Inter** provides a clean, functional counterpoint for all data-heavy and body text roles, ensuring maximum legibility across global time zones and devices.

Use `label-caps` for small navigational elements and section headers above the main headline to create a structured, "organized" document feel.

## Layout & Spacing

The design system employs a **Fixed 12-Column Grid** for desktop and a **Fluid 4-Column Grid** for mobile. The layout philosophy is "Breathe First"—we prioritize generous margins (`stack-lg`) between major content blocks to convey a sense of calm and control.

For founder profiles and human-centric sections, use asymmetrical layouts (e.g., text spanning 5 columns, image spanning 7 columns) to create a cinematic, editorial feel that breaks the monotony of standard corporate grids.

## Elevation & Depth

Visual hierarchy is established through **Tonal Layering** rather than traditional shadows. Surfaces are stacked using color values:
- **Level 0 (Base):** Dark Navy (#1B263B).
- **Level 1 (Cards/Containers):** Deep Slate Grey (#2F3E46) with a 1px border of either Gold (at 20% opacity) or a lighter Navy.
- **Level 2 (Popovers/Modals):** Pure Deep Slate with a subtle ambient glow using the Primary color.

Founder imagery should use soft, localized vignettes rather than hard drop shadows to blend into the interface.

## Shapes

To maintain a professional, architectural, and serious tone, this design system uses **Sharp (0px)** roundedness. 

Right angles communicate precision and structural integrity, which are critical in the context of international trade and logistics. Circular elements are permitted only for founder avatars when a softer "human" touch is required, or for specific iconography. All containers, buttons, and input fields must remain strictly rectangular.

## Components

### Buttons
- **Primary:** Deep Navy background, Gold text, and a 1px Gold border. Rectangular with generous internal padding.
- **Secondary:** Transparent background, Cream text, and a 1px Cream border at 40% opacity.

### Cards
Cards are defined by their content rather than heavy styling. Use Deep Slate Grey backgrounds. For founder cards (Eustella, Hadi, Emin, Elbin, Senthil), the image should be the hero, with the name in `headline-sm` and a caption in `body-sm`.

### Input Fields
Strictly rectangular. Use the Deep Slate Grey background with a Cream bottom-border only for a "minimalist legal document" aesthetic.

### Lists & Data
Global trade requires clear data. Use Inter for all tabular data. Alternate row backgrounds with a 5% opacity difference to maintain scanability without adding visual clutter.