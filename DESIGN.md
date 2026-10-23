---
name: Obsidian Workspace
colors:
  surface: '#031427'
  surface-dim: '#031427'
  surface-bright: '#2a3a4f'
  surface-container-lowest: '#000f21'
  surface-container-low: '#0b1c30'
  surface-container: '#102034'
  surface-container-high: '#1b2b3f'
  surface-container-highest: '#26364a'
  on-surface: '#d3e4fe'
  on-surface-variant: '#c7c4d8'
  inverse-surface: '#d3e4fe'
  inverse-on-surface: '#213145'
  outline: '#918fa1'
  outline-variant: '#464555'
  surface-tint: '#c3c0ff'
  primary: '#c3c0ff'
  on-primary: '#1d00a5'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#4d44e3'
  secondary: '#bec6e0'
  on-secondary: '#283044'
  secondary-container: '#3f465c'
  on-secondary-container: '#adb4ce'
  tertiary: '#4cd7f6'
  on-tertiary: '#003640'
  tertiary-container: '#006a7c'
  on-tertiary-container: '#93e8ff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#031427'
  on-background: '#d3e4fe'
  surface-variant: '#26364a'
typography:
  display:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Geist
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.015em
  title-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: -0.01em
  title-sm:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0em
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.005em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-lg: 1.5rem
  margin: 1rem
  margin-md: 1.5rem
  margin-lg: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

This design system expresses quiet authority, high-focus precision, and technological restraint for enterprise-grade digital workspaces. Tailored for modern knowledge workers, engineers, and product operators, the visual tone avoids decorative distraction in favor of density control, structural clarity, and hyper-legible utility.

The aesthetic fuses **Modern Minimalism** with subtle **Tonal Layering** and **Engineered Precision**:
- Surfaces prioritize negative space and mathematical alignment over ornamental assets.
- Contrast is engineered to eliminate optical fatigue during prolonged workspace sessions.
- Accents deploy selectively to denote state changes, actionable triggers, and context pivots without visual noise.

## Colors

The palette leverages a dark-first system founded upon rich slate undertones rather than pure achromatic blacks, preventing harsh optical glare.

- **Primary (`#4F46E5`)**: Deep Indigo. Applied exclusively to key user actions, focused inputs, active selection tabs, and critical operational triggers.
- **Secondary (`#0F172A`)**: Deep Slate. Forms the bedrock container surfaces, elevated panels, and navigation architecture.
- **Tertiary (`#06B6D4`)**: Electric Cyan. Reserved for live telemetry, real-time sync indicators, collaborative cursors, and system updates.
- **Neutral (`#64748B`)**: Balanced Slate. Governs structural hairline borders, secondary metadata, inactive iconography, and disabled states.

### Surface System
- `canvas-default`: `#090D16` (Deepest canvas backing)
- `surface-base`: `#0F172A` (Sidebars, toolbars, persistent panels)
- `surface-raised`: `#1E293B` (Cards, context menus, data table rows)
- `surface-overlay`: `#334155` (Hover states, active chips, modal surfaces)
- `border-subtle`: `rgba(148, 163, 184, 0.08)`
- `border-strong`: `rgba(148, 163, 184, 0.18)`

## Typography

The typography system relies on **Geist** for all conversational and interface hierarchy, taking advantage of its mechanical neutrality, compact metrics, and high legibility within dense layouts. Monospaced elements utilize **JetBrains Mono** to reinforce precision in telemetry, data fields, keybindings, and status labels.

- Headings utilize tightened letter-spacing (`-0.01em` to `-0.03em`) to anchor the layout visually without requiring excessive font weights.
- Body text retains uncompressed letter spacing and generous line height for uninterrupted scanning.
- Numerical readouts, system paths, tags, and timestamps systematically use `label-md` or `label-sm` with tabular lining figures.

## Layout & Spacing

This design system uses a dual-axis structural model: a flexible container system for contextual workspaces combined with an outer 12-column responsive grid for structured content dashboards.

### Responsive Breakpoints
- **Compact (Mobile: < 768px)**: 4-column layout, `margin`: `1rem`, `gutter`: `1rem`. Collapsible side drawers replace persistent utility panels.
- **Medium (Tablet: 768px - 1024px)**: 8-column layout, `margin-md`: `1.5rem`, `gutter`: `1rem`. Secondary navigation converts to icon rails.
- **Expanded (Desktop: > 1024px)**: 12-column layout, `margin-lg`: `2rem`, `gutter-lg`: `1.5rem`. Multi-pane workspace splitting enabled.

### Spacing Scale Rules
- Spacing strictly follows an 8-point base progression, with `0.25rem` (4px) reserved for micro-adjustments in tightly packaged inputs and dense table rows.
- Component-level internal padding utilizes `space-sm` (8px) for compact elements, and `space-md` (12px) to `space-lg` (16px) for standard inputs and list groups.
- Visual separation between unrelated functional blocks relies on structural section gaps of `space-xl` (24px) or higher.

## Elevation & Depth

Depth is established through **Tonal Layering** paired with ultra-subtle, ambient shadow diffusion and translucent perimeter outlines. Heavy drop shadows and simulated light sources are intentionally omitted.

### Depth Architecture
- **Layer 0 (Base Canvas)**: Flat `#090D16`. Background for high-density workspaces.
- **Layer 1 (Grouped Cards / Panels)**: Surface `#0F172A` with a 1px solid border of `rgba(148, 163, 184, 0.08)`. No shadow.
- **Layer 2 (Floating Popovers / Menus / Dropdowns)**: Surface `#1E293B`, 1px solid border of `rgba(148, 163, 184, 0.14)`, and an ambient shadow: `0 8px 24px -4px rgba(0, 0, 0, 0.45)`.
- **Layer 3 (Modals / Critical Overlays)**: Surface `#1E293B`, 1px solid border of `rgba(148, 163, 184, 0.20)`, shadow: `0 24px 48px -12px rgba(0, 0, 0, 0.65)`. Backing backdrop employs `rgba(9, 13, 22, 0.7)` with `backdrop-filter: blur(8px)`.

## Shapes

The design system adopts a **Soft (`1`)** shape language, utilizing conservative corner radii to project an architectural, tool-like demeanor.

- Small interactive elements (badges, buttons, form controls, chips) standardise on `0.25rem` (4px) corner rounding.
- Medium structural containers (cards, data tables, popovers) use `0.5rem` (8px).
- Large overlays and modals scale up to `0.75rem` (12px).
- Pill shapes are strictly forbidden except for user avatars and circular status pings.

## Components

### Buttons
- **Primary**: Solid background `#4F46E5`, foreground `#FFFFFF`, border none, inner subtle top highlight `inset 0 1px 0 rgba(255, 255, 255, 0.15)`. Hover: `#4338CA`. Active: scale `0.99`.
- **Secondary**: Surface `#1E293B`, text `#F8FAFC`, 1px border `rgba(148, 163, 184, 0.12)`. Hover: `#334155` with border `rgba(148, 163, 184, 0.24)`.
- **Ghost / Tertiary**: Transparent surface, text `#94A3B8`. Hover: `#0F172A` background, text `#F8FAFC`.
- Sizing: Standard height `36px` (`padding: 0 14px`), compact height `28px` (`padding: 0 10px`), radius `4px`.

### Input Fields
- Container: Surface `#0F172A`, height `36px`, border `1px solid rgba(148, 163, 184, 0.14)`, text `#F8FAFC`, placeholder `#64748B`, border-radius `4px`.
- Focus State: Border transitions to `#4F46E5` with a soft outer ring: `0 0 0 1px #4F46E5`.
- Error State: Border color `#EF4444`, ring `0 0 0 1px #EF4444`.

### Cards & Panels
- Border: `1px solid rgba(148, 163, 184, 0.08)`.
- Background: Surface `#0F172A` with standard internal padding of `space-lg` (16px).
- Header sections include a bottom border `1px solid rgba(148, 163, 184, 0.06)` with a `44px` height baseline.

### Chips & Badges
- Background: `#1E293B`, text `#94A3B8`, border `1px solid rgba(148, 163, 184, 0.12)`, radius `4px`.
- Status Variants: Feature a leading `6px` circular status indicator (e.g., `#10B981` for active, `#06B6D4` for syncing, `#F59E0B` for pending).
- Typography: Uses `label-sm` (JetBrains Mono).

### Checkboxes & Radios
- Size: `16px x 16px`.
- Rest: Background `#0F172A`, border `1px solid rgba(148, 163, 184, 0.24)`, radius `3px` (checkbox) or `50%` (radio).
- Checked: Background `#4F46E5`, border-color `#4F46E5`, check icon rendered in `#FFFFFF`.

### Lists & Data Rows
- Row Height: `40px` compact, `48px` standard.
- Border: Separated by a bottom hairline `1px solid rgba(148, 163, 184, 0.05)`.
- Hover: Background `#1E293B` transitioned at `120ms ease-out`.

### Command Palette & Keybinding Hints
- Overlay search modal featuring an input-first architecture (`48px` height).
- Keybindings embedded inside inputs and contextual items use `label-sm` with a background `#090D16`, border `1px solid rgba(148, 163, 184, 0.16)`, and padding `2px 5px`.