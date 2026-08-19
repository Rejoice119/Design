---
name: Industrial Integrity System
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#48454e'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#79757f'
  outline-variant: '#c9c4cf'
  surface-tint: '#615888'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1d1441'
  on-primary-container: '#877db0'
  inverse-primary: '#cabff7'
  secondary: '#b02f00'
  on-secondary: '#ffffff'
  secondary-container: '#fd6537'
  on-secondary-container: '#5c1400'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#191c1e'
  on-tertiary-container: '#818486'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e6deff'
  primary-fixed-dim: '#cabff7'
  on-primary-fixed: '#1d1441'
  on-primary-fixed-variant: '#49406f'
  secondary-fixed: '#ffdbd1'
  secondary-fixed-dim: '#ffb5a0'
  on-secondary-fixed: '#3b0900'
  on-secondary-fixed-variant: '#862200'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
  technical-data:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  unit-1: 0.25rem
  unit-2: 0.5rem
  unit-4: 1rem
  unit-6: 1.5rem
  unit-8: 2rem
  unit-12: 3rem
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
---

## Brand & Style

This design system is engineered for the industrial sector, balancing B2B procurement complexity with B2C ease-of-use. The brand personality is authoritative, robust, and dependable—evoking the scale of large-scale manufacturing and infrastructure. 

The visual style is **Corporate Modern with a "Heavy-Industry" bias**. It utilizes high-contrast frames, generous white space for technical clarity, and a structural grid that feels architectural. Every element is designed to feel "bolted-in" and permanent, utilizing sharp precision and high-value materials (Navy and Terracotta) to communicate professional trust and Pan-African industrial leadership.

## Colors

The palette is anchored by **Roof Navy Blue (#1C1340)**, used for structural elements like headers, sidebar navigation, and primary headings to establish authority. 

**Terracotta Orange (#D84B1F)** serves as the high-visibility accent, reserved strictly for conversion-driving actions (Add to Cart, Request Quote, Submit) and critical status indicators. 

The background employs **Light Industrial Slate (#F8FAFC)** to reduce eye strain during long procurement sessions, while **Deep Charcoal (#0F172A)** ensures maximum legibility for technical specifications and data tables. Borders and dividers utilize **#E2E8F0** to maintain a clean, organized hierarchy without adding visual clutter.

## Typography

This design system uses **Inter** for all primary interfaces to leverage its exceptional legibility and neutral, professional tone. Headings are set with heavy weights (700-800) to mimic industrial signage and blueprint headers.

A specialized role, `technical-data`, uses **JetBrains Mono** to distinguish part numbers, dimensions, and SKU codes from descriptive text. This monospaced clarity is essential for B2B technical accuracy. All labels for categories and statuses should be uppercase with slightly increased letter spacing to enhance the "industrial plate" aesthetic.

## Layout & Spacing

The layout follows a **Fixed-Fluid Hybrid Grid**. On desktop, content is contained within a 1280px max-width 12-column grid to ensure readability on ultra-wide monitors common in logistics offices. 

A 4px baseline grid governs all vertical rhythm. Use larger gaps (unit-8 or unit-12) between major sections to emphasize the "massive" industrial feel. For technical data tables and product grids, use tight 1px borders with unit-4 gutters to maximize information density without losing organization.

**Breakpoints:**
- **Mobile (<768px):** 4-column grid, 16px margins.
- **Tablet (768px - 1024px):** 8-column grid, 24px margins.
- **Desktop (>1024px):** 12-column grid, fixed container.

## Elevation & Depth

To maintain a "heavy" and "grounded" feel, this design system avoids soft, floating shadows. Instead, it uses **Tonal Layers** and **Rigid Outlines**.

- **Surface Level 0:** #F8FAFC (Global Background).
- **Surface Level 1:** #FFFFFF (Cards, Content Blocks) with a 1px solid #E2E8F0 border.
- **Surface Level 2:** #FFFFFF with a subtle, tight 2px/4px blur shadow (Alpha 0.05) to indicate interactivity on hover.
- **Active State:** Terracotta Orange (#D84B1F) 2px interior border for focused input fields.

Depth is communicated through "recessed" input fields and "stamped" buttons, rather than high-elevation floating panels.

## Shapes

The shape language is **Soft-Industrial**. We use a 0.25rem (4px) base radius for standard components like buttons and inputs. This provides enough "machine-finished" quality to feel modern while maintaining the structural rigidity associated with industrial hardware. 

Avoid "Pill" shapes entirely, as they are too soft for this brand's authoritative tone. Large containers (Product Detail Cards) may use `rounded-lg` (8px) for a more refined look, but buttons must remain strictly at 4px.

## Components

### Buttons
- **Primary:** Background #D84B1F, Text #FFFFFF, 4px radius. Bold weight.
- **Secondary/Structural:** Background #1C1340, Text #FFFFFF. Used for Navigation or Quote History.
- **Outline:** Transparent background, 1px #E2E8F0 border, Text #0F172A.

### Product Cards
- Background #FFFFFF, Border 1px #E2E8F0. 
- Titles in #1C1340 (Navy), Prices in #0F172A (Deep Charcoal).
- On hover, the border darkens to #1C1340 and adds a slight elevation.

### Input Fields
- Background #FFFFFF, Border 1px #E2E8F0. 
- Labels must use `body-sm` in #0F172A. 
- Focused state uses a #D84B1F 1px border.

### Status Badges
- **In Stock:** Subtle green tint background with deep green text.
- **Out of Stock:** Subtle gray background with #0F172A text.
- **Low Stock/Urgent:** Subtle #D84B1F (Terracotta) tint with #D84B1F text.

### Technical Specification Tables
- Alternating row stripes (Zebra striping) using #F8FAFC and #FFFFFF.
- 1px #E2E8F0 horizontal dividers only.
- Headers are #1C1340 with #FFFFFF text for maximum visual anchor.