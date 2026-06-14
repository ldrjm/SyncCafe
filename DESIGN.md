---
name: Artisanal Productivity
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#504442'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#827472'
  outline-variant: '#d3c3c0'
  surface-tint: '#745853'
  primary: '#271310'
  on-primary: '#ffffff'
  primary-container: '#3e2723'
  on-primary-container: '#ae8d87'
  inverse-primary: '#e3beb8'
  secondary: '#50652a'
  on-secondary: '#ffffff'
  secondary-container: '#cfe99f'
  on-secondary-container: '#546a2e'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cba72f'
  on-tertiary-container: '#4e3d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#e3beb8'
  on-primary-fixed: '#2b1613'
  on-primary-fixed-variant: '#5b403c'
  secondary-fixed: '#d2eca2'
  secondary-fixed-dim: '#b6d088'
  on-secondary-fixed: '#131f00'
  on-secondary-fixed-variant: '#394d14'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  headline-xl:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  body-md:
    fontFamily: Hanken Grotesk
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
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style

The design system is rooted in the concept of "Productive Warmth." It bridges the gap between a high-end artisanal coffee house and a high-performance coworking environment. The aesthetic is **Minimalist-Modern** with a focus on **Tactile Quality**. 

The target audience consists of digital nomads, creative entrepreneurs, and students who value focus as much as they value a perfect pour-over. The UI should feel serene and professional, avoiding the clutter of typical "work" apps, while maintaining the welcoming, sensory appeal of a physical cafe.

Key visual pillars include:
- **Cleanliness:** Ample white space to reduce cognitive load.
- **Warmth:** Natural, earthy tones that prevent the digital interface from feeling sterile.
- **Precision:** Sharp alignment and refined typography that signal reliability and "high-performance infrastructure."

## Colors

The palette is a sophisticated blend of organic earth tones and metallic prestige.

- **Primary (Espresso):** A deep, rich coffee brown used for primary text, headers, and core branding elements. It provides the grounding force of the system.
- **Secondary (Olive):** A muted, professional green that represents the "coworking" aspect—growth, focus, and calm. Used for secondary actions and success states.
- **Tertiary (Gold):** A refined accent used sparingly for highlights, premium membership indicators, and "active" states.
- **Neutral (Parchment):** The background is not a pure white but a warm, textured off-white that mimics high-quality paper or a plaster wall, reducing eye strain during long work sessions.

## Typography

This design system utilizes **Hanken Grotesk** as the primary typeface. It is a clean, contemporary sans-serif that feels both engineered and human. To lean into the "technology" and "infrastructure" side of the coworking space, **JetBrains Mono** is used for small labels, data points (like Wi-Fi speeds or table numbers), and utility links.

- **Headlines:** Set in Hanken Grotesk with tight tracking to feel authoritative and modern.
- **Body:** Standardized for readability with generous line heights to facilitate comfortable reading.
- **Utility:** Monospaced labels provide a subtle "dev-tool" aesthetic that appeals to the tech-savvy target demographic.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to maintain the "contained" and "focused" feel of a physical space. 

- **Desktop:** A 12-column grid with a 1200px max-width. Large 40px margins create a "frame" around the content, emphasizing the premium nature of the brand.
- **Mobile:** A 4-column grid with 16px margins.
- **Rhythm:** An 8px base unit governs all spacing. Vertical rhythm is strictly enforced to ensure the UI feels as organized as a well-managed workstation.

## Elevation & Depth

To maintain a minimalist and tactile aesthetic, the system avoids heavy shadows. Instead, it uses **Tonal Layers** and **Low-Contrast Outlines**.

- **Surfaces:** Different levels of depth are achieved by shifting the background color from the base Neutral (#F9F7F2) to a slightly darker "Stone" tint.
- **Outlines:** Elements like cards and inputs use thin 1px borders in a soft brown-grey.
- **Active State:** A very soft, diffused shadow (15% opacity of the Primary color) is used only for floating elements like dropdowns or active modals to give them a "lift" off the page without breaking the minimalist aesthetic.

## Shapes

The shape language is **Soft (0.25rem)**. This subtle rounding removes the clinical "hardness" of 90-degree corners, making the interface feel more approachable and "cozy," while remaining sharp enough to look professional. 

Buttons and input fields should utilize the standard `rounded` (4px) setting. Containers like cards can scale up to `rounded-lg` (8px) to soften the overall layout.

## Components

### Buttons
- **Primary:** Solid Espresso (#3E2723) with white text. High contrast for clear "Book Table" or "Order Now" actions.
- **Secondary:** Outlined in Olive (#556B2F) with Olive text. Used for secondary tasks like "View Menu."
- **Tertiary/Ghost:** Text only in Espresso with a Gold (#D4AF37) underline on hover.

### Cards
- Cards use a subtle background fill and a 1px soft-brown border. Content inside cards should have generous internal padding (24px) to reflect the "spaciousness" of the cafe.

### Input Fields
- Understated design with a focus on the label (JetBrains Mono). The active state is indicated by a 2px Gold bottom border, signaling a "premium" focus when the user is typing.

### Status Chips
- Used for "Available Seats" or "Wi-Fi Strength." These are small, pill-shaped elements using the Secondary (Olive) color for positive states and a light Brown for neutral states.

### Interactive Elements
- Hover states should be gentle—typically a slight darkening of the background or a subtle shift in the Gold accent color. Transitions should be smooth (200ms) to mirror the calm atmosphere of the space.