---
name: Clinical Academic Portfolio
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
  on-surface-variant: '#444653'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#757684'
  outline-variant: '#c4c5d5'
  surface-tint: '#3755c3'
  primary: '#00288e'
  on-primary: '#ffffff'
  primary-container: '#1e40af'
  on-primary-container: '#a8b8ff'
  inverse-primary: '#b8c4ff'
  secondary: '#006398'
  on-secondary: '#ffffff'
  secondary-container: '#5bb8fe'
  on-secondary-container: '#00476e'
  tertiary: '#003853'
  on-tertiary: '#ffffff'
  tertiary-container: '#005074'
  on-tertiary-container: '#68c4ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#173bab'
  secondary-fixed: '#cce5ff'
  secondary-fixed-dim: '#93ccff'
  on-secondary-fixed: '#001d31'
  on-secondary-fixed-variant: '#004b73'
  tertiary-fixed: '#c9e6ff'
  tertiary-fixed-dim: '#89ceff'
  on-tertiary-fixed: '#001e2f'
  on-tertiary-fixed-variant: '#004c6e'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 68px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 30px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-xxs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4.5rem
  gutter-mobile: 1rem
  gutter-desktop: 1.5rem
  max-container: 72rem
---

## Brand & Style

This design system establishes an intersection between peer-reviewed medical authority and modern software engineering precision. Developed for clinician-scientists, biomedical researchers, and health-tech leaders, it balances the scholarly weight of academic publishing with the clean, rapid legibility of high-performance technical interfaces.

The aesthetic philosophy centers on **Editorial Precision**:
- **Intellectual Clarity:** High typographic contrast between classical academic serifs and crisp geometric sans serifs conveys both long-standing scholarly credibility and contemporary analytical rigor.
- **Clinical Restraint:** Ample negative space, controlled hairline borders, and a calibrated slate-on-light canvas evoke laboratory precision without appearing sterile.
- **Deliberate Accents:** Vivid clinical sapphire and diagnostic cyan serve functional purposes—indexing disciplines, accentuating live telemetry, and highlighting citations rather than merely decorating the surface.

## Colors

The color system is optimized for reading-intensive applications, analytical dashboards, and academic portfolios. It emphasizes a clinical canvas paired with high-contrast functional color roles.

### Functional Roles
- **Primary (`#1E40AF`):** Clinical Navy Blue. Denotes primary calls-to-action, authoritative header accents, active navigation states, and primary institutional affiliations.
- **Secondary (`#0284C7`):** Technical Cyan/Cerulean. Used for interactive links, data visualizations, hover highlights, and secondary actions.
- **Tertiary (`#0EA5E9`):** Diagnostic Cyan. Reserved for live statuses, interactive pill tags, code highlights, and micro-interactions.
- **Neutral Surface Canvas:**
  - Base canvas: `#F8FAFC` (Slate 50) for a softened, low-fatigue page backdrop.
  - Surface cards: `#FFFFFF` (Pure White) with crisp hairline borders.
  - Borders: `#E2E8F0` (Slate 200) for structural division.
  - Text Primary: `#0F172A` (Slate 900) for strict WCAG AAA contrast against white cards.
  - Text Secondary: `#475569` (Slate 600) for citation metadata and supporting copy.

## Typography

The typographic pairing reflects the dual nature of clinical scholarship and modern computing:

- **Headlines & Editorial Titles (`Playfair Display`):** Carries traditional academic gravitas, reminiscent of major medical journals and university presses. Used for prominent headers, publication titles, and research statements.
- **Body, Metrics & Metadata (`Plus Jakarta Sans`):** Provides clean geometric rhythm with distinct apertures, ensuring effortless scanning across complex clinical records, abstract summaries, code samples, and performance benchmarks.
- **Hierarchy Notes:** Use small caps tracking (`label-sm` with `0.06em` letter-spacing) for discipline indicators, DOI numbers, pub status flags, and algorithmic labels.

## Layout & Spacing

The layout model adheres to a strictly structured 12-column responsive fluid grid with disciplined margins and generous section breathing room.

- **Desktop (≥1024px):** 12 columns, 24px gutters, max-width constrained to `72rem` (1152px) for optimized editorial line lengths (65–75 characters per line).
- **Tablet (768px - 1023px):** 8 columns, 20px gutters, 32px safe margins.
- **Mobile (<768px):** 4 columns, 16px gutters, 16px safe margins.
- **Rhythm Philosophy:** Dense components (e.g., metric readouts, tag groups) use compact `0.5rem` to `0.75rem` spacing, while article layouts and narrative sections adopt generous `3rem` to `4.5rem` vertical spacing to preserve academic elegance.

## Elevation & Depth

This system avoids heavy drop shadows, opting instead for **low-contrast micro-outlines and ambient clinical diffuse shadows**.

1. **Flat Surface Tier:** Background cards sit at `#FFFFFF` framed by a 1px border (`#E2E8F0`), creating zero visual noise for focused reading.
2. **Elevated Card Tier:** For interactive publication cards and active project modules, apply a layered micro-shadow:
   - `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 6px 16px -4px rgba(15, 23, 42, 0.06);`
   - Paired with a subtle border highlight on hover: `border-color: #CBD5E1`.
3. **Overlay Tier (Modals, Citations, Popovers):**
   - Backdrop blur: `backdrop-filter: blur(8px)`.
   - Card surface: `rgba(255, 255, 255, 0.96)`.
   - Shadow: `0 20px 25px -5px rgba(15, 23, 42, 0.08), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`.

## Shapes

The design system employs a **Balanced Rounded** geometry (`roundedness: 2`), anchoring structural cards with modern softness while retaining architectural stability:

- **Cards and Containers:** `rounded-lg` (16px / 1rem) for content cards, editorial summaries, and interactive panels.
- **Buttons and Form Inputs:** `rounded-md` (8px / 0.5rem) to ensure crisp, tactile touchpoints without leaning into overly playful curves.
- **Discipline & Status Pills:** Full radius (`rounded-full` / 9999px) for clinical metadata, topic chips, and citation badges to immediately distinguish taxonomy from interactive cards.

## Components

### Buttons
- **Primary:** Background `#1E40AF`, text `#FFFFFF`, radius 8px, padding 10px 20px. Font: `Plus Jakarta Sans` semi-bold (14px). Hover: `#1D4ED8` with subtle lift (`translate-y-[-1px]`).
- **Secondary / Ghost:** White background, 1px `#E2E8F0` border, text `#0F172A`. Hover: `#F8FAFC` background with `#0284C7` border and text.
- **Action Links:** Understated text links with `#0284C7`, accompanied by micro arrow icons (`w-3.5 h-3.5`) that translate on hover.

### Chips & Discipline Badges
- **Clinical Badge:** Slate-50 background, `#1E40AF` text, 1px border `#DBEAFE`. Fully rounded pill geometry with leading 6px pulsing or solid dot.
- **Technology / Data Badge:** Cyan-50 background (`#F0F9FF`), `#0369A1` text, 1px border `#BAE6FD`.
- **Status Indicator:** Uppercase tracking (`label-sm`), displaying publication statuses such as `PEER-REVIEWED`, `PREPRINT`, or `CLINICAL TRIAL PHASE II`.

### Cards & Publication Rows
- **Academic Publication Card:** Crisp white surface, 1px `#E2E8F0` border, 24px internal padding. Features a dual-header with a Playfair Display title, meta block (Journal, Year, DOI) in `Plus Jakarta Sans`, and trailing citation counts rendered in mono or high-weight sans.
- **Metric Highlights:** Large tabular figures (32px sans-serif) above subtle muted labels (`#64748B`), framed in delicate 1px grid partitions.

### Form Inputs & Filters
- **Text Inputs:** `#FFFFFF` background, 1px `#CBD5E1` border, 10px 14px padding. Focus state: border `#0284C7` with a 3px outer glow in `rgba(2, 132, 199, 0.12)`.
- **Selection Controls:** Checkboxes and radio buttons colored `#1E40AF` with smooth state transitions.