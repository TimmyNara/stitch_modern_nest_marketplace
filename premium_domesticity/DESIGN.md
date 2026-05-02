---
name: Premium Domesticity
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1a'
  on-surface-variant: '#464740'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#77786f'
  outline-variant: '#c7c7bd'
  surface-tint: '#5c614d'
  primary: '#535845'
  on-primary: '#ffffff'
  primary-container: '#6b705c'
  on-primary-container: '#eff4db'
  inverse-primary: '#c4c9b1'
  secondary: '#625e57'
  on-secondary: '#ffffff'
  secondary-container: '#e6ded6'
  on-secondary-container: '#67625b'
  tertiary: '#485860'
  on-tertiary: '#ffffff'
  tertiary-container: '#617079'
  on-tertiary-container: '#e4f4fe'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e0e5cc'
  primary-fixed-dim: '#c4c9b1'
  on-primary-fixed: '#191d0e'
  on-primary-fixed-variant: '#444937'
  secondary-fixed: '#e9e1d9'
  secondary-fixed-dim: '#ccc5be'
  on-secondary-fixed: '#1e1b16'
  on-secondary-fixed-variant: '#4a4640'
  tertiary-fixed: '#d5e5ef'
  tertiary-fixed-dim: '#b9c9d3'
  on-tertiary-fixed: '#0e1d25'
  on-tertiary-fixed-variant: '#3a4951'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2e0'
typography:
  display:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '500'
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
    lineHeight: '1.6'
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-gap: 80px
---

## Brand & Style

The brand personality of this design system is grounded, serene, and intentional. It aims to evoke a sense of "quiet luxury" for the home, moving away from the frantic pace of traditional e-commerce toward a curated, editorial experience. The target audience values longevity and quality over trends, seeking a home environment that acts as a sanctuary.

This design system utilizes a **Minimalist** style with **Corporate Modern** refinements. It relies on generous whitespace, a restricted but warm color palette, and a focus on high-quality product photography. The aesthetic is "soft-modern"—achieving a professional and trustworthy feel through precision and order, while maintaining comfort through organic tones and rounded UI elements.

## Colors

The palette is designed to be receding and non-distracting, allowing the product imagery to provide the primary visual interest. 

- **Primary (Muted Sage):** Used for primary actions, success states, and subtle branding moments. It represents growth and domestic tranquility.
- **Secondary (Warm Beige):** Used for background containers, subtle separators, and secondary UI elements to provide warmth and depth without the sterility of pure gray.
- **Tertiary (Deep Slate):** Reserved for high-contrast typography and iconography to ensure maximum readability and a premium, authoritative feel.
- **Neutral (Bone White):** The primary canvas color. It is slightly warmer than pure white to reduce eye strain and create a "comfortable" digital environment.

Surface colors should prioritize a hierarchy of `Neutral` -> `Secondary` for nested elements.

## Typography

This design system uses **Inter** for all typographic needs to maintain a systematic and utilitarian clarity. The type scale is built on a modular rhythm to ensure a clean vertical flow.

Large display and headline styles utilize tighter letter spacing and heavier weights to feel "anchored" and premium. Body text uses a generous 1.6x line height to ensure maximum readability for long-form product descriptions and care guides. Labels and small metadata should use slightly increased letter spacing and medium-to-bold weights to maintain legibility even at small scales. Use the Deep Slate color for all primary text to provide a sophisticated contrast against the Bone White backgrounds.

## Layout & Spacing

This design system employs a **Fixed Grid** model for desktop viewports to maintain an editorial, boutique feel that prevents content from feeling overstretched. 

- **Desktop:** A 12-column grid with a 1280px maximum container width.
- **Gutter & Margins:** 24px gutters provide breathing room between product tiles. External margins of 40px ensure the content feels centered and prestigious.
- **Vertical Rhythm:** A strict 8px baseline grid is used. Sections are separated by large gaps (80px+) to emphasize the minimalist philosophy and allow the eye to rest.
- **Mobile:** Transition to a fluid 2-column or 1-column grid with 16px side margins to maximize screen real estate for product imagery.

## Elevation & Depth

To maintain a premium and modern aesthetic, this design system avoids heavy shadows in favor of **Tonal Layers** and **Ambient Shadows**.

Depth is primarily communicated through color shifts: the main background is Bone White, while "elevated" surfaces (like cards or menus) use subtle border-less containers with extremely soft, diffused shadows. Shadows should be low-offset (Y: 4px, Blur: 20px) and low-opacity (8-10%), tinted slightly with the Tertiary Slate color rather than pure black. This creates a "soft glow" effect that makes elements feel like they are gently resting on the surface rather than floating high above it.

## Shapes

The shape language of this design system is **Rounded**, strike a balance between geometric precision and organic softness. 

Standard components like buttons, input fields, and product thumbnails utilize a 0.5rem (8px) base radius. Larger containers, such as promotional banners or modal overlays, use a more pronounced 1rem (16px) radius. This roundedness echoes the comfort of household goods—furniture, ceramics, and textiles—avoiding sharp, aggressive corners in favor of a more approachable and trustworthy silhouette.

## Components

### Buttons
Primary buttons use a solid Muted Sage fill with white text, featuring a subtle hover state that deepens the green. Secondary buttons use a Deep Slate outline with no fill, conveying a lighter visual weight.

### Input Fields
Inputs are minimal: a 1px border using the Secondary Beige color, which shifts to Muted Sage upon focus. Labels should be placed above the field in the `label-md` style for clarity.

### Cards
Product cards are the centerpiece. They use a "no-border" approach, relying on the product image's own boundaries and generous internal padding (24px) to define the space. Use the `body-md` for product names and `label-lg` for pricing to create clear hierarchy.

### Chips & Tags
Used for product categories (e.g., "Sustainable", "New Arrival"). These should use the Secondary Beige fill with Tertiary Slate text, keeping them subtle so they do not compete with the primary Call-to-Action.

### Lists & Navigation
Navigation links should use `label-lg` with a subtle underline animation on hover. Lists in product details should use custom bullet points in Muted Sage to tie the branding together.

### Additional Components
- **Breadcrumbs:** Small, understated text in the header to facilitate easy navigation through categories.
- **Quantity Pickers:** Minimalist counters with + and - icons, avoiding the boxy look of standard browser inputs.