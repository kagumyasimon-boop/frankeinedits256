---
name: Cinematic Mastery
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#59dad1'
  on-secondary: '#003734'
  secondary-container: '#00a8a0'
  on-secondary-container: '#003532'
  tertiary: '#ffc293'
  on-tertiary: '#4d2600'
  tertiary-container: '#ff9b3f'
  on-tertiary-container: '#6c3800'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#79f6ed'
  secondary-fixed-dim: '#59dad1'
  on-secondary-fixed: '#00201e'
  on-secondary-fixed-variant: '#00504c'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#ffb77d'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3900'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0em
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
  body-sm:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0.02em
  label-lg:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.08em
  label-md:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin: 64px
---

## Brand & Style

The design system is anchored in the world of high-end visual post-production, evoking the atmosphere of a professional color grading suite. The brand personality is authoritative, meticulous, and artistic, catering to an audience that values technical precision and aesthetic soul.

The chosen style is **Minimalist Glassmorphism**. This approach utilizes deep, atmospheric backgrounds with translucent, "frosted" interface layers that mimic the look of high-end studio hardware and professional editing software. The interface focuses on content-first presentation, using generous whitespace—or rather, "darkspace"—to let imagery and cinematography take center stage. Every interaction should feel deliberate and smooth, mirroring the fluid nature of color grading.

## Colors

The palette is rooted in a "Darkroom" philosophy. The foundation is a deep, neutral charcoal that provides the necessary contrast for color-accurate work.

- **Primary (Muted Gold):** Used sparingly for high-level branding and primary calls to action. It represents the "premium" nature of the craft.
- **Secondary (Teal):** Used for functional accents, active states, and secondary information, providing a cool balance to the palette.
- **Tertiary (Orange):** Used for highlights, hover states, or "Rec" indicators, completing the classic cinematic complementary pairing.
- **Neutral:** A range of deep grays and charcoals to create depth without introducing color cast that could interfere with the perception of on-screen imagery.

## Typography

This design system employs a sophisticated typographic pairing to balance tradition with modernity. 

**Noto Serif** is reserved for headlines. Its classic, elegant letterforms convey a sense of editorial authority and artistic history. It should be used with tight letter spacing in large formats to feel like a film title.

**Manrope** serves as the functional workhorse for body text and UI labels. Its geometric yet approachable structure ensures maximum readability in dark environments. For UI labels and metadata, use upper-case styling with increased letter spacing to emulate the technical markings found on professional lenses and monitors.

## Layout & Spacing

The layout utilizes a **Fixed Grid** model for editorial content and a **Fluid Grid** for production tools and galleries. 

- **The Editorial Grid:** A centered 12-column grid with a max-width of 1440px, using wide margins (64px) to create a "letterboxed" cinematic feel.
- **The Spacing Rhythm:** Built on an 8px linear scale. Large-scale vertical rhythm (48px or 80px) should be used between major sections to maintain an airy, high-end feel.
- **Component Padding:** Elements like cards and modals should use generous internal padding (24px+) to prevent the UI from feeling "cramped" or "technical-heavy."

## Elevation & Depth

Hierarchy is established through **Backdrop Blurs** and **Low-Contrast Outlines** rather than heavy shadows.

- **Surface 1 (Base):** The deepest charcoal (#121212).
- **Surface 2 (Containers):** A slightly lighter charcoal (#1A1A1A) with a subtle 1px border (#ffffff10).
- **Surface 3 (Overlays/Modals):** A semi-transparent layer (approx. 80% opacity) with a 20px backdrop blur. This creates a "glass" effect that allows the underlying colors of video or film stills to bleed through softly.
- **Glows:** Instead of shadows, use subtle, colored outer glows (Teal or Gold) at extremely low opacities (10-15%) to indicate active or "in-focus" states, mimicking the light emission of a high-end monitor.

## Shapes

The shape language is **Soft (0.25rem)**. This subtle rounding provides a modern touch while maintaining a professional, structured edge. 

Buttons and input fields should utilize this small radius to appear precise. Larger containers, such as project cards or video players, can scale up to `rounded-lg` (0.5rem) to soften the overall composition. Avoid pill-shapes entirely, as they are too casual for this professional context; keep shapes rectangular and grounded.

## Components

- **Buttons:** Primary buttons use a solid Muted Gold with dark text. Secondary buttons are "Ghost" style with a Teal 1px border and Teal text. Use a slow transition (300ms) for hover states.
- **Inputs:** Fields should be dark with a bottom-border only or a very subtle 4-sided stroke. On focus, the border transitions to Teal with a very faint glow.
- **Cards:** Project cards should feature edge-to-edge imagery. Metadata (title, frame rate, color space) appears on a glassmorphic overlay that slides up or fades in on hover.
- **Chips/Badges:** Use for technical tags (e.g., "4K", "RAW", "LOG"). These should have a dark background, light-gray text, and a subtle border.
- **Selection Controls:** Checkboxes and radios should be minimal. When active, they should use a Teal fill.
- **Specialty Components:** 
    - **Histogram/Waveform Viewers:** Monochromatic (Teal or White) data visualizations with high transparency.
    - **Color Swatch Strips:** Used for displaying the palette of a specific grade, presented as a horizontal sequence of rectangles with sharp corners.