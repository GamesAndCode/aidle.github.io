---
name: 'Rise of AIdle: Kinetic Industrial'
colors:
  surface: '#121316'
  surface-dim: '#121316'
  surface-bright: '#38393c'
  surface-container-lowest: '#0d0e11'
  surface-container-low: '#1b1b1f'
  surface-container: '#1f1f23'
  surface-container-high: '#292a2d'
  surface-container-highest: '#343538'
  on-surface: '#e3e2e6'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#e3e2e6'
  inverse-on-surface: '#303034'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#ffabf3'
  on-secondary: '#5b005b'
  secondary-container: '#fe00fe'
  on-secondary-container: '#500050'
  tertiary: '#f6f4ff'
  on-tertiary: '#2f3038'
  tertiary-container: '#d9d8e3'
  on-tertiary-container: '#5d5e67'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#ffd7f5'
  secondary-fixed-dim: '#ffabf3'
  on-secondary-fixed: '#380038'
  on-secondary-fixed-variant: '#810081'
  tertiary-fixed: '#e3e1ed'
  tertiary-fixed-dim: '#c6c5d0'
  on-tertiary-fixed: '#1a1b23'
  on-tertiary-fixed-variant: '#45464f'
  background: '#121316'
  on-background: '#e3e2e6'
  surface-variant: '#343538'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.15em
  data-mono:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: 0.05em
spacing:
  unit: 4px
  gutter: 24px
  margin: 40px
  container-max: 1280px
---

## Brand & Style

The brand personality is high-stakes, technical, and immersive. It evokes the feeling of a command-and-control interface found on a deep-space derelict vessel. The target audience includes hardcore gamers and sci-fi enthusiasts who value technical depth and tactical aesthetics.

The design style is a hybrid of **Brutalism** and **Glassmorphism**, termed "Industrial Cyber-Tech." It utilizes raw, structural elements—like heavy borders and monospaced data readouts—layered over frosted, dark-glass surfaces. High-contrast neon accents provide a sense of active energy against a gritty, industrial backdrop. The interface should feel like a living machine: precise, powerful, and slightly dangerous.

## Colors

This design system uses a deeply desaturated, near-black base to simulate the vacuum of space and industrial carbon plating.

- **Primary (Electric Cyan):** Used for critical action paths, active states, and "AI logic" indicators. It represents the advanced technology of AIdle.
- **Secondary (Neon Magenta):** Reserved for high-alert elements, experimental tech, and biological/alien signatures. It provides a jarring, energetic contrast to the cyan.
- **Tertiary (Deep Slate):** Used for structural backgrounds and "container" surfaces to separate them from the void of the pure black background.
- **Neutral (Obsidian):** The foundation. Used for global backgrounds and deep shadows to ensure the neon accents pop with maximum luminosity.

## Typography

The typography strategy focuses on a "Mission Control" aesthetic. **Space Grotesk** is the primary choice for headlines and labels due to its technical, geometric construction and futuristic quirks (like the distinctive 'g' and 'a'). Headlines should be treated as structural elements—often paired with decorative "data-bit" labels in all-caps.

**Inter** is utilized for body copy to ensure maximum readability against dark, textured backgrounds. It provides a functional, utilitarian balance to the more expressive headline font. All labels and data readouts should use uppercase styling or monospaced-like tracking to reinforce the sci-fi terminal theme.

## Layout & Spacing

This design system employs a **Fixed Grid** model with a rigid 12-column structure. The spacing rhythm is based on a 4px baseline, ensuring all elements align to a technical "grid paper" logic.

Layouts should feel dense but organized. Use wide margins (40px+) to frame the content, making the central UI feel like a specialized cockpit display. Gutters are kept at a standard 24px, but "structural" sections can be separated by heavy 2px borders rather than whitespace to emphasize the industrial construction.

## Elevation & Depth

Depth is achieved through **Glassmorphism** and **Tonal Layers** rather than traditional drop shadows.

- **Backgrounds:** Use a subtle "film grain" or "carbon fiber" pattern overlay at 3% opacity on the neutral base.
- **Surfaces:** Use semi-transparent slate containers (60-80% opacity) with a `backdrop-filter: blur(12px)`.
- **Glows:** Instead of shadows, use "Outer Glows" for active elements. Primary buttons and active chips should cast a soft cyan or magenta bloom onto the surface beneath them.
- **Borders:** Use high-contrast 1px or 2px borders. For top-tier elevation, use a "double-border" effect: a solid primary color line followed by a 4px gap and a faint 10% opacity line.

## Shapes

The shape language is strictly **Sharp (0)**. Everything in this design system is built with 90-degree angles or 45-degree chamfered corners to mimic industrial machinery and military-grade hardware.

Avoid circles. If a circular element is required (e.g., user avatars), enclose it within a sharp square frame or an octagon. Use "bracket" shapes ( [ ] ) to frame important data points or navigational links.

## Components

- **Buttons:** Use a "clipped corner" (chamfer) look. Primary buttons are solid Cyan with black text; Secondary buttons are ghost-style with a Magenta border and a subtle hover fill.
- **Input Fields:** Thick bottom borders only. Focus states trigger a vertical "scan-line" animation or a pulse of the Primary color.
- **Cards:** Heavy 2px borders. Use "Technical Specs" headers—small monospaced text in the top-right corner indicating "SECURE_CONNECTION" or "ID_0842".
- **Progress Bars:** Segmented blocks (steppers) rather than a smooth continuous fill, evoking retro-loading sequences.
- **HUD Overlays:** Floating elements with thin crosshair lines at the corners. These should appear in the four corners of the viewport to frame the landing page content.
- **Chips/Tags:** All-caps text inside a simple outlined box. Use small '+' icons at the corners for an "engineering schematic" feel.