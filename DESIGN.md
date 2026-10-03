---
name: Campus Utility Minimal
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#434655'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#515f74'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3fc'
  on-secondary-container: '#57657a'
  tertiary: '#943700'
  on-tertiary: '#ffffff'
  tertiary-container: '#bc4800'
  on-tertiary-container: '#ffede6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#d5e3fc'
  secondary-fixed-dim: '#b9c7df'
  on-secondary-fixed: '#0d1c2e'
  on-secondary-fixed-variant: '#3a485b'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb596'
  on-tertiary-fixed: '#360f00'
  on-tertiary-fixed-variant: '#7d2d00'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system delivers a focused, institutional-grade utility aesthetic tailored for high-volume campus administration and academic operations. Built around the principles of functional minimalism, speed, and absolute clarity, the design eliminates visual noise, decorative gradients, and frivolous ornamentation in favor of purposeful structure and high legibility.

The brand personality is dependable, modern, and precise. It communicates operational efficiency to campus administrators, department coordinators, student leaders, and registrars handling mission-critical credentials. The interface instills confidence through deterministic feedback, clean visual hierarchy, generous white space, and clear structural separation.

## Colors

The palette establishes an orderly, high-contrast light mode hierarchy rooted in crisp white, structural slate grays, and an authoritative royal blue accent.

- **Primary (`#2563EB`)**: Anchor for key actions, selected states, progress meters, and primary interactive affordances.
- **Secondary (`#475569`)**: Mid-tone slate used for supporting actions, inactive steps, table headers, and meta values.
- **Neutral Canvas & Surfaces**:
  - Pure White (`#FFFFFF`): Main canvas and elevated modal/card surfaces.
  - Off-white Slate (`#F8FAFC`): Base application canvas, subtle zebra-striping, and nested panel backgrounds.
  - Border & Dividers (`#E2E8F0`): Crisp 1px structural boundaries defining tables, inputs, and containment wrappers.
  - Muted Surface (`#F1F5F9`): Inactive badge backgrounds, hover fills, and step trail connectors.
- **Text & Foreground**:
  - Primary Content (`#0F172A`): Deep slate for primary headlines, table data cells, and active labels.
  - Secondary Content (`#334155` / `#64748B`): Descriptions, captions, helper instructions, and placeholder text.
- **Semantic Accents**: Success states leverage `#16A34A`, destructive/error states use `#DC2626`, and warning/draft notices use `#D97706`.

## Typography

Typography relies uniformly on `Inter` across all structural layers to maximize legibility, numeric tabular alignment, and fast scanning of data. 

- Use tabular numbers (`font-feature-settings: "tnum"`) within data tables, timestamp lists, and generation counters.
- Keep letter spacing neutral to slightly snug (`-0.01em` on headlines, `0` on body and data rows).
- Restrict all bold display weights to functional labels, section headings, and explicit status titles. Avoid decorative typographic treatments.

## Layout & Spacing

The layout is built upon an 8px grid foundation structured within an aligned, fixed-max utility frame (max-width `1280px` for desktop workflows).

- **Grid System**: 12-column layout on desktop with `1.5rem` gutters. On mobile viewports (<768px), the layout reflows into a single column with `1rem` outer margins.
- **Rhythm & Padding**: Use `space-md` (`1rem`) for standard component interiors and compact table paddings; reserve `space-xl` (`2rem`) for major workflow milestone separations and card grouping gaps.
- **Form & Content Containers**: Certificate configuration, mapping forms, and generation flows follow a distinct 2/3 action column to 1/3 real-time preview distribution on desktop views.

## Elevation & Depth

Depth is established primarily through structural borders and flat, low-contrast tonal layering rather than high-elevation drop shadows.

- **Flat Tonal Boundaries**: Surfaces rest on `#F8FAFC` canvas backgrounds. Elevated content containers use `#FFFFFF` fills bounded by a deliberate 1px border (`#E2E8F0`).
- **Low-Radius Ambient Shadows**:
  - `elevation-low`: `0 1px 2px 0 rgba(15, 23, 42, 0.05)` for floating cards, dropdown panels, and hover table rows.
  - `elevation-mid`: `0 4px 6px -1px rgba(15, 23, 42, 0.08), 0 2px 4px -2px rgba(15, 23, 42, 0.04)` strictly reserved for context modals, file drop active zones, and slide-over preview sheets.
- Avoid multi-stop blurs, saturated glow effects, or glassmorphic backdrops.

## Shapes

The interface embraces a balanced medium-rounded aesthetic that balances software utility with contemporary polish.

- **Standard Elements (0.5rem / 8px)**: Default inputs, buttons, table cell selections, alerts, and inline badges.
- **Containers & Panels (1rem / 16px)**: Primary application cards, file upload dropzones, stepper enclosures, and modal dialogs.
- **Outer Shells & Sheets (1.5rem / 24px)**: Outer workflow containers and large-format certificate preview frames.

## Components

### Buttons
- **Primary**: Solid background `#2563EB`, text `#FFFFFF`, rounded `0.5rem`, padding `0.625rem 1.25rem`. Hover `#1D4ED8`, active `#1E40AF`.
- **Secondary / Outline**: Background `#FFFFFF`, 1px border `#E2E8F0`, text `#334155`. Hover background `#F8FAFC`, border `#CBD5E1`.
- **Destructive**: Background `#FFFFFF`, 1px border `#FCA5A5`, text `#DC2626`. Hover background `#FEF2F2`.

### Stepper Indicator
- Horizontal track connecting discrete numbered circular nodes (`32px × 32px`).
- **Completed**: `#2563EB` fill, white checkmark, connecting bar colored `#2563EB`.
- **Active**: 2px border `#2563EB`, white fill, `#2563EB` numeric text with bold label below.
- **Upcoming**: `#E2E8F0` border, `#F8FAFC` fill, `#94A3B8` text, connecting bar `#E2E8F0`.

### Data Tables
- Crisp, borderless interiors bounded by an outer 1px `#E2E8F0` frame.
- **Header**: `#F8FAFC` background, `#475569` text, `12px` font size with uppercase letter-spacing (`0.05em`), height `40px`.
- **Rows**: Alternating hover fill `#F8FAFC`, border-bottom 1px `#F1F5F9`, height `48px`, numeric columns aligned right.

### Input Fields & Upload Dropzones
- **Text Inputs**: Height `40px`, border 1px `#CBD5E1`, background `#FFFFFF`, text `#0F172A`. Focused state uses ring `2px #2563EB` with `0` offset.
- **File Upload Area**: Dashed 2px border `#CBD5E1`, `#F8FAFC` background, transition to `#EFF6FF` background and `#2563EB` border on drag hover.

### Badges & Status Chips
- Pill-shaped (`rounded-full`), padding `2px 10px`, font size `12px`, weight `500`.
- **Success (Generated/Sent)**: Background `#DCFCE7`, text `#15803D`.
- **Pending/Draft**: Background `#F1F5F9`, text `#475569`.
- **Error/Failed**: Background `#FEE2E2`, text `#B91C1C`.