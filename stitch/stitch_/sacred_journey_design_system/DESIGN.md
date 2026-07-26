---
name: Sacred Journey Design System
colors:
  surface: '#fcf8f9'
  surface-dim: '#dcd9da'
  surface-bright: '#fcf8f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f4'
  surface-container: '#f0edee'
  surface-container-high: '#eae7e8'
  surface-container-highest: '#e5e2e3'
  on-surface: '#1b1b1c'
  on-surface-variant: '#414943'
  inverse-surface: '#303031'
  inverse-on-surface: '#f3f0f1'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3b6751'
  primary: '#001b0f'
  on-primary: '#ffffff'
  primary-container: '#013220'
  on-primary-container: '#6f9c84'
  inverse-primary: '#a2d1b7'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#161712'
  on-tertiary: '#ffffff'
  tertiary-container: '#2b2b26'
  on-tertiary-container: '#93928b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bdedd2'
  primary-fixed-dim: '#a2d1b7'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#234f3b'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e5e2db'
  tertiary-fixed-dim: '#c9c6bf'
  on-tertiary-fixed: '#1c1c17'
  on-tertiary-fixed-variant: '#474741'
  background: '#fcf8f9'
  on-background: '#1b1b1c'
  surface-variant: '#e5e2e3'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: IBM Plex Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: IBM Plex Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: IBM Plex Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
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
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
The brand personality is rooted in the concept of "Sakinah" (tranquility) and "Ihsan" (excellence). It serves a target audience of pilgrims seeking a seamless, high-end Umrah experience that balances spiritual devotion with modern efficiency. 

The design style is **Minimalism** infused with **Subtle Islamic Geometry**. By utilizing heavy whitespace and a restricted, prestigious color palette, the UI creates a sense of calm and focus. Design elements should feel intentional and quiet, allowing the sacred imagery of the Two Holy Mosques to remain the focal point. This design system avoids visual clutter, favoring a structured, editorial-inspired layout that evokes trust and reverence.

## Colors
The palette is a sophisticated trio that reflects the heritage and sanctity of the pilgrimage:

- **Deep Mosque Green (#013220):** Our primary color, representing the traditions of Islam, growth, and serenity. It is used for primary navigation, core brand elements, and high-level headings.
- **Zari Gold (#D4AF37):** Our secondary accent, inspired by the Kiswah's embroidery. Used sparingly for highlights, call-to-action buttons, and premium indicators to convey quality.
- **Sacred White & Parchment (#FFFFFF, #F9F6EE):** The foundational colors that ensure the interface feels breathable and pure.
- **Obsidian Neutral (#1A1A1B):** Used for body text to ensure maximum legibility against light backgrounds.

## Typography
The typography system pairs a timeless serif with a structured sans-serif to bridge the gap between tradition and modern utility.

- **Headlines:** `notoSerif` is used for all major headings and display text. Its elegant, high-contrast strokes provide an authoritative yet welcoming tone.
- **Body & UI:** `ibmPlexSans` provides the industrial-grade clarity needed for travel itineraries, booking details, and technical information. Its neutral architecture balances the more expressive nature of the serif headings.
- **Hierarchy:** Maintain a clear vertical rhythm by ensuring body text never exceeds 65 characters per line for optimal readability during long-form reading of travel guides or package details.

## Layout & Spacing
The design system utilizes a **12-column fixed grid** for desktop and a **4-column fluid grid** for mobile devices. 

- **The Golden Ratio:** Use generous padding (spacing units of 24px, 32px, or 48px) to separate distinct content blocks, ensuring the "Sacred Journey" never feels cramped or rushed.
- **Desktop:** Content is centered with a max-width of 1280px. Use 64px outer margins to create a letterbox effect that feels like a premium travel brochure.
- **Mobile:** Margins are reduced to 20px, but vertical spacing between elements remains high to maintain the sense of elegance.
- **Islamic Accents:** Use a 4px or 8px grid for micro-spacing to ensure alignment of icons and small UI labels.

## Elevation & Depth
To maintain a modern aesthetic, this design system uses **Tonal Layering** and **Minimal Ambient Shadows**. 

- **Surfaces:** Use `#F9F6EE` (Parchment) as a secondary surface color to sit on top of pure white backgrounds. This creates soft depth without the need for heavy shadows.
- **Shadows:** When necessary for interactive elements like cards, use a very soft, diffused shadow: `0px 4px 20px rgba(1, 50, 32, 0.05)`. Note the slight green tint in the shadow to harmonize with the primary brand color.
- **Outlines:** Use 1px solid borders in a very light grey or gold-tinted cream to define containers, rather than relying on heavy drop shadows.

## Shapes
The shape language avoids sharp, aggressive corners in favor of **Rounded** geometry (0.5rem base radius). 

This softening of the UI elements reflects the "gentleness" and "mercy" inherent in the spiritual journey. Large containers, such as hero images or package cards, should utilize `rounded-lg` or `rounded-xl` to feel modern and high-end. Small elements like chips or badges may use pill shapes to contrast against the more structured rectangular cards.

## Components
- **Buttons:** Primary buttons use the Dark Green background with White text. Secondary buttons utilize a Gold border with Gold text. On hover, primary buttons should transition to a subtle Gold gradient (linear-gradient(135deg, #D4AF37 0%, #B8860B 100%)) to signal premium interactivity.
- **Package Cards:** These are the centerpiece. Use a high-quality photo at the top with a `rounded-t` corner. Below the photo, use a Gold divider line (1px) before the package title and pricing.
- **Chips/Badges:** Use these for "Standard," "Premium," or "VIP" package labels. They should be pill-shaped with a low-opacity background of the primary color and dark green text.
- **Inputs:** Clean, outlined fields with a 1px border. On focus, the border color changes to Gold to provide clear, elegant feedback.
- **Patterns:** Apply subtle Arabesque or geometric star patterns as background watermarks (opacity 0.03) or as decorative footers for cards to reinforce the Islamic identity without distracting from the content.
- **Navigation:** A clean, centered logo with menu items in `label-sm` typography. The active state is indicated by a small Gold dot beneath the navigation text.