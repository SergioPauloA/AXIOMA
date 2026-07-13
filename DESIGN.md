---
name: AXIOMA Urban Science
colors:
  surface: '#141313'
  surface-dim: '#141313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2b2a2a'
  surface-container-highest: '#353434'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c9c6c5'
  primary: '#c9c6c5'
  on-primary: '#313030'
  primary-container: '#0a0a0a'
  on-primary-container: '#7b7979'
  inverse-primary: '#5f5e5e'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#cac6c3'
  on-tertiary: '#32302f'
  tertiary-container: '#0b0a09'
  on-tertiary-container: '#7c7977'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e6e1df'
  tertiary-fixed-dim: '#cac6c3'
  on-tertiary-fixed: '#1d1b1a'
  on-tertiary-fixed-variant: '#484645'
  background: '#141313'
  on-background: '#e5e2e1'
  surface-variant: '#353434'
typography:
  display-xl:
    fontFamily: Anton
    fontSize: 84px
    fontWeight: '400'
    lineHeight: 80px
    letterSpacing: -0.02em
  display-xl-mobile:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 44px
  headline-lg:
    fontFamily: Anton
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: Anton
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 32px
  body-lg:
    fontFamily: Space Mono
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Space Mono
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Archivo Narrow
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  container-max: 1440px
---

## Brand & Style
This design system captures the raw, high-energy aesthetic of early 2000s rhythm games and street culture, subverting the clinical nature of science education. The brand personality is rebellious, loud, and uncompromising—designed to make learning feel like a high-stakes underground event. 

The style is a fusion of **Neo-Brutalism** and **Grunge**. It utilizes heavy outlines, "broken" layout structures, and high-contrast digital artifacts. Visual interest is driven by "urban decay" motifs: distressed textures, digital noise, and elements that appear "taped" or "stapled" to the screen. The emotional response is one of adrenaline and urgency, breaking away from the safe, sterile environments usually associated with academia.

## Colors
The palette is rooted in a "Dirty Wall" black, providing a deep, textured void for high-intensity neon accents to pop. 

- **Base (#0a0a0a):** Use for the primary background. It should never be a flat hex; apply a subtle grain or "concrete" texture overlay.
- **Text (#eeeeee):** High-readability off-white to prevent retina burn against the black.
- **Chemistry (#00ff66):** Neon green used for biological and chemical data, progress bars, and "success" states.
- **Physics (#00ccff):** Electric blue for mechanical data, wave functions, and interactive links.
- **Math (#ff3300):** Blood red for core equations, critical errors, and high-priority alerts.

Colors should be applied with "ink-bleed" or "glow" effects where possible to simulate spray-paint or CRT monitors.

## Typography
The typography system relies on a "collision" of styles. 

- **Headlines (Anton):** Massive, condensed, and aggressive. These should feel like posters wheat-pasted onto a wall. Use `text-transform: uppercase` for all headlines.
- **Body (Space Mono):** Brings a technical, "urban science" feel. It mimics terminal output and old lab reports.
- **Labels (Archivo Narrow):** Tight and efficient for data-heavy overlays and secondary navigation.

**Distress Rule:** For main display headers, apply a 2-degree random rotation and a slight "glitch" or displacement map to break the digital perfection.

## Layout & Spacing
The layout follows a **Fluid Grid** but intentionally breaks it to create a sense of disorder. 

- **The Offset Rule:** Elements should rarely be perfectly centered. Use 4px or 8px offsets on containers to create a "layered paper" effect.
- **Columns:** Use a 12-column grid for desktop. Elements should "burst" out of their containers using negative margins.
- **Gutters:** Maintain wide 24px gutters to allow the background texture to peek through, emphasizing the separation of "scraps" of information.
- **Borders:** All primary containers must have a solid 3px or 4px border.

## Elevation & Depth
In this design system, depth is not achieved through light and shadow, but through **Stacking and Hard Offsets**.

- **Hard Shadows:** Do not use blurs. Use solid color blocks (usually the accent color or pure black) offset by 4px to 8px behind the element.
- **Taped Layers:** Use small "tape" rectangles (semi-transparent #eeeeee) at the corners of cards to simulate them being stuck to the UI.
- **Negative Space:** Use the #0a0a0a background as the "ground." Content layers should feel like physical materials (cardboard, metal, paper) placed on top.
- **Z-Index Play:** Overlap elements aggressively. A headline should partially obscure a decorative image or a border.

## Shapes
The shape language is **Sharp and Jagged**. 

- **Corners:** 0px radius is the standard. Everything is hard-edged.
- **Custom Shapes:** Use clipped corners (45-degree cuts) for buttons and active tabs to mimic industrial plates.
- **Scribbles:** Use hand-drawn, "scribbled" SVG paths for underlines, strikethroughs, and circling key data points. These should be colored in Math Red or Chemistry Green.

## Components
- **Buttons:** Solid background (Accent color), black text, 4px hard black border, and an 8px hard offset shadow. On hover, the shadow "snaps" into the button (0px offset).
- **Input Fields:** Thick white borders, black background. The cursor should be a solid, blinking block in the Physics Blue color.
- **Cards:** Use a "Distressed Container" look. A solid border with a "hand-drawn" rough edge or a jittered stroke. Include a "Serial Number" in the top right of every card using the Label font.
- **Chips/Badges:** Designed to look like "Dymo" embossed labels. Black background, white uppercase text, slightly skewed.
- **Progress Bars:** Representing lesson progress or energy. Use a segmented "block" style rather than a smooth fill. Each block glows with the Chemistry Green when active.
- **Lists:** Bullet points should be replaced with "X" marks or chemical symbols. Every third item in a list should have a subtle background "highlight" that looks like a swipe of a highlighter pen.