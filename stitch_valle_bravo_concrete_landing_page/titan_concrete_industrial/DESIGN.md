---
name: Titan Concrete Industrial
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#5a413d'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#8e706b'
  outline-variant: '#e2beb9'
  surface-tint: '#b4281b'
  primary: '#5f0000'
  on-primary: '#ffffff'
  primary-container: '#890101'
  on-primary-container: '#ff8e7d'
  inverse-primary: '#ffb4a8'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2e2e2'
  on-secondary-container: '#646464'
  tertiary: '#00168b'
  on-tertiary: '#ffffff'
  tertiary-container: '#0024c6'
  on-tertiary-container: '#9ca7ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#ffb4a8'
  on-primary-fixed: '#410000'
  on-primary-fixed-variant: '#910905'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1b1b1b'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#dfe0ff'
  tertiary-fixed-dim: '#bcc2ff'
  on-tertiary-fixed: '#000c61'
  on-tertiary-fixed-variant: '#0f2ccb'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
  concrete-gray: '#D3D3D3'
  deep-slate: '#1A1A1A'
  surface-muted: '#F5F5F5'
typography:
  display-lg:
    fontFamily: Chivo
    fontSize: 72px
    fontWeight: '900'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Chivo
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Chivo
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Chivo
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  button-text:
    fontFamily: Chivo
    fontSize: 16px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.05em
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 80px
  section-gap: 120px
---

## Brand & Style

The brand identity is built on a foundation of **Industrial Minimalism**. It targets residential and commercial clients who value structural integrity and precision. The visual language conveys authority and "heavy-duty" reliability through a high-contrast palette and bold, architectural typography.

The aesthetic balance focuses on:
- **Raw Sophistication:** Utilizing massive whitespace to frame high-resolution imagery of textures (concrete grain, steel, architectural lines).
- **Functional Boldness:** Using a striking red for action-oriented elements, ensuring the "Get Estimate" and "Call" triggers are impossible to miss.
- **Trust-Driven Clarity:** A clean, systematic layout that removes visual clutter, presenting the business as an organized, high-end professional entity rather than a local utility.

## Colors

The palette is strictly high-contrast to mirror the raw materials of the trade.

- **Primary (Industrial Red):** Used exclusively for primary Call-to-Action (CTA) buttons, urgent alerts, and subtle brand accents. This color is meant to pierce through the monochrome background.
- **Secondary (Black/Deep Slate):** Used for heavy headlines and primary navigation bars to ground the design in strength.
- **Neutral (White/Muted Surface):** Provides the "gallery" feel required to make the project photography stand out. 
- **Concrete Gray:** Utilized for secondary text, borders, and icon containers to maintain the industrial theme without adding unnecessary hue.

## Typography

The typography strategy is "loud and clear." 

- **Headlines (Chivo):** A heavy, confident sans-serif. Use `display-lg` for hero sections with tight letter-spacing to emphasize the "mass" of the brand.
- **Body (Hanken Grotesk):** A modern, legible grotesque that balances the aggressive headlines with professional clarity.
- **Labels (JetBrains Mono):** Monospaced type is used for technical data (licensing, phone numbers, measurements) to evoke engineering precision and industrial blueprints. All labels should be uppercase with wide tracking.

## Layout & Spacing

This design system utilizes a **12-column fixed grid** for desktop and a **4-column fluid grid** for mobile.

- **Rhythm:** An 8px base unit drives all spacing.
- **Whitespace:** Sections are separated by massive gaps (`120px+`) to allow each service (e.g., Stamped Concrete, Culverts) to feel like a distinct "exhibit."
- **Layout Model:** Use asymmetrical layouts where imagery takes 7/12 columns and text blocks occupy the remaining 5/12 to create a modern, editorial flow.
- **Mobile Reflow:** For mobile, stack all columns vertically but maintain generous top/bottom padding within cards to ensure "breathability."

## Elevation & Depth

To maintain the "flat and heavy" industrial feel, this design system avoids soft ambient shadows. Instead, depth is created through:

- **Tonal Layering:** Using `#F5F5F5` (Surface Muted) containers against `#FFFFFF` backgrounds to define card areas.
- **High-Contrast Outlines:** Buttons and inputs use thick (2px) solid black or red borders rather than shadows.
- **Image Overlays:** Text is often placed in high-contrast boxes (black background, white text) that partially overlap imagery, creating a layered, "stacked materials" effect.
- **Parallax:** Subtle scroll-based movement on background textures (concrete grit) can be used to add technical depth.

## Shapes

The shape language is strictly **Sharp (0px)**. 

In line with the structural nature of concrete, curves are avoided unless they are inherent in the photography. Every button, input field, card, and image container must have square corners. This reinforces the "unyielding" and "solid" brand personality. 

Vertical and horizontal dividers should be 1px solid `#D3D3D3` to act as grid lines, mimicking architectural drawings.

## Components

### Buttons
- **Primary:** Solid Red background, white `button-text`, sharp corners, 2px red border. On hover: Black background.
- **Secondary:** Transparent background, black 2px border, black `button-text`.
- **Icon Buttons:** Use a simple arrow (`→`) following the text for CTAs to suggest forward momentum.

### Cards (Service/Project)
- No shadows. Use a 1px `concrete-gray` border.
- Images should be top-aligned with no padding.
- Use `label-caps` for the category (e.g., "COMMERCIAL") and `headline-md` for the title.

### Input Fields
- White background with a 2px black border. 
- Placeholder text in `concrete-gray`.
- Focus state: Border changes to Red.

### Lists
- Use custom bullet points: small 4x4px red squares rather than circles to maintain the geometric, sharp aesthetic.

### Financing Widget
- To integrate the third-party Hearth financing cleanly, wrap the widget in a `surface-muted` container with a 1px border. Ensure the "Get Rates" button is styled to match the system's Primary Button style for consistency.