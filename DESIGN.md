---
name: Architectural Prestige
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1c1b1d'
  surface-container: '#201f22'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#d0c5b5'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#313032'
  outline: '#998f81'
  outline-variant: '#4d463a'
  surface-tint: '#e3c285'
  primary: '#e5c487'
  on-primary: '#402d00'
  primary-container: '#c8a96e'
  on-primary-container: '#533d0c'
  inverse-primary: '#735b28'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#bac7f2'
  on-tertiary: '#222f51'
  tertiary-container: '#9facd5'
  on-tertiary-container: '#334063'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdea3'
  primary-fixed-dim: '#e3c285'
  on-primary-fixed: '#261900'
  on-primary-fixed-variant: '#594312'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#dae2ff'
  tertiary-fixed-dim: '#b8c5f0'
  on-tertiary-fixed: '#0b1a3b'
  on-tertiary-fixed-variant: '#394669'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
  surface-muted: '#1A1A1D'
  border-subtle: '#27272A'
  gold-dimmed: '#8B734B'
typography:
  display-lg:
    fontFamily: Literata
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Literata
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Literata
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Literata
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-mono-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-mono-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
spacing:
  unit: 4px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  container-max-width: 1280px
---

## Brand & Style

This design system is built upon an aesthetic of **Architectural Minimalism** and **Technical Sophistication**. It targets a high-end professional audience, evoking an emotional response of authority, precision, and timeless elegance. 

The design narrative focuses on the juxtaposition of "The Archive" and "The Future." It utilizes a deep, immersive black canvas to create high-contrast focal points using gold accents and razor-sharp typography. The visual style leans heavily into **Brutalism-lite**—incorporating structured grids and thin hairlines—softened by luxurious serif typography and intentional negative space. Every element should feel intentional, deliberate, and engineered rather than merely decorated.

## Colors

The palette is strictly limited to maintain a high-prestige, editorial feel. 

- **Primary (Gold/Tan):** Used exclusively for high-priority calls to action, active states, and critical highlights. It represents the "value" within the dark void.
- **Secondary (White):** Reserved for primary content and high-readability text.
- **Neutral (Deep Black):** The foundation of the system. It should be applied to backgrounds to create a sense of infinite depth.
- **Surface & Borders:** For secondary containers or structural lines, use dark grays that remain close to the black base to prevent the grid from becoming visually noisy.

## Typography

This system employs a high-contrast typographic pairing to signal both "The Scholar" and "The Engineer."

- **Serif (Literata):** Used for headlines and display text. It provides the editorial, authoritative voice of the brand.
- **Sans-Serif (Plus Jakarta Sans):** Used for long-form body copy to ensure maximum legibility and a friendly, modern touch.
- **Monospace (JetBrains Mono):** Used for all UI metadata, labels, tags, and small technical details. This reinforces the "engineered" nature of the design.

Apply **uppercase** styling to Monospace labels to increase their "blueprint" aesthetic. Headlines should utilize tight letter-spacing to feel more cohesive.

## Layout & Spacing

The layout is a **structured architectural grid**. It relies on 1px borders to define regions rather than shadows or background changes.

- **Grid Model:** A 12-column fluid grid for desktop with 24px gutters. On mobile, transition to a single-column stack with 20px side margins.
- **Hairlines:** Use thin `#27272A` borders to separate sections. Every major layout block should feel like it exists within a cell of a larger technical drawing.
- **Negative Space:** Be aggressive with whitespace. Content should be allowed to breathe to emphasize its importance. Use a base 4px spacing scale (4, 8, 16, 24, 32, 48, 64, 80) for all internal margins and paddings.

## Elevation & Depth

In this dark-mode centric system, depth is achieved through **Tonal Layering** and **Outline Definition** rather than traditional shadows.

1.  **Base Layer:** The deepest black (#09090B).
2.  **Elevated Surface:** A slightly lighter gray (#1A1A1D) used for cards or drawers that sit "on top" of the base.
3.  **Interaction Depth:** Instead of shadows, use 1px borders in Gold (#C8A96E) to indicate focus or active states.
4.  **Glassmorphism:** For overlays (like navigation bars), use a backdrop-blur (20px) with a 60% opacity version of the neutral black to maintain context of the content underneath.

## Shapes

The shape language is strictly **Sharp (0px)**. 

To maintain the architectural and technical tone, avoid rounded corners on any UI elements, including buttons, input fields, and containers. This creates a "blueprint" feel where every line is a vector and every corner is an intersection. The only exception is for circular avatars or icon-specific geometry. All primary containers and action elements must maintain 90-degree angles.

## Components

- **Buttons:**
    - **Primary:** Solid Gold (#C8A96E) fill with Black text. No border. Sharp corners.
    - **Secondary:** Transparent fill with White 1px border. Sharp corners.
    - **Ghost:** Text-only, using the Monospace font style, with a subtle underline appearing on hover.
- **Input Fields:**
    - 1px White or Light Gray border, sharp corners, transparent background. 
    - Floating labels using the Monospace label-mono-sm style. 
    - Active state: Border changes to Gold (#C8A96E).
- **Navigation:**
    - Clean, text-based links using the Monospace font. 
    - Active links should have a simple Gold dot or 1px underline.
- **Cards:**
    - Defined by 1px borders (#27272A) rather than background colors. 
    - Titles within cards should always use the Serif font, while metadata uses the Monospace font.
- **Chips/Tags:**
    - Rectangular, sharp corners, small Monospace text. 
    - High contrast: White text on a dark gray background or Black text on a Gold background for "featured" tags.
- **Dividers:**
    - 1px solid lines using `#27272A`. Horizontal and vertical dividers should be used liberally to reinforce the grid system.