---
name: Serene Clarity
colors:
  surface: '#f4faff'
  surface-dim: '#ccdce7'
  surface-bright: '#f4faff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#e7f6ff'
  surface-container: '#e0f0fb'
  surface-container-high: '#daebf5'
  surface-container-highest: '#d5e5ef'
  on-surface: '#0e1d25'
  on-surface-variant: '#424845'
  inverse-surface: '#23323a'
  inverse-on-surface: '#e3f3fd'
  outline: '#727875'
  outline-variant: '#c2c8c4'
  surface-tint: '#4e635a'
  primary: '#4e635a'
  on-primary: '#ffffff'
  primary-container: '#8da399'
  on-primary-container: '#263932'
  inverse-primary: '#b5ccc1'
  secondary: '#50606f'
  on-secondary: '#ffffff'
  secondary-container: '#d1e1f4'
  on-secondary-container: '#556474'
  tertiary: '#5f5e5b'
  on-tertiary: '#ffffff'
  tertiary-container: '#a09e9a'
  on-tertiary-container: '#363632'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d1e8dd'
  primary-fixed-dim: '#b5ccc1'
  on-primary-fixed: '#0b1f18'
  on-primary-fixed-variant: '#374b43'
  secondary-fixed: '#d4e4f6'
  secondary-fixed-dim: '#b8c8da'
  on-secondary-fixed: '#0d1d2a'
  on-secondary-fixed-variant: '#394857'
  tertiary-fixed: '#e5e2dd'
  tertiary-fixed-dim: '#c9c6c2'
  on-tertiary-fixed: '#1c1c19'
  on-tertiary-fixed-variant: '#474743'
  background: '#f4faff'
  on-background: '#0e1d25'
  surface-variant: '#d5e5ef'
typography:
  headline-xl:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
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
  headline-xl-mobile:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
---

## Brand & Style

The design system is anchored in the concept of "The Breathing Space." It aims to provide a digital environment that mirrors a therapist's office: quiet, safe, professional, and free of clutter. The target audience includes individuals seeking mental health support who may be feeling overwhelmed; therefore, the UI must avoid cognitive load and prioritize ease of navigation.

The style is a blend of **Modern Minimalism** and **Organic Professionalism**. It utilizes high-quality typography and intentional whitespace to foster a sense of psychological safety. The emotional response should be one of immediate relief and grounded trust.

## Colors

This design system uses a palette inspired by nature and soft light to promote tranquility.

*   **Primary (Sage Green):** Used for primary actions and key brand moments. It represents growth and renewal.
*   **Secondary (Muted Blue-Grey):** Used for supportive elements and accents. It conveys stability and calm.
*   **Tertiary (Warm Beige):** The primary surface color for sections and containers, providing a softer, more "human" alternative to pure white.
*   **Neutral (Deep Slate):** Reserved for typography and high-contrast borders to ensure WCAG AA accessibility while maintaining a sophisticated look.

Avoid using harsh blacks or vibrant "emergency" reds. Success states should use a deeper shade of the Primary Sage, and warning states should use a muted terracotta.

## Typography

The typography strategy balances the authoritative, timeless nature of a serif with the modern efficiency of a sans-serif.

*   **Headlines (Noto Serif):** Used to establish a "voice." This font feels established and literary, suggesting wisdom and reliability. Use `headline-xl` sparingly for hero sections.
*   **Body (Inter):** Chosen for its extreme legibility and neutral character. It allows the content of the therapy descriptions to be read without distraction.
*   **Rhythm:** Always prioritize line height (1.6 for body) to ensure text-heavy pages feel airy and approachable.

## Layout & Spacing

The layout follows a **Fixed-Width Grid** model for desktop to maintain a reading-optimized line length, transitioning to a fluid model for mobile.

*   **The 8px Rule:** All spacing between elements must be a multiple of 8px.
*   **Generous Margins:** Section vertical padding should default to `xl` (80px) to allow content to "breathe." This intentional use of empty space signals to the user that they are not being rushed.
*   **Grid:** A 12-column grid for desktop with 24px gutters. Content should typically occupy the center 8 columns for optimal readability of long-form text.
*   **Mobile:** Scale margins down to 20px and reduce vertical section padding to `lg` (48px).

## Elevation & Depth

To maintain a grounded feel, this design system avoids floating elements or high-contrast shadows.

*   **Tonal Layers:** Depth is primarily communicated through subtle color shifts (e.g., a Warm Beige card sitting on a White background).
*   **Ambient Shadows:** When elevation is necessary (such as on a primary CTA or a focused card), use a very soft, diffused shadow. The shadow should use the Neutral Slate color with a low opacity (8-10%) and a large blur radius (20px+) to avoid looking "heavy."
*   **Focus States:** Use a soft, 2px Primary Sage Green outer glow rather than a harsh black border.

## Shapes

Shapes in this design system are purposefully softened to avoid the clinical or "sharp" feel of traditional medical websites.

*   **Corner Radius:** A base `roundedness` of 2 (0.5rem) is applied to all buttons, input fields, and cards.
*   **Large Components:** For larger sections or decorative image containers, use `rounded-xl` (1.5rem) to emphasize the modern, approachable aesthetic.
*   **Human Imagery:** Photos should feature soft focus backgrounds and be placed within rounded containers to blend seamlessly with the UI.

## Components

### Buttons
*   **Primary:** Solid Primary Sage Green with white text. High padding (16px 32px) and `rounded-lg`.
*   **Secondary:** Ghost style with a 1.5px border of Secondary Blue-Grey and matching text.
*   **Transitions:** All hover states must use a 300ms ease-in-out transition, gently deepening the background color.

### Cards
*   **Surface:** Use the Tertiary Warm Beige for card backgrounds to distinguish them from the page background.
*   **Padding:** Generous internal padding (min 32px) to ensure text doesn't feel cramped.

### Input Fields
*   **Styling:** 1px border using a lightened version of the Neutral Slate. On focus, the border transitions to Primary Sage with a soft glow. Labels should always be visible (no placeholder-only labels).

### Chips & Tags
*   **Usage:** For therapy specializations (e.g., "Anxiety," "CBT"). Use a desaturated version of the Secondary color with dark text to keep them legible but non-intrusive.

### Lists
*   **Bullet Points:** Replace standard discs with a custom Primary Sage Green "check" or "soft dot" to maintain brand alignment.