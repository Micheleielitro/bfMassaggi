---
name: Zen Wellness System
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
  on-surface-variant: '#424845'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#737874'
  outline-variant: '#c2c8c3'
  surface-tint: '#506259'
  primary: '#4e6057'
  on-primary: '#ffffff'
  primary-container: '#66796f'
  on-primary-container: '#f5fff8'
  inverse-primary: '#b7cbc0'
  secondary: '#6a5c4b'
  on-secondary: '#ffffff'
  secondary-container: '#f0ddc6'
  on-secondary-container: '#6e604f'
  tertiary: '#5e5c55'
  on-tertiary: '#ffffff'
  tertiary-container: '#77746d'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d3e7dc'
  primary-fixed-dim: '#b7cbc0'
  on-primary-fixed: '#0e1f18'
  on-primary-fixed-variant: '#394b42'
  secondary-fixed: '#f3dfc9'
  secondary-fixed-dim: '#d6c4ae'
  on-secondary-fixed: '#241a0c'
  on-secondary-fixed-variant: '#514534'
  tertiary-fixed: '#e6e2d9'
  tertiary-fixed-dim: '#cac6be'
  on-tertiary-fixed: '#1c1c16'
  on-tertiary-fixed-variant: '#484740'
  background: '#faf9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e3e2e0'
typography:
  h1:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  h3:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: '0'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  section-padding: 80px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system centers on the concept of "Digital Sanctuary." It is designed to lower the heart rate of the user through intentionality, balance, and quietude. The target audience seeks high-end professional wellness services and expects an interface that reflects the same level of care they receive during a treatment.

The style is a blend of **Minimalism** and **Tonal Layering**. It prioritizes heavy whitespace to allow content to breathe, avoiding the visual clutter typical of medical or booking platforms. The aesthetic is "cool" in its composure—never frantic, never loud—utilizing subtle transitions and a soft palette to create a sense of professional luxury and holistic peace.

## Colors

The palette is derived from natural elements: moss, stone, and sand. 

- **Sage Green (Primary):** Used for primary actions and brand presence. It represents growth and restoration.
- **Warm Sand (Secondary):** Used for accents and secondary interactive elements, providing a grounding earthiness.
- **Stone & Ivory (Neutrals):** The foundation of the UI. These colors replace pure whites to reduce eye strain and provide a "paper-like" tactile quality.
- **Charcoal Green (Text):** A softened dark tone that maintains high legibility while feeling more organic than pure black.

Usage should follow a 60-30-10 rule, where the neutral stone tones dominate the background to maintain a "breathable" atmosphere.

## Typography

This design system employs a sophisticated typographic pairing to balance tradition and modernity. 

**Noto Serif** is used for headlines to convey elegance and a "literary" quality associated with high-end editorial wellness journals. It should be used with generous leading.

**Manrope** serves as the functional workhorse for body text and interface labels. Its geometric yet soft construction ensures clarity and professional reliability. 

For navigation and small labels, an uppercase Manrope with increased letter spacing is recommended to add a touch of "boutique" modernism.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model to ensure a curated, "framed" appearance on larger screens. Elements are aligned to a 12-column grid with generous 24px gutters.

The spacing rhythm is intentionally "loose." Rather than packing information, this design system mandates wide margins and significant vertical padding (80px+) between sections to prevent cognitive overload. Use the 8px base unit for all component-level spacing to maintain a mathematical harmony throughout the interface.

## Elevation & Depth

Hierarchy is achieved through **Tonal Layers** rather than heavy shadows. 

1. **Base Layer:** The soft Ivory neutral (#F9F8F6).
2. **Raised Layer:** Surfaces that need to stand out (like cards) use the Tertiary Stone color (#E5E1D8) or a pure white with a very soft, diffused ambient shadow (8% opacity, 12px blur, 4px offset).
3. **Interactive Depth:** When an element is engaged, use a subtle "glow" or a color shift to the Primary Sage Green, rather than a significant increase in shadow depth.

The goal is to feel like paper or smooth stone layers resting gently on top of one another.

## Shapes

The shape language is **Soft** but structured. 

A base radius of 0.25rem (4px) is used for input fields and small buttons to maintain a sense of professional precision. Larger containers and cards use a rounded-lg (8px) or rounded-xl (12px) treatment to soften the overall visual weight. 

Avoid "pill" shapes for buttons to maintain the sophisticated, high-end aesthetic; instead, stick to soft-cornered rectangles that feel more architectural and grounded.

## Components

### Buttons
Primary buttons should be solid Sage Green with white text, utilizing the "Soft" corner radius. Secondary buttons should be ghost-style with a thin 1px border in the Primary color. All hover states should be gentle—a slight opacity change or a soft color shift.

### Cards
Cards for services or blog posts should have no borders. Use the Stone neutral background to differentiate them from the Ivory page background. Text within cards should have ample internal padding (minimum 24px).

### Input Fields
Inputs should be minimalist: a 1px border in a muted neutral, using the Secondary Sand color for the focus state. Labels should use the "label-caps" typographic style for a high-end feel.

### Chips & Tags
Used for selecting massage types or durations. These should have a background of the Tertiary Stone color and transition to a solid Secondary Sand or Primary Sage when selected.

### Date/Time Pickers
These should be presented as a clean, open grid without heavy lines. Selected dates should be highlighted with a soft Sage circle, emphasizing a "calm schedule" rather than a rigid appointment book.