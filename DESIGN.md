---
name: Structural Integrity
colors:
  surface: '#f8f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f8f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#edeef0'
  surface-container-high: '#e7e8ea'
  surface-container-highest: '#e1e2e4'
  on-surface: '#191c1e'
  on-surface-variant: '#43474e'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f3'
  outline: '#73777f'
  outline-variant: '#c3c6cf'
  surface-tint: '#436084'
  primary: '#002444'
  on-primary: '#ffffff'
  primary-container: '#1a3a5c'
  on-primary-container: '#87a4cc'
  inverse-primary: '#abc9f2'
  secondary: '#20609f'
  on-secondary: '#ffffff'
  secondary-container: '#83b9fe'
  on-secondary-container: '#004981'
  tertiary: '#002446'
  on-tertiary: '#ffffff'
  tertiary-container: '#003a6a'
  on-tertiary-container: '#57a5ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4ff'
  primary-fixed-dim: '#abc9f2'
  on-primary-fixed: '#001c37'
  on-primary-fixed-variant: '#2a486b'
  secondary-fixed: '#d3e4ff'
  secondary-fixed-dim: '#a2c9ff'
  on-secondary-fixed: '#001c38'
  on-secondary-fixed-variant: '#004881'
  tertiary-fixed: '#d3e4ff'
  tertiary-fixed-dim: '#a3c9ff'
  on-tertiary-fixed: '#001c38'
  on-tertiary-fixed-variant: '#004882'
  background: '#f8f9fb'
  on-background: '#191c1e'
  surface-variant: '#e1e2e4'
  background-alt: '#eaf3fb'
  surface-card: '#ffffff'
  text-main: '#1a1a2e'
  text-muted: '#4a5568'
  accent-gold: '#f5c518'
  cta-hover: '#1a5fa8'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 36px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Open Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-lg:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '600'
    lineHeight: '1.0'
  label-sm:
    fontFamily: Open Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  section-padding-desktop: 80px
  section-padding-mobile: 48px
---

## Brand & Style

This design system is built for a premium home renovation firm in Valencia with two decades of expertise. The brand personality is **authoritative, dependable, and meticulous**, reflecting the craftsmanship required for large-scale structural changes. 

The chosen style is **Corporate / Modern**, characterized by a structured grid, clear information hierarchy, and a rhythmic use of alternating background sections to guide the user's journey. It avoids unnecessary flourishes in favor of a clean, substantial aesthetic that emphasizes stability and longevity. Visual interest is introduced through subtle SVG wave separators and a sophisticated layering of tonal blues, creating a sense of professional depth.

## Colors

The palette is a monochrome exploration of blue, communicating trust and technical precision. 

- **Primary (#1a3a5c):** Used for structural elements like headers, footers, and high-impact hero backgrounds.
- **Secondary (#1e5f9e):** Reserved for borders, secondary actions, and iconography.
- **Action/Tertiary (#2e86de):** The high-visibility blue for primary Calls to Action and active states.
- **Neutrals:** The canvas uses a "Blanco Roto" (#f7f8fa) for general backgrounds to reduce eye strain, while pure white is reserved for cards and form inputs to make them pop.
- **Accent (#f5c518):** A golden yellow used sparingly for trust indicators like star ratings, badges, and certification icons.

## Typography

The typography strategy pairs the geometric strength of **Montserrat** with the exceptional readability of **Open Sans**.

- **Headlines:** Montserrat is utilized in Bold and ExtraBold weights to convey a sense of architectural permanence and strength.
- **Body:** Open Sans provides a neutral, friendly, and highly legible experience for long-form descriptions and service details. 
- **Buttons & UI Labels:** Montserrat SemiBold is used for interface elements to maintain the brand’s "bold" personality even at smaller scales.
- **Mobile Scaling:** Large display headings scale down significantly for mobile devices to ensure readability and prevent awkward word breaks on narrow screens.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop screens, centering content within a 1200px container to ensure a premium, editorial feel. 

- **Vertical Rhythm:** A systematic approach to section padding (80px on desktop) creates clear visual separation between service blocks. 
- **Transitions:** Soft SVG wave separators should be used between sections of different background colors (e.g., transitioning from #f7f8fa to #eaf3fb) to soften the structural grid and add a modern touch.
- **Responsive Behavior:** On mobile, margins shrink to 16px. Elements within cards and lists should stack vertically to maintain tap targets and legibility.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Ambient Shadows** rather than heavy outlines.

- **Surface Strategy:** Backgrounds alternate between off-white and very light blue to define different content areas. 
- **Shadows:** A signature shadow `0 4px 20px rgba(0,0,0,0.08)` is applied to cards and floating elements. This shadow is intentionally soft and diffused, suggesting that the UI elements are resting gently above the surface.
- **Depth in Interaction:** Buttons and interactive cards may lift slightly on hover, increasing the shadow spread to `0 8px 30px rgba(0,0,0,0.12)` to provide tactile feedback.

## Shapes

The design system utilizes a **Rounded** shape language to balance the "serious" nature of the industry with a modern, approachable feel.

- **Cards:** Use a standard 8px (0.5rem) radius to create a sturdy, container-like feel.
- **Buttons:** Use a slightly tighter 6px (0.375rem) radius to differentiate them from larger layout containers while maintaining the professional aesthetic.
- **Iconography:** Use line-style (outline) icons with a 2px stroke weight. These should be rendered in the Secondary Blue (#1e5f9e) to maintain brand cohesion.

## Components

### Buttons
- **Primary:** Tertiary Blue (#2e86de) background, White text, 6px radius. Hover state shifts to #1a5fa8.
- **Secondary:** White background with a 1px border of Secondary Blue (#1e5f9e). Text in Secondary Blue.

### Cards
- **Style:** Pure White (#ffffff) background, 8px radius, signature soft shadow. 
- **Usage:** Project showcases and service summaries. Padding should be generous (24px-32px) to maintain a premium feel.

### Input Fields
- **Style:** Pure White background, 1px border in #4a5568 (low opacity), 6px radius. Focus state uses a 2px border of Tertiary Blue.

### Chips & Badges
- **Accents:** Use the Gold (#f5c518) for "Completed Projects" or "Verified" badges to draw immediate trust.
- **Tags:** Light Blue (#eaf3fb) background with Primary Blue text for category tags (e.g., "Kitchens," "Bathrooms").

### Navigation
- **Header:** Primary Blue (#1a3a5c) background with White text. Links should use Montserrat SemiBold.
- **Sticky State:** Transition to a slightly translucent version of the Primary Blue with a subtle backdrop blur.