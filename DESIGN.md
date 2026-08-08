---
name: Growth Partner
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
  on-surface-variant: '#434656'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#737688'
  outline-variant: '#c3c5d9'
  surface-tint: '#004ced'
  primary: '#003ec7'
  on-primary: '#ffffff'
  primary-container: '#0052ff'
  on-primary-container: '#dfe3ff'
  inverse-primary: '#b7c4ff'
  secondary: '#006e2a'
  on-secondary: '#ffffff'
  secondary-container: '#5cfd80'
  on-secondary-container: '#00732c'
  tertiary: '#6f4500'
  on-tertiary: '#ffffff'
  tertiary-container: '#905a00'
  on-tertiary-container: '#ffdfbe'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#001452'
  on-primary-fixed-variant: '#0038b6'
  secondary-fixed: '#69ff87'
  secondary-fixed-dim: '#3ce36a'
  on-secondary-fixed: '#002108'
  on-secondary-fixed-variant: '#00531e'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Montserrat
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
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  section-gap: 120px
---

## Brand & Style
The design system is engineered to project a blend of institutional reliability and modern agility. It targets local established businesses seeking digital transformation and global startups requiring high-velocity growth. 

The aesthetic sits within **Corporate / Modern** with a strong emphasis on **Minimalism**. It uses high-contrast typography and expansive whitespace to convey clarity of thought and results. Visual complexity is minimized to ensure the focus remains on performance data and success metrics. The emotional response should be one of "assured expertise"—the feeling that the user is in the hands of a senior-level strategic partner.

## Colors
The palette is centered on "Executive Blue" (#0052FF), a vibrant royal blue that signals tech-forwardness and stability. "Success Green" (#00C853) is used specifically for data visualizations and positive growth indicators, while "Momentum Orange" (#F59E0B) is reserved strictly for primary Conversion Actions to ensure high visibility.

The background uses a subtle off-white (#F8FAFC) to reduce eye strain, while the neutral palette is a deep navy-charcoal (#0F172A) instead of pure black, maintaining a premium feel.

## Typography
This design system utilizes a dual-sans-serif approach. **Montserrat** is used for headlines to provide a geometric, confident, and slightly urban character. **Inter** is utilized for all body copy and UI labels to ensure maximum legibility and a systematic, tech-centric feel.

Scale headlines aggressively to create a clear information hierarchy. Large "Display" sizes should be used for value propositions, while "Label" styles should be used for small metadata and overlines, always in semi-bold or bold to maintain authority.

## Layout & Spacing
The layout follows a **Fixed Grid** model for desktop (1280px max-width) and a **Fluid Grid** for mobile devices. A strict 8px base unit (linear scale) governs all padding and margins.

- **Desktop:** 12-column grid with 24px gutters.
- **Tablet:** 8-column grid with 24px gutters.
- **Mobile:** 4-column grid with 16px margins.

Section vertical spacing is intentional and generous (120px+) to allow the brand's message to breathe and to prevent the UI from feeling cluttered or "low-cost."

## Elevation & Depth
The design system employs **Tonal Layers** combined with **Ambient Shadows**. Depth is used sparingly to signify interactivity and priority.

- **Flat Surface:** Primary background, no shadow.
- **Raised Level:** Cards and containers use a very soft, highly diffused shadow (Blur: 30px, Y: 10px, Opacity: 4% Black) to create a subtle lift without being heavy.
- **Interaction Level:** On hover, elements should increase their shadow spread slightly and shift -2px on the Y-axis.
- **Overlays:** Modals use a background blur (12px) on the backdrop to maintain context while focusing the user's attention.

## Shapes
The shape language is defined by **Rounded** corners to bridge the gap between "Professional" and "Approachable." 

- **Standard Elements:** Buttons and input fields use a `0.5rem` radius.
- **Large Containers:** Cards and sections use `rounded-2xl` (1.5rem) to create a modern, friendly frame for content.
- **Visual Accents:** Icons and avatars should follow the same rounded logic, avoiding sharp 90-degree angles.

## Components
- **Buttons:** Primary CTAs use the secondary color (#F59E0B) with white text for maximum "pop." Secondary buttons use the primary blue as an outline or text-only link. Use a minimum height of 48px for touch-friendliness.
- **Input Fields:** Use a subtle 1px border (#E2E8F0) that transitions to the Primary Blue on focus. Labels should always be visible above the field (not placeholder-only).
- **Cards:** Cards are white with the `rounded-2xl` radius and the "Raised Level" ambient shadow. Use internal padding of at least 32px.
- **Chips:** Small, low-contrast pills used for tagging services (e.g., "SEO," "PPC"). Use a light tint of the primary blue with 70% opacity text.
- **Data Visuals:** Use the Success Green for all upward-trending line graphs and bar charts to reinforce the "Growth Partner" narrative.
- **Navigation:** A sticky top bar with high transparency and a backdrop blur of 20px to keep the UI feeling "airy."