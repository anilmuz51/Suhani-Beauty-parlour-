---
name: Suhani Beauty Parlour Design System
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
  on-surface-variant: '#514440'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#84746f'
  outline-variant: '#d6c2bd'
  surface-tint: '#ba0061'
  primary: '#ba0061'
  on-primary: '#ffffff'
  primary-container: '#ff87af'
  on-primary-container: '#830043'
  inverse-primary: '#ffb1c7'
  secondary: '#76546a'
  on-secondary: '#ffffff'
  secondary-container: '#ffd3ed'
  on-secondary-container: '#7b586e'
  tertiary: '#685d4a'
  on-tertiary: '#ffffff'
  tertiary-container: '#b9ab94'
  on-tertiary-container: '#493f2e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e2'
  primary-fixed-dim: '#ffb1c7'
  on-primary-fixed: '#3e001d'
  on-primary-fixed-variant: '#8e0049'
  secondary-fixed: '#ffd8ee'
  secondary-fixed-dim: '#e5bad4'
  on-secondary-fixed: '#2d1225'
  on-secondary-fixed-variant: '#5d3d52'
  tertiary-fixed: '#f0e0c8'
  tertiary-fixed-dim: '#d3c5ad'
  on-tertiary-fixed: '#221b0b'
  on-tertiary-fixed-variant: '#4f4533'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2e0'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
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
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
This design system translates the essence of high-end self-care into a digital experience. The brand personality is rooted in **Modern Luxury**, blending editorial elegance with a vibrant, high-fashion energy. It targets an audience that values professional expertise, trend-setting aesthetics, and a bold, pampered lifestyle.

The visual style utilizes a mix of **Minimalism** and **High-End Editorial** influences. It prioritizes generous white space (the "airy" feel), intentional typography pairings, and a soft, tactile depth. The interface should feel like a premium lifestyle magazine—sophisticated, confident, and impeccably curated.

## Colors
The palette is a harmonic blend of bold energy and sophisticated depth:
- **Primary (Vibrant Magenta):** Used for key calls to action, highlights, and modern accents. It represents the "vibrant energy" and confidence of beauty.
- **Secondary (Deep Plum):** Used for primary text, deep backgrounds, and high-contrast UI elements to provide an anchor of professionalism and luxury.
- **Tertiary (Champagne Ivory):** A soft accent used for subtle section backgrounds and container fills.
- **Neutral (Cream):** The foundation of the UI. Replacing pure white with a creamy ivory (#FAF9F6) softens the visual impact and feels more expensive.

Use a high-contrast ratio for text (Plum on Ivory) to maintain accessibility while preserving the boutique aesthetic.

## Typography
The typography strategy relies on the tension between the classic, high-contrast serif **Playfair Display** and the modern, geometric **Montserrat**.

- **Headlines:** Use Playfair Display for all major headings. It evokes a sense of timeless beauty and authority. For extra elegance, use italic styles for specific keywords within a headline.
- **Body:** Use Montserrat for all long-form text and functional UI. Ensure line heights are generous (at least 1.5x) to maintain the "airy" feel.
- **Labels/Navigation:** Use Montserrat in Uppercase with increased letter-spacing (0.1em) for navigation items and small labels to give them a professional, organized structure.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop to ensure a controlled, boutique presentation. 

- **Desktop:** A 12-column grid with a 1200px max-width, centered. Use wide outer margins (64px+) to create a "frame" around the content.
- **Mobile:** A 4-column fluid grid with 16px side margins. 
- **Spacing Logic:** Use an 8px base unit. To achieve the "pampering" feel, prioritize "Large" and "Extra Large" spacing between sections (e.g., 80px or 120px) to allow the imagery and typography to breathe. Avoid crowding elements; luxury is defined by the space you *don't* fill.

## Elevation & Depth
Depth is created through **Ambient Shadows** and **Tonal Layering** rather than harsh borders.

- **Surfaces:** Use the Ivory neutral as the base. Elevated containers (like service cards) should use a slightly lighter or pure white background to "pop" subtly.
- **Shadows:** Shadows must be extremely diffused and low-opacity (using the Deep Plum color at 5-10% opacity for the shadow tint). This creates a "soft glow" effect rather than a heavy drop shadow.
- **Glassmorphism:** Use subtle backdrop blurs (10px–20px) on navigation bars or modal overlays to maintain a sense of lightness and transparency.

## Shapes
The shape language is **Soft and Organic**. 

- **Corners:** Use Level 2 Roundedness (0.5rem / 8px) as the default for buttons, input fields, and cards. 
- **Images:** Photography should use Level 2 or Level 3 (1rem / 16px) rounding to avoid sharp, aggressive edges.
- **Special Elements:** For "Book Now" or featured callouts, consider pill-shaped buttons to further emphasize the "soft/pampering" theme.

## Components
- **Buttons:** 
  - *Primary:* Solid Deep Plum with Ivory text. 
  - *Secondary:* Ghost style with a thin Vibrant Magenta border and Vibrant Magenta text. 
  - *Hover States:* Subtle scale increase (1.02x) with a soft shadow expansion.
- **Cards:** 
  - Use a subtle Ivory background, no border, and an ambient plum-tinted shadow. 
  - Image-to-text ratio should be approximately 60/40 to prioritize high-quality beauty imagery.
- **Input Fields:** 
  - Clean, minimal design. Use a bottom-border only or a very light Tertiary fill with Level 1 rounding. 
  - Focus state uses a Vibrant Magenta underline.
- **Chips/Tags:** 
  - Small, pill-shaped with a Tertiary background and Deep Plum text for service categories (e.g., "Facials," "Massage").
- **Lists:** 
  - Service menus should use a classic "dot-leader" or generous spacing between the service name (Playfair Display) and price (Montserrat).
- **Navigation:** 
  - A centered logo with a thin, horizontal Vibrant Magenta line or a soft shadow separator at the bottom. Use the Uppercase Label style for links.