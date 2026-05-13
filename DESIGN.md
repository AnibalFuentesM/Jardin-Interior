---
name: Jardín Interior
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
  on-surface-variant: '#424844'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#727974'
  outline-variant: '#c1c8c3'
  surface-tint: '#466557'
  primary: '#163428'
  on-primary: '#ffffff'
  primary-container: '#2d4b3e'
  on-primary-container: '#99baa9'
  inverse-primary: '#adcebd'
  secondary: '#53634e'
  on-secondary: '#ffffff'
  secondary-container: '#d6e8ce'
  on-secondary-container: '#596954'
  tertiary: '#521f0b'
  on-tertiary: '#ffffff'
  tertiary-container: '#6e351f'
  on-tertiary-container: '#f09f82'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c8ead8'
  primary-fixed-dim: '#adcebd'
  on-primary-fixed: '#012116'
  on-primary-fixed-variant: '#2f4d40'
  secondary-fixed: '#d6e8ce'
  secondary-fixed-dim: '#baccb3'
  on-secondary-fixed: '#111f0f'
  on-secondary-fixed-variant: '#3c4b38'
  tertiary-fixed: '#ffdbcf'
  tertiary-fixed-dim: '#ffb59b'
  on-tertiary-fixed: '#380d00'
  on-tertiary-fixed-variant: '#703620'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  headline-xl:
    fontFamily: Literata
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Literata
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Literata
    fontSize: 28px
    fontWeight: '500'
    lineHeight: '1.3'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Manrope
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
  base: 8px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 80px
  max-width: 1280px
---

## Brand & Style
The brand personality is rooted in the concept of "emotional cultivation." This design system reflects a sanctuary-like environment where personal growth is nurtured through clinical expertise. The aesthetic bridges the gap between botanical organicism and medical professionalism. 

The style is **Modern Tactile**, utilizing soft-touch surfaces, ample whitespace, and organic shapes to evoke a sense of calm and safety. It prioritizes a "human-centric" interface that feels less like a digital tool and more like a gentle extension of a therapy room. The emotional response is one of relief, tranquility, and quiet confidence.

## Colors
The palette is derived from a sun-drenched conservatory. 
- **Primary (Forest):** A deep, grounding green used for primary navigation and high-level headings to establish authority and depth.
- **Secondary (Sage/Moss):** A muted, calming green for secondary actions and subtle backgrounds, representing soft growth.
- **Tertiary (Terracotta):** A warm earth tone used sparingly for emphasis, call-to-action highlights, and "warmth" in the UI.
- **Neutral (Cream & Sand):** The primary background colors are off-white (#F9F7F2) and soft sand (#EBE6D8) to avoid the sterile harshness of pure white.

Avoid high-contrast black; use a tinted charcoal (#242A28) for text to maintain a soft visual threshold.

## Typography
The typographic strategy balances the "Literary" elegance of a serif with the "Functional" clarity of a geometric sans-serif.

- **Headlines:** Literata provides a scholarly yet nurturing voice. It features organic terminals that feel hand-crafted.
- **Body & Interface:** Manrope ensures maximum readability and a professional, modern tone for clinical information and user inputs. 
- **Scale:** Large display type should be used generously in hero areas to create a sense of breathability and calm. All body text maintains a high line-height (1.6) to prevent visual density.

## Layout & Spacing
This design system utilizes a **Fixed Grid** approach on desktop to maintain "contained" and secure-feeling content blocks, while transitioning to a fluid model on mobile.

- **Rhythm:** An 8px linear scale governs all padding and margins.
- **Desktop:** 12-column grid with generous 80px side margins to create "breathing room."
- **Tablet:** 8-column grid with 40px margins.
- **Mobile:** 4-column grid with 20px margins.

Layouts should favor asymmetrical balance—much like a natural garden—using staggered imagery and offset text blocks to prevent a rigid, institutional feel.

## Elevation & Depth
Depth is created through **Tonal Layering** rather than aggressive shadows. 
- **Surface Tiers:** Backgrounds use the Cream neutral, while foreground cards use a slightly lighter "Paper" white or a very pale Moss green to indicate elevation.
- **Shadows:** When necessary, use "Botanical Shadows"—highly diffused (20px-40px blur), low opacity (5-8%), with a slight tint of the Primary Forest green. This creates a soft, ambient lift that feels like natural light filtering through leaves.
- **Glassmorphism:** Use subtle backdrop blurs (10px) on navigation headers to suggest transparency and openness.

## Shapes
The shape language is "Organic-Geometric." 
- **Corners:** A standard 0.5rem (8px) radius is used for small components like inputs, while a 1.5rem (24px) radius is reserved for large containers and cards to emphasize a "soft landing."
- **Organic Accents:** Use "blob" shapes or soft, non-uniform circles as background decorative elements behind photography to reinforce the garden theme.
- **Icons:** Use thin-stroke, rounded-end icons to maintain the gentle atmosphere.

## Components
- **Buttons:** Primary buttons feature the Forest green background with Cream text. Secondary buttons use a Terracotta outline for a warm, accessible touch. Always use rounded corners (min 8px).
- **Cards:** Large radius (24px) with a soft tinted shadow. Cards should have ample internal padding (32px+) to avoid crowding content.
- **Input Fields:** Soft sand background with a subtle Forest green border on focus. Labels use Manrope Semibold in the label-sm style.
- **Chips/Tags:** Used for therapy specializations (e.g., "Anxiety," "Mindfulness"). These should be pill-shaped with Sage backgrounds and Forest green text.
- **Lists:** Use custom botanical bullet points (e.g., a small leaf icon) instead of standard circles to reinforce the brand narrative.
- **Interactive States:** Hover states should involve a gentle shift in color temperature (e.g., Sage becoming slightly warmer) rather than a drastic change in brightness.
