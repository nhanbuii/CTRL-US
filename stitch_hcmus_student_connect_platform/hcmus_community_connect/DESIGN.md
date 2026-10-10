---
name: HCMUS Community Connect
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
  on-surface-variant: '#434652'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#737783'
  outline-variant: '#c3c6d4'
  surface-tint: '#2b5bb5'
  primary: '#003178'
  on-primary: '#ffffff'
  primary-container: '#0d47a1'
  on-primary-container: '#a1bbff'
  inverse-primary: '#b0c6ff'
  secondary: '#006493'
  on-secondary: '#ffffff'
  secondary-container: '#00affe'
  on-secondary-container: '#003f5f'
  tertiary: '#003a50'
  on-tertiary: '#ffffff'
  tertiary-container: '#005270'
  on-tertiary-container: '#59c8ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#b0c6ff'
  on-primary-fixed: '#001945'
  on-primary-fixed-variant: '#00429c'
  secondary-fixed: '#cae6ff'
  secondary-fixed-dim: '#8dcdff'
  on-secondary-fixed: '#001e30'
  on-secondary-fixed-variant: '#004b70'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
  display-lg-mobile:
    fontFamily: Be Vietnam Pro
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Be Vietnam Pro
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system captures the academic rigor, youthful energy, and technical ambition of the VNUHCM-University of Science (ĐH Khoa học Tự nhiên) community. Designed for tech-savvy Gen-Z university students, faculty clubs, and academic circles, the interface balances institutional prestige with high-engagement student culture.

### Aesthetic Foundation
- **Modern Clean with Vibrancy:** Merges institutional royal blue with dynamic electric cyan and sky blue micro-accents to evoke forward-looking innovation.
- **Tone & Mood:** Intelligent, optimistic, collaborative, energetic, and legible under high-density campus use cases (timetables, club boards, research circles).
- **Visual Tenets:** Crisp cool-gray canvases, expansive white content surfaces, sculpted pill tags, hyper-legible Vietnamese-ready typography, and soft atmospheric backdrops referencing key campus touchpoints.

## Colors

The palette grounds itself in HCMUS's iconic royal blue tradition while layering vivid digital cyans to avoid institutional sterility.

### Palette Roles & Application
- **Primary (`#0D47A1`):** Institutional anchor. Used for high-emphasis callouts, primary buttons, major navigation indicators, and prominent app bar elements. A companion shade (`#1565C0`) serves as interactive hover/active states.
- **Secondary (`#00B0FF`):** Digital electricity. Applied to active status pips, focus rings, interactive toggles, live stream indicators, and notification pings.
- **Tertiary (`#38BDF8`):** Atmospheric accent. Used for secondary badge fills, soft icon containers, and interactive metric highlights.
- **Neutral Surface Ecosystem:**
  - Base Background: Pristine `#FFFFFF` and cool backdrop `#F8FAFC`.
  - Surface Subdued: `#F1F5F9` for nested modules, list headers, and secondary cards.
  - Border/Dividers: `#E2E8F0` for structural low-contrast separation.
  - Body Text & Headings: `#0F172A` (Dark Navy) provides high-contrast, fatigue-free reading compared to pure black.
  - Muted Text: Slate tones (`#64748B`) for secondary metadata and timestamps.

## Typography

The type stack combines **Be Vietnam Pro** for primary content and headlines with **Space Grotesk** for numerical data, student IDs, tags, and badge labels.

### Font Hierarchy & Rationale
- **Be Vietnam Pro:** Crafted specifically with Vietnamese diacritics in mind, maintaining balanced vertical proportions, clear tone-mark placements, and modern open apertures.
- **Space Grotesk:** Introduces a subtle STEM/technological character for student IDs, classroom codes (e.g., `F.102`, `C.33`), metric counters, event timestamps, and category pills.

### Usage Rules
- Avoid uppercase formatting in extended Vietnamese strings to prevent diacritic clipping.
- Restrict `display-lg` to onboarding and major dashboard greetings.
- Ensure minimum contrast ratios exceeding WCAG AAA standards for all `body-sm` metadata using `#475569` or darker against `#FFFFFF`.

## Layout & Spacing

The layout is built on an adaptive 8pt spatial grid designed for mobile-first handheld usage on campus, scaling smoothly to tablet and desktop portals.

### Breakpoint Strategy
- **Mobile (< 640px):** Single column, 4-column layout matrix, `margin: 1rem` (`16px`), `gutter: 1rem`. Bottom navigation persistent dock.
- **Tablet (640px – 1024px):** 8-column layout, `margin: 1.5rem` (`24px`), dynamic cards reflowing into two-column boards.
- **Desktop (≥ 1024px):** 12-column grid capped at `1280px` max-width with centered alignment. `margin: 2.5rem` (`40px`), `gutter-desktop: 1.5rem` (`24px`).

### Reflow Principles
- Campus feeds stack strictly linear on mobile; dual columns (Feed + Event/Club sidebar) activate on screens above 1024px.
- Spacing within dense schedules (e.g., student timetables) utilizes `space-xs` and `space-sm`, while content discovery cards leverage `space-md` to `space-lg` to preserve breathing room.

## Elevation & Depth

Visual hierarchy uses clean multi-layered surfaces with diffuse ambient lighting and subtle tinted shadows, avoiding heavy drops.

### Elevation Levels
- **Level 0 (Flat Canvas):** `#F8FAFC`. Baseline screen background for feeds and profile backdrops.
- **Level 1 (Default Cards & Surfaces):** `#FFFFFF` surface accompanied by a crisp hairline border `1px solid #E2E8F0` and an ultra-soft blue-tinted drop:
  `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(13, 71, 161, 0.04);`
- **Level 2 (Hover & Interactive Cards):** Activated on card focus or student touch:
  `box-shadow: 0 8px 20px -4px rgba(13, 71, 161, 0.08), 0 4px 6px -2px rgba(15, 23, 42, 0.03);`
- **Level 3 (Modals, Action Sheets, Floating Navigation):**
  `box-shadow: 0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(13, 71, 161, 0.06);`

### Glassmorphism Overlays
- Top App Bar and Bottom Tab Bar leverage `backdrop-filter: blur(12px)` over a semi-transparent surface `rgba(255, 255, 255, 0.85)` with a bottom/top border `rgba(226, 232, 240, 0.8)`.

## Shapes

The design system incorporates geometric roundedness (`level 2`), delivering approachable, tactile interfaces without sacrificing screen real estate.

### Geometry Breakdown
- **Base Components (Inputs, Small Cards, Buttons):** `0.5rem` (`8px`).
- **Standard Cards, Modals, Action Panels:** `rounded-lg` at `1rem` (`16px`).
- **Featured Hero Cards, Story Containers, Campus Landmark Highlights:** `rounded-xl` at `1.5rem` (`24px`).
- **Badges, Tags, User Avatars, Floating Action Triggers:** Full pill shape (`9999px`).

## Components

### Buttons
- **Primary:** Solid Royal Blue (`#0D47A1`) fill, `#FFFFFF` text, `font: label-lg`, height `44px` on mobile, `rounded-md` (8px). Hover: `#1565C0`. Active scale: `0.98`.
- **Secondary / Accent:** Tinted background `rgba(0, 176, 255, 0.12)`, text `#0288D1`, border `1px solid rgba(0, 176, 255, 0.25)`.
- **Ghost:** Transparent background, `#0D47A1` text, hover with `#F1F5F9`.

### Chips & Badges
- **Club & Department Tags:** Space Grotesk `label-sm`, full pill radius (`9999px`), internal padding `0.25rem 0.75rem`.
  - Faculty of IT / Math / Biotech / Chemistry: Distinct micro-tinted backgrounds (e.g., Sky Blue `rgba(56, 189, 248, 0.15)` with `#0369A1` text).
- **Status Badges:** Featuring a live `#00B0FF` pulsing beacon dot for active study groups or club sessions.

### Cards
- **Feed / Event Cards:** Level 1 elevation, `#FFFFFF` background, `rounded-lg` (16px), `space-md` internal padding. Top media banner for campus landmarks (e.g., Cơ sở 2 Linh Trung, Giảng đường 1) rounded with nested `12px` border radius.

### Input Fields
- White background (`#FFFFFF`), border `1.5px solid #E2E8F0`, padding `0.75rem 1rem`, typography `body-md`. Focus state switches border to `#00B0FF` with a glowing outline `box-shadow: 0 0 0 3px rgba(0, 176, 255, 0.18)`.

### Checkboxes & Radios
- Size `20px × 20px`, border `1.5px solid #CBD5E1`. Checked state transitions to `#0D47A1` background with white glyph, rounded `4px` for checkboxes and circular for radios.

### Specialized Campus Components
- **Student ID Micro-Card:** Compact wallet element displaying student avatar, faculty tag, matriculation QR code, and academic year in `Space Grotesk`.
- **Timetable Strip:** Horizontal scrollable rail of classroom markers (`C.33`, `E.201`) with active current-session indicators anchored in `#00B0FF`.