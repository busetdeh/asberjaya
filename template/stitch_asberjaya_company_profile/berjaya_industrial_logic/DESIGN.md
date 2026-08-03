---
name: Berjaya Industrial Logic
colors:
  surface: '#f7fafc'
  surface-dim: '#d7dadc'
  surface-bright: '#f7fafc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f6'
  surface-container: '#ebeef0'
  surface-container-high: '#e5e9eb'
  surface-container-highest: '#e0e3e5'
  on-surface: '#181c1e'
  on-surface-variant: '#5d3f3c'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eef1f3'
  outline: '#926f6b'
  outline-variant: '#e7bdb8'
  surface-tint: '#c00014'
  primary: '#ba0013'
  on-primary: '#ffffff'
  primary-container: '#e31e24'
  on-primary-container: '#fffafa'
  inverse-primary: '#ffb4ab'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#385d8b'
  on-tertiary: '#ffffff'
  tertiary-container: '#5276a5'
  on-tertiary-container: '#fcfbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#93000d'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#d3e3ff'
  tertiary-fixed-dim: '#a5c9fd'
  on-tertiary-fixed: '#001c39'
  on-tertiary-fixed-variant: '#214875'
  background: '#f7fafc'
  on-background: '#181c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '700'
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
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

The design system for AS BERJAYA is built on the pillars of **precision, momentum, and industrial reliability**. It targets enterprise clients in the logistics and heavy machinery sectors who value efficiency and institutional strength.

The visual style is **Corporate Modern with Industrial accents**. It utilizes a structured grid, high-contrast color blocking, and bold typographic hierarchies to communicate movement (the "flow" of supply chains) and stability. By mixing the raw power of the logistics sector with a refined digital interface, the design system ensures the brand feels both grounded in physical reality and technologically forward-thinking.

## Colors

The palette is derived from the core brand identity, expanded for complex UI needs.

- **Primary Red (#E31E24):** Used for critical actions, highlights, and indicating momentum. It represents the energy and urgency of logistics.
- **Secondary Black (#1A1A1A):** Provides the "industrial" weight. Used for primary text and heavy structural elements.
- **Supportive Blue (#2B517E):** A deep, professional blue used for informational containers and secondary accents to build trust and calm.
- **Neutral Grays:** A range of cool-toned grays (from #F4F7F9 to #4A5568) are used for backgrounds, borders, and secondary text to maintain a clean, high-contrast environment.

## Typography

Typography focuses on immediate legibility and a "mechanical" precision.

- **Headlines:** Hanken Grotesk provides a sharp, contemporary grotesque feel. Use "ExtraBold" for display levels to mirror the weight of heavy machinery.
- **Body:** Inter is the workhorse for all functional text, ensuring readability across data-heavy logistics dashboards and long-form company profiles.
- **Labels:** JetBrains Mono is used for technical data, tracking numbers, and metadata. Its monospaced nature reinforces the feeling of systematic accuracy and digital tracking.

## Layout & Spacing

This design system utilizes a **12-column Fluid Grid** for desktop and a **4-column grid** for mobile. 

The layout logic follows an **8px hard grid** system. All vertical spacing and component heights must be multiples of 8. 

For high-level layout, use "industrial margins"—generous white space between sections to prevent the UI from feeling cluttered, but tight internal spacing within components (like data tables) to maintain information density. Reflow rules should prioritize vertical stacking on mobile while maintaining the "blocky" high-contrast sections seen in the brand's presentation style.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **High-Contrast Outlines** rather than traditional shadows.

1.  **Base Layer:** The light neutral gray (#F4F7F9) acts as the canvas.
2.  **Surface Layer:** White cards or sections are placed on the base layer, defined by subtle 1px borders in a mid-tone gray (#E2E8F0).
3.  **Accent Depth:** For primary callouts or "active" cards, a 4px solid offset "shadow" (Border-bottom and Border-right) in the Secondary Black can be used to evoke a more tactile, industrial feel.
4.  **Backdrop Blurs:** Use sparingly for navigation overlays or modals to maintain context without sacrificing the clean, professional aesthetic.

## Shapes

The shape language is primarily **Soft (0.25rem)** to reflect modern precision engineering. 

- **Standard Elements:** Buttons, inputs, and small cards use the base `rounded` (4px) setting.
- **Large Containers:** Hero sections or main content cards use `rounded-lg` (8px).
- **Industrial Icons:** Icons should be contained within square boxes with the same 4px radius, emphasizing the "containerized" nature of the logistics industry.
- **Pill Shapes:** Reserved exclusively for status indicators (e.g., "In Transit", "Delivered") to distinguish them from actionable buttons.

## Components

### Buttons
Primary buttons use the Brand Red with white text, featuring a subtle 2px bottom border of a darker red for a tactile feel. Secondary buttons use the Black or Blue with a ghost-style outline.

### Input Fields
Fields should have a solid 1px border. On focus, the border weight increases to 2px in the Brand Red. Labels use the monospaced font for a technical look.

### Cards
Cards are the primary container for services and data. They should use a white background with a subtle border. For AS BERJAYA, use a "Header Stripe"—a 4px vertical bar of Brand Red or Support Blue on the left edge of the card to categorize content.

### Status Chips
Utilize the pill-shape setting. Use high-contrast color pairings (e.g., Light Green background with Dark Green text) to ensure status is glanceable in high-speed operations.

### Data Lists
Lists should be dense and clean. Use alternating row colors (zebra striping) in very light grays to help users track information across wide screens.