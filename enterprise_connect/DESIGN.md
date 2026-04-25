---
name: Enterprise Connect
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daef'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8fd'
  surface-container-highest: '#dce2f7'
  on-surface: '#141b2b'
  on-surface-variant: '#594140'
  inverse-surface: '#293040'
  inverse-on-surface: '#edf0ff'
  outline: '#8d706f'
  outline-variant: '#e1bebd'
  surface-tint: '#b22834'
  primary: '#5e0010'
  on-primary: '#ffffff'
  primary-container: '#88001b'
  on-primary-container: '#ff8c8c'
  inverse-primary: '#ffb3b1'
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#380081'
  on-tertiary: '#ffffff'
  tertiary-container: '#5300b8'
  on-tertiary-container: '#bd9cff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3b1'
  on-primary-fixed: '#410008'
  on-primary-fixed-variant: '#900920'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#eaddff'
  tertiary-fixed-dim: '#d2bbff'
  on-tertiary-fixed: '#25005a'
  on-tertiary-fixed-variant: '#5a00c6'
  background: '#f9f9ff'
  on-background: '#141b2b'
  surface-variant: '#dce2f7'
typography:
  display-xl:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '700'
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
    lineHeight: '1.5'
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 1.5rem
  section-padding: 5rem
  stack-sm: 0.5rem
  stack-md: 1.5rem
  stack-lg: 3rem
---

## Brand & Style

The design system is anchored in a **Corporate / Modern** aesthetic, specifically tailored for enterprise-grade communication services. It balances authority with accessibility, aiming to evoke a sense of reliability, global scale, and technical precision. 

The visual language uses a high-density information layout tempered by generous vertical breathing room between sections. It avoids the austerity of traditional banking UIs by introducing soft color washes and rounded geometries, ensuring the brand feels "high-touch" rather than just "high-tech." The audience is composed of business decision-makers who value uptime, security (ISO certified), and seamless integration.

## Colors

The color palette is built on a foundation of professional high-contrast tones. 

- **Primary Maroon:** Used for critical calls to action, headers, and brand-heavy components. It conveys maturity and established authority.
- **Electric Blue:** Acts as the functional secondary color, used for links, informational tags, and specific service icons to represent "tech" and "connectivity."
- **Lavender Tint:** A very soft background wash is used to differentiate sections (e.g., the "Why Choose Us" and "FAQ" areas) from the primary white surface, creating a subtle layered effect without the need for heavy borders.
- **Neutral Palette:** Utilizes deep charcoals for typography and soft greys for borders and secondary text to maintain a high level of readability.

## Typography

This design system employs a dual-font strategy to balance character with utility. 

**Manrope** is used for all headlines and display text. Its geometric yet slightly warm proportions make large-scale marketing copy feel approachable but professional. High font weights (Bold/ExtraBold) are preferred for section headers to create a clear visual hierarchy.

**Inter** is the workhorse for all UI elements, body copy, and technical details. Chosen for its exceptional legibility at small sizes and its neutral, systematic feel, it ensures that long-form feature lists and pricing details remain easy to scan.

## Elevation & Depth

Hierarchy in this design system is achieved through **Tonal Layers** and **Ambient Shadows**.

1.  **Level 0 (Base):** Pure white (#FFFFFF) or the Lavender Tint background.
2.  **Level 1 (Cards):** Surfaces use a pure white background with a very soft, diffused shadow (0px 4px 20px rgba(0,0,0,0.05)) to lift them slightly off the tinted background.
3.  **Interactive States:** On hover, cards may increase their shadow spread or introduce a subtle colored border (Primary Maroon or Secondary Blue) to indicate interactivity.
4.  **Flat Accents:** Small UI elements like badges and chips use flat fills with no elevation to remain secondary to the main content cards.

## Shapes

The shape language is consistently **Rounded**, softening the corporate edge of the brand.

- **Cards & Containers:** Utilize a 16px (1rem) corner radius, creating a modern, friendly frame for content.
- **Interactive Elements:** Buttons are primarily pill-shaped (fully rounded) to maximize their "clickability" and distinguish them from static structural elements.
- **Iconography:** Icons are housed within rounded squares or circles with soft background fills that match the icon's primary color at a lower opacity.

## Components

### Buttons
- **Primary:** Pill-shaped, Solid Maroon background, White text. Includes a right-pointing arrow icon for directional flow.
- **Secondary/Ghost:** Pill-shaped, transparent background with a thin grey border or simple underline for "Learn More" links.
- **Floating Chat:** A prominent circular button fixed to the bottom right, using a high-contrast dark fill.

### Cards
- **Service Cards:** White background, 16px border radius, subtle shadow. Features a colorful icon at the top left, followed by a Bold headline and a bulleted list of features.
- **Pricing Cards:** Feature a prominent "Most Popular" badge. The primary card in a set uses a dark fill or a heavy border to create a focal point.

### Lists & Inputs
- **Feature Lists:** Use custom-colored checkmarks (often green) to signify positive benefits.
- **Input Fields:** Minimalist design with a light grey border, 8px radius, and high-contrast placeholder text.

### Accordions (FAQ)
- Clean, full-width rows with a subtle bottom border and a chevron toggle. The question is weighted more heavily than the answer text.