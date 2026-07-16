---
name: Lumina Terra
colors:
  surface: '#fbfbe2'
  surface-dim: '#dbdcc3'
  surface-bright: '#fbfbe2'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f5dc'
  surface-container: '#efefd7'
  surface-container-high: '#eaead1'
  surface-container-highest: '#e4e4cc'
  on-surface: '#1b1d0e'
  on-surface-variant: '#40493d'
  inverse-surface: '#303221'
  inverse-on-surface: '#f2f2d9'
  outline: '#707a6c'
  outline-variant: '#bfcaba'
  surface-tint: '#1b6d24'
  primary: '#0d631b'
  on-primary: '#ffffff'
  primary-container: '#2e7d32'
  on-primary-container: '#cbffc2'
  inverse-primary: '#88d982'
  secondary: '#126d27'
  on-secondary: '#ffffff'
  secondary-container: '#9cf49c'
  on-secondary-container: '#19722b'
  tertiary: '#69512d'
  on-tertiary: '#ffffff'
  tertiary-container: '#836943'
  on-tertiary-container: '#ffeedc'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a3f69c'
  primary-fixed-dim: '#88d982'
  on-primary-fixed: '#002204'
  on-primary-fixed-variant: '#005312'
  secondary-fixed: '#9ff79f'
  secondary-fixed-dim: '#83da85'
  on-secondary-fixed: '#002105'
  on-secondary-fixed-variant: '#005318'
  tertiary-fixed: '#ffddb0'
  tertiary-fixed-dim: '#e2c195'
  on-tertiary-fixed: '#281800'
  on-tertiary-fixed-variant: '#594320'
  background: '#fbfbe2'
  on-background: '#1b1d0e'
  surface-variant: '#e4e4cc'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-md:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '500'
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
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 80px
  section-gap: 120px
---

## Brand & Style

This design system embodies the intersection of environmental stewardship and high-end industrial innovation. The aesthetic is rooted in **Premium Minimalism** with a **Glassmorphic** layer, reflecting the transparency and purity of biodegradable materials. The interface should evoke a sense of calm authority and high-value craftsmanship.

The visual narrative relies on expansive whitespace to signal luxury and focus, while soft shadows and translucent surfaces provide a tactile, organic depth. Every interaction should feel intentional, smooth, and high-precision, positioning the brand as a global leader in sustainable luxury manufacturing.

## Colors

The palette is derived from a refined natural spectrum. **Forest Green** serves as the anchor, representing stability and deep ecological roots. **Light Green** is used for interactive states and growth-oriented messaging. 

The supporting **Beige** and **Light Brown** provide an earthy, organic foundation that softens the professional rigidity of the greens. **Soft Gold** is reserved strictly for high-value accents, premium certifications, and subtle highlights to denote the "luxury" tier of the products. Glassmorphic elements utilize white at 40-70% opacity with a high backdrop blur to maintain legibility against these organic tones.

## Typography

The typographic scale uses **Montserrat** for headlines to convey confidence and a modern architectural feel. The geometric nature of Montserrat complements the rounded UI elements. **Inter** is utilized for body text and labels to ensure maximum legibility and a systematic, professional tone.

Large display sizes should use tighter letter spacing to maintain a "lock-up" feel, while labels utilize increased tracking for a premium, airy aesthetic. All type should be rendered with high contrast against beige or white backgrounds to ensure accessibility.

## Layout & Spacing

The design system utilizes a **Fixed Grid** model for desktop, centered within a 1440px container. A 12-column structure is used with generous 32px gutters to prevent content density. 

Luxury is communicated through "negative space." Vertical rhythm follows an 8px base unit, but section headers should be separated by significantly larger gaps (120px+) to allow the products to "breathe." Content should be grouped in logical "islands" rather than edge-to-edge blocks, emphasizing a curated, gallery-like experience.

## Elevation & Depth

Hierarchy is established through **Glassmorphism** and **Ambient Shadows**. 

1.  **Base Layer:** Solid White (#FFFFFF) or Beige (#F5F5DC) backgrounds.
2.  **Elevated Layer (Cards/Modals):** White at 60% opacity with a 20px Backdrop Blur.
3.  **Shadows:** Shadows are highly diffused and low-opacity. Use a hex value like `#2E7D32` at 5-8% opacity for the shadow color to create a "glow" that feels integrated with the brand's primary green, rather than a generic grey shadow.
4.  **Transitions:** All elevation changes must use a 300ms "ease-out" transition to simulate the soft, organic movement of natural elements.

## Shapes

The shape language is defined by the **2xl** (1.5rem / 24px) corner radius, reflecting the organic, non-sharp nature of edible products. Large containers and glassmorphic panels use this radius to feel friendly yet sophisticated. Primary buttons and small input fields should maintain a slightly smaller but still significantly rounded profile to match the overarching softness.

## Components

### Buttons
Primary buttons use a solid Forest Green background with white Montserrat text (Medium weight). Hover states should involve a subtle shift to Light Green and a slight increase in the ambient shadow spread. Secondary buttons should be glassmorphic with a thin 1px border in Light Brown.

### Cards
Cards are the primary vehicle for product showcases. They must feature the 24px rounded corners, a glassmorphic background, and a soft primary-tinted shadow. Images within cards should have a 16px radius to create a nested, harmonious look.

### Input Fields
Fields should use the Beige support color for the background with a 1px Forest Green border that only appears on focus. This keeps the form looking clean and "un-designed" until interaction is required.

### Chips & Tags
Used for sustainability certifications (e.g., "100% Biodegradable"). These should use the Soft Gold accent color for the text and a 10% opacity Soft Gold background, ensuring the premium nature of the claim is visually distinct.

### Lists
Lists should be understated, using Soft Gold dots or custom organic icons instead of standard bullets, maintaining the high-end editorial feel.