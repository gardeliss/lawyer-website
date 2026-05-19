---
name: Juris & Prestige
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#44464e'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#75777f'
  outline-variant: '#c5c6cf'
  surface-tint: '#4c5e86'
  primary: '#00081e'
  on-primary: '#ffffff'
  primary-container: '#0a1f44'
  on-primary-container: '#7687b2'
  inverse-primary: '#b4c6f4'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e4e2e1'
  on-secondary-container: '#656464'
  tertiary: '#0f0800'
  on-tertiary: '#ffffff'
  tertiary-container: '#2d1e00'
  on-tertiary-container: '#a5833f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#b4c6f4'
  on-primary-fixed: '#041a3f'
  on-primary-fixed-variant: '#34466d'
  secondary-fixed: '#e4e2e1'
  secondary-fixed-dim: '#c8c6c6'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#ffdea5'
  tertiary-fixed-dim: '#e9c176'
  on-tertiary-fixed: '#261900'
  on-tertiary-fixed-variant: '#5d4201'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Playfair Display
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
  label-sm:
    fontFamily: Inter
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
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-padding: 120px
---

## Brand & Style

This design system is built on the pillars of **Heritage, Precision, and Absolute Trust**. It serves a high-end legal clientele where clarity and authority are paramount. The aesthetic follows a **Minimalist High-End** approach—stripping away unnecessary ornamentation to let the weight of the content and the quality of the typography communicate expertise. 

The emotional response should be one of "quiet confidence." We achieve this through an expansive use of whitespace, a structured grid that suggests stability, and a refined color palette that balances the deep, historical weight of navy with the modern luxury of gold accents. The interface does not shout; it commands attention through order and elegance.

## Colors

The palette is designed to evoke the atmosphere of a sophisticated law office. 

*   **Primary (Deep Navy):** Used for headers, primary actions, and brand-heavy elements. It represents the "Pillar of Stability."
*   **Secondary (Charcoal):** Reserved for body text and iconography to ensure high legibility without the harshness of pure black.
*   **Tertiary (Elegant Gold):** Used sparingly as a "Signifier of Excellence." Apply it to text links, call-to-action borders, or active states to draw the eye with refinement.
*   **Neutral (Crisp White/Off-White):** Used for large surface areas to provide the "Air" required for a minimalist, premium feel.

Avoid using gold for large background areas; it should remain a precision tool for highlighting value.

## Typography

The typographic hierarchy creates a dialogue between tradition and modern utility. 

**Headlines (Playfair Display):** These should be treated with editorial care. Large headlines use negative letter spacing to feel tighter and more customized. Ensure high contrast between the navy text and white backgrounds.

**Body & Labels (Inter):** Inter provides the necessary "functional" counterweight to the serif headings. It ensures that complex legal documents and long-form practice area descriptions remain highly readable. Labels should use slight letter-spacing and uppercase styling to denote categorization and hierarchy without adding visual bulk.

## Layout & Spacing

The design system utilizes a **Fixed Grid** model to convey a sense of permanence and structure. 

*   **Desktop:** A 12-column grid with a maximum container width of 1200px. Sections are separated by generous vertical padding (120px) to allow content to "breathe" and signal high-end positioning.
*   **Tablet:** Reflows to an 8-column grid with 32px margins.
*   **Mobile:** A 4-column grid with 20px margins. 

Spacing follows a strict 8px rhythm. Components should favor internal padding over external margins to maintain clean alignment. Alignment should lean towards the center for brand-heavy landing pages, and left-aligned for data-dense legal or service pages.

## Elevation & Depth

To maintain a minimalist aesthetic, depth is communicated through **Ambient Shadows** and **Tonal Layering** rather than heavy gradients.

*   **Surface Depth:** Primary surfaces are pure white. Secondary containers (like cards or sidebars) use a subtle `#F8F9FA` background to differentiate without creating hard visual breaks.
*   **Shadows:** Use extremely diffused, low-opacity shadows (e.g., `box-shadow: 0 4px 20px rgba(10, 31, 68, 0.05)`). The shadow color should be a tinted version of the Primary Navy to keep the UI "warm" and cohesive.
*   **Borders:** Utilize hairline borders (1px) in a light grey or a very muted gold for high-importance items like primary contact forms.

## Shapes

The shape language is **Soft (0.25rem)**. 

Sharp corners feel too aggressive for a firm that values approachability, while fully rounded "pill" shapes feel too casual. The 4px radius (Soft) provides a subtle modernization of traditional legal documents, making the interface feel "architectural" yet contemporary. Apply this consistently across buttons, input fields, and practice area cards.

## Components

### Buttons
*   **Primary:** Solid Navy background, White text. No border. Soft 4px radius.
*   **Secondary:** Ghost style with a 1px Gold border and Gold text. 
*   **State:** On hover, the primary button should slightly darken; the secondary button should transition to a subtle gold fill with white text.

### Practice Area Cards
Cards should be "flat" by default with a subtle 1px border (`#E5E5E5`). Upon hover, they should lift slightly using an ambient shadow and the border should transition to Gold. Titles in Playfair Display (Headline-sm).

### Input Fields
Forms must feel professional and unobstructed. Use a 1px border on all four sides. On focus, the border transitions to Primary Navy. Use `Label-md` for field titles to maintain a structured, organized appearance.

### Lawyer Profiles
Use high-quality, professional photography. Portraits should be framed in a simple rectangle with the 4px radius. Use the serif typeface for the lawyer's name and the sans-serif for their title and credentials to clearly define the hierarchy of information.

### Lists & Citations
Legal citations should be styled in `Body-md` but with a slightly reduced opacity (70%) to differentiate from core argumentative text while maintaining legibility.