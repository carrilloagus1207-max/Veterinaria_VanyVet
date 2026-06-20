---
name: VanyVet Design System
colors:
  surface: '#f8fafa'
  surface-dim: '#d8dada'
  surface-bright: '#f8fafa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f4'
  surface-container: '#eceeee'
  surface-container-high: '#e6e8e9'
  surface-container-highest: '#e1e3e3'
  on-surface: '#191c1d'
  on-surface-variant: '#3e4946'
  inverse-surface: '#2e3131'
  inverse-on-surface: '#eff1f1'
  outline: '#6e7a76'
  outline-variant: '#bdc9c5'
  surface-tint: '#006b5d'
  primary: '#006b5d'
  on-primary: '#ffffff'
  primary-container: '#76d7c4'
  on-primary-container: '#005d51'
  inverse-primary: '#76d7c4'
  secondary: '#9e412e'
  on-secondary: '#ffffff'
  secondary-container: '#fe8b72'
  on-secondary-container: '#752313'
  tertiary: '#0060ac'
  on-tertiary: '#ffffff'
  tertiary-container: '#a3c8ff'
  on-tertiary-container: '#005396'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#93f4e0'
  primary-fixed-dim: '#76d7c4'
  on-primary-fixed: '#00201b'
  on-primary-fixed-variant: '#005046'
  secondary-fixed: '#ffdad3'
  secondary-fixed-dim: '#ffb4a4'
  on-secondary-fixed: '#3e0500'
  on-secondary-fixed-variant: '#7e2b19'
  tertiary-fixed: '#d4e3ff'
  tertiary-fixed-dim: '#a4c9ff'
  on-tertiary-fixed: '#001c39'
  on-tertiary-fixed-variant: '#004883'
  background: '#f8fafa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e3'
typography:
  display-lg:
    fontFamily: Quicksand
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Quicksand
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Quicksand
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
  title-md:
    fontFamily: Quicksand
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Nunito Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Nunito Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Nunito Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.01em
  caption:
    fontFamily: Nunito Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 40px
  xl: 64px
  container-padding: 20px
  gutter: 16px
---

## Brand & Style
The design system is centered on the intersection of medical precision and empathetic care. The brand personality is "The Trusted Companion"—professional enough to handle medical emergencies, yet soft enough to comfort a worried pet owner. 

The visual style follows a **Modern/Minimalist** approach with a **Tactile Softness**. By utilizing expansive whitespace and high-quality imagery of healthy animals, the UI reduces the cognitive load and anxiety often associated with veterinary visits. The aesthetic is "Cloud-like," prioritizing smooth transitions, large touch targets, and a lack of aggressive sharp edges to evoke a sense of safety and calm.

## Colors
The palette is designed to be therapeutic.
- **Primary (Mint Green):** Used for the dominant brand presence, success states, and primary navigation backgrounds. It represents health and vitality.
- **Secondary (Warm Coral):** Reserved strictly for Call-to-Actions (CTAs) and urgent notifications. Its warmth contrasts the cool mint without feeling alarming.
- **Neutral Surface:** A very faint, cool-toned white is used for backgrounds to reduce screen glare and maintain a "sterile but soft" clinic feel.
- **Text:** Deep charcoal instead of pure black is used to maintain high legibility while appearing softer to the eye.

## Typography
This design system utilizes a dual-font strategy to balance character with readability.
- **Headlines (Quicksand):** The rounded terminals of Quicksand provide a friendly, approachable look that feels "organic" and pet-friendly.
- **Body & Labels (Nunito Sans):** While still rounded, Nunito Sans offers better legibility at smaller scales for medical records, dosage instructions, and appointment details.

For mobile, headlines scale down slightly to ensure high-impact text doesn't break into awkward line fragments. All body text maintains a generous line height to assist users who may be viewing the app in stressful, "on-the-go" situations.

## Layout & Spacing
The layout follows a **Fluid Grid** model optimized for mobile-first usage. 
- **Mobile (Default):** 4-column grid with 20px side margins. 
- **Desktop:** 12-column centered grid with a max-width of 1200px.

Spacing is generous to promote a "breathable" atmosphere. Avoid crowding elements; medical information should be grouped logically using the `md` (24px) spacing unit between sections. The 8px base unit ensures all elements align to a consistent rhythmic scale.

## Elevation & Depth
Depth is achieved through **Tonal Layering** and **Soft Ambient Shadows** rather than harsh outlines.
- **Surface Level 0:** The neutral background (#F8FAFA).
- **Surface Level 1 (Cards):** Pure white (#FFFFFF) with a very soft, diffused shadow (Y: 4px, Blur: 20px, Opacity: 4% Black).
- **Surface Level 2 (Modals/Overlays):** Pure white with a more pronounced shadow (Y: 8px, Blur: 30px, Opacity: 8% Black).

This hierarchy creates a "stacked paper" effect that feels tactile and organized.

## Shapes
Shapes in the design system are heavily rounded to eliminate visual tension. 
- **Standard Radius:** 0.5rem (8px) for input fields and small components.
- **Large Radius (Cards/Buttons):** 1rem (16px) to create the "friendly" aesthetic.
- **Extra Large (Images):** 1.5rem (24px) for pet profile photos and featured clinic images.
- **Pill Shapes:** Used for status indicators (e.g., "Confirmed", "Vaccinated") and secondary chips.

## Components
- **Buttons:** Primary buttons use the secondary Coral color with white text. They should have a subtle 2px bottom "press" shadow to feel tactile.
- **Input Fields:** Large tap areas (min 48px height) with soft grey borders that turn Mint Green on focus.
- **Pet Cards:** These are the centerpiece. They should feature a large rounded avatar, the pet's name in `title-md`, and quick-action icons (medical history, next appointment).
- **Progressive Disclosure:** Use accordions for medical records to keep the interface clean, only showing complex data when requested.
- **Chips:** Small, pill-shaped tags used for pet categories (Cat, Dog, Exotic) or urgency levels.
- **Iconography:** Use 2px stroke weight with rounded caps. Incorporate pet-centric motifs like paw-shaped heart icons for "Favorites" or "Health Tracking."