---
name: Botanical Utility
colors:
  surface: '#f5fbf4'
  surface-dim: '#d6dcd5'
  surface-bright: '#f5fbf4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff5ee'
  surface-container: '#eaefe8'
  surface-container-high: '#e4eae3'
  surface-container-highest: '#dee4dd'
  on-surface: '#171d19'
  on-surface-variant: '#43483f'
  inverse-surface: '#2c322d'
  inverse-on-surface: '#ecf2eb'
  outline: '#73796e'
  outline-variant: '#c3c8bc'
  surface-tint: '#46673d'
  primary: '#0f2d0a'
  on-primary: '#ffffff'
  primary-container: '#25441e'
  on-primary-container: '#8db181'
  inverse-primary: '#acd19e'
  secondary: '#326b00'
  on-secondary: '#ffffff'
  secondary-container: '#a6f86c'
  on-secondary-container: '#367200'
  tertiary: '#152d0c'
  on-tertiary: '#ffffff'
  tertiary-container: '#2a4320'
  on-tertiary-container: '#92b083'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c7edb8'
  primary-fixed-dim: '#acd19e'
  on-primary-fixed: '#032102'
  on-primary-fixed-variant: '#2f4e27'
  secondary-fixed: '#a6f86c'
  secondary-fixed-dim: '#8cdb53'
  on-secondary-fixed: '#0b2000'
  on-secondary-fixed-variant: '#245100'
  tertiary-fixed: '#ccecbb'
  tertiary-fixed-dim: '#b1cfa0'
  on-tertiary-fixed: '#092103'
  on-tertiary-fixed-variant: '#344d29'
  background: '#f5fbf4'
  on-background: '#171d19'
  surface-variant: '#dee4dd'
  canvas-matcha: '#BEE0B1'
  surface-card: '#E2E8E1'
  surface-card-hover: '#D8E0D7'
  text-headline: '#283F20'
  text-body: '#3D5732'
  text-muted: '#506E45'
  badge-urgent-text: '#BA1A1A'
  border-canvas: '#A2C993'
  border-subtle: '#A8CE9B'
typography:
  display:
    fontFamily: Noto Sans
    fontSize: 36px
    fontWeight: '900'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Sans
    fontSize: 24px
    fontWeight: '800'
    lineHeight: 30px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Noto Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 26px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Noto Sans
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 22px
    letterSpacing: 0em
  body-lg:
    fontFamily: Noto Sans
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Noto Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Noto Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.005em
  label-md:
    fontFamily: Noto Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Noto Sans
    fontSize: 10px
    fontWeight: '800'
    lineHeight: 12px
    letterSpacing: 0.03em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 0.75rem
  margin: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.875rem
  space-lg: 1.25rem
  space-xl: 1.5rem
---

## Brand & Style

Botanical Utility is a serene, grounding, and purposeful visual identity designed for personal administration and deadline tracking. It merges the structure of modern productivity tools with an organic, calm palette inspired by matcha, sage, and forest foliage. 

The aesthetic draws primarily from **Soft Tactile Modernism**:
- Calibrated organic backgrounds paired with soft, milk-toned surface modules (`#E2E8E1`).
- Deliberate use of pill-shaped geometry and deep forest-green typography (`#253F1F`, `#3D5732`) to eliminate anxiety typically associated with urgency and deadlines.
- Tactile, crisp boundary borders (`border-white/80` and subtle earthy dividers) instead of harsh dark lines.
- Purposeful micro-elevation that mimics clean, smooth physical cards resting on a soft surface.

## Colors

The palette is built around calming botanical greens, balanced with off-white milky grey surfaces to ensure high legibility and low visual fatigue.

- **Canvas Background (`#BEE0B1`)**: A vibrant yet soothing light matcha tone that frames the entire experience, signaling health, balance, and natural calm.
- **Surface Card (`#E2E8E1`)**: An ultra-pale sage/grey tone used across elevated metric tiles, category buttons, and list rows to provide clean contrast against the green canvas.
- **Primary Brand / Action (`#25441E`)**: A deep, saturated evergreen used for dominant text, heavy headers, and the primary call-to-action dock button.
- **Secondary Accent (`#5DA824`)**: A vivid leaf green utilized for positive statuses, primary urgency chips, and completion indicators.
- **Urgent Accent (`#BA1A1A`)**: A controlled, high-contrast red reserved exclusively for critical deadline badges.

## Typography

The typography system relies on **Noto Sans** to create an approachable, highly legible, and globally robust typographic scale.

- **Weight Contrast**: Heavy weights (`700`, `800`, and `900`) are applied generously to numeric metrics and category headings to establish immediate scanability against soft container surfaces.
- **Micro-Labels**: Supporting metadata, dates, and category paths rely on `10px`–`12px` variants styled in medium forest green tones (`#506E45`) with positive tracking to maintain clarity at compact sizes.

## Layout & Spacing

The system uses a compact, mobile-first column layout designed around a standard mobile canvas width (390px) while maintaining responsive flexibility:

- **Outer Canvas Margins**: Uniform `1.25rem` (20px) on lateral sides, keeping cards well within safe navigation boundaries.
- **Section Rhythm**: Vertical separation between modules uses `1.25rem` (`space-lg`), with individual list and grid items separated by `0.625rem`–`0.75rem` (`gap-2.5` to `gap-3`).
- **Internal Card Padding**: Metric and category blocks use `space-md` (14px) to `space-lg` (16px), ensuring content breathes while fitting two- or three-up grids comfortably.

## Elevation & Depth

Visual hierarchy is constructed through soft layering rather than strong, dark drop shadows:

- **Surface Tiers**: Base application canvas (`#BEE0B1`) acts as tier 0. Elevated cards and interactive chips (`#E2E8E1`) sit at tier 1. Inner icon housings (`#FFFFFF/80` to `#FFFFFF/90`) sit at tier 2.
- **Crisp Translucent Borders**: Cards utilize white semi-transparent borders (`border border-white/80`) that catch ambient light, defining edges softly over the green base.
- **Subtle Ambient Shadows**: Elements employ low-opacity, diffused micro-shadows (`box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.05)`) to achieve soft tactile lift without visual clutter.

## Shapes

The design embraces an organic, ultra-rounded aesthetic that removes sharp angles to induce a relaxed psychological response:

- **Outer Enclosure**: Mobile frames and structural parent sheets use deep corner radii (`rounded-[40px]`).
- **Cards & Metric Modules**: Use `24px` (`rounded-3xl`) to `16px` (`rounded-2xl`).
- **Interactive Buttons & Badges**: Fully pill-shaped (`rounded-full`) for status indicators, pill tabs, profile triggers, and floating primary action buttons.
- **Inner Icon Holders**: Gently smoothed squircle geometries (`rounded-xl` and `rounded-2xl`).

## Components

### Buttons & CTAs
- **Primary Action (Bottom Dock)**: Full-width, pill-shaped (`rounded-full`), height of 48px (`h-12`). Saturated dark evergreen background (`#25441E`), pure white text, 20px leading icon. Micro-scale tap feedback (`active:scale-[0.99]`).
- **Category Buttons**: Rectangular pill tiles (`rounded-3xl`), milky surface background (`#E2E8E1`), featuring an inner white rounded squircle (`w-10 h-10 rounded-2xl bg-white/80`) housing an outline icon, followed by centered bold body text.

### Chips & Badges
- **Urgent Priority**: Solid vibrant green (`#5DA824`) or soft alert background with uppercase bold micro-text (`text-[10px] text-[#BA1A1A] font-extrabold`).
- **Neutral / Pending**: Translucent white badge (`bg-white/80 text-[#304E26] border border-[#A6C49C]`) with `rounded-full` curvature and compact padding (`px-2.5 py-1`).

### Cards & Metric Modules
- **Metric Highlights**: 2-column grid. Uniform height (128px / `h-32`), pale sage container (`#E2E8E1`), containing top label, rounded icon badge, prominent display metric (`36px` font-black), and contextual sub-label.
- **Deadline Item Rows**: Single-column list item with `rounded-2xl` corners, containing a left icon anchor, vertically centered primary title and subtitle, and right-aligned dual-tiered status indicators.