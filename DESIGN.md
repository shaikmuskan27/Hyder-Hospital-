---
name: Hyder Hospital Clinical Care System
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#444651'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#86f2e4'
  on-secondary-container: '#006f66'
  tertiary: '#5d0004'
  on-tertiary: '#ffffff'
  tertiary-container: '#87000a'
  on-tertiary-container: '#ff8b80'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#ffdad6'
  tertiary-fixed-dim: '#ffb4ab'
  on-tertiary-fixed: '#410002'
  on-tertiary-fixed-variant: '#93000b'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: 0em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes a premium, authoritative, and deeply reassuring presence for a premier tertiary hospital and round-the-clock emergency care provider in Nandyala, Andhra Pradesh. The interface combines institutional trust with state-of-the-art clinical efficiency. It must serve patients seeking urgent treatment, families coordinating outpatient consultations across multi-specialty departments, and clinical staff interacting with fast triage interfaces.

The aesthetic philosophy is **Modern Clinical Precision**:
- **Absolute Legibility and Calmness:** High contrast, luminous surfaces, and structured whitespace eliminate friction and cognitive anxiety during medical emergencies.
- **Distinct Functional Color-Coding:** Clear demarcation between standard clinical functions (deep navy, medical teal) and life-saving critical actions (emergency crimson).
- **Tactile Softness with Professional Rigor:** Generous corner radiuses (`rounded-2xl` on primary container cards) balanced with crisp alignment, structural borders, and subtle tinted atmospheric shadows.

## Colors

The palette leverages psychological foundations of medical care: profound institutional trust, hygiene, precision, and decisive emergency response.

### Core Swatches & Roles
- **Primary (`#1e3a8a` Deep Trust Navy):** Anchors navigation headers, key action triggers, primary medical department banners, and primary CTAs. Paired with midnight navy (`#0f172a`) for deep footers and high-impact structural panels.
- **Secondary (`#0d9488` Clinical Teal & `#14b8a6` Bright Teal):** Represents wellness, recovery, routine diagnostics, OPD booking statuses, and successful health outcomes.
- **Tertiary (`#dc2626` Emergency Crimson):** Exclusively reserved for emergency care triggers, immediate ambulance dispatch hotlines, trauma notices, and critical allergy alerts. Never dilute this color for generic destructive actions.
- **Neutral Dark (`#1e293b` Deep Charcoal Slate):** Provides high-contrast, effortless legibility for body text, avoiding the harshness of pure black. Secondary copy uses slate `#475569`.
- **Surfaces & Tints (`#f0f9ff` Ice Tint, `#e0f2fe` Soft Cyan Tint, `#ffffff` Pure White):** Clean, crisp surfaces that mimic sterile modern environments. Ice tint `#f0f9ff` separates sections without relying on heavy borders.

## Typography

The type system blends the human-centered, confident geometry of **Plus Jakarta Sans** for headlines and department titles with the ultra-meticulous readability of **Inter** for clinical data, doctor credentials, and dosage/appointment schedules.

### Hierarchy Guidelines
- **Emergency Callouts:** Use `headline-sm` with `fontWeight: 700` in tertiary crimson for ambulance, triage, and critical ICU notifications.
- **Medical Numeric Displays:** Doctor counts, 24/7 time stamps, and room numbers leverage tabular figure styling (`tnum`) in Inter for stable scanning.
- **Doctor & Specialty Badges:** Use `label-md` or `label-sm` with upper/sentence case pairing to maintain clear hierarchy over doctor bio body text.

## Layout & Spacing

A responsive 12-column grid system governs desktop views, adapting cleanly across breakpoints:
- **Desktop (1200px+):** 12 columns, 24px (`1.5rem`) gutters, max-width container 1280px, with generous 48px outer canvas margins.
- **Tablet (768px - 1199px):** 8 columns, 20px gutters, 24px margins. Specialized multi-column layouts (e.g., Doctor directory + filters) collapse into a slide-over drawer and 2-column cards.
- **Mobile (< 768px):** 4 columns, 16px gutters, 16px side margins. Persistent top emergency sticky banner and bottom quick-action navigation for instant calling and booking.

Spacing tokens (`space-xs` through `space-xl`) strictly follow an 8pt architectural rhythm, with `space-xs` (4px) providing fine micro-spacing within badges and button icons.

## Elevation & Depth

This design system avoids harsh drop shadows in favor of **ambient tinted shadows** combined with hairline structural outlines, creating an airy, reassuring clinical depth.

### Shadow Tokens & Application
- **Level 0 (Flat/Subsurface):** `#ffffff` with a subtle 1px border of `rgba(226, 232, 240, 0.8)`. Used for base table rows, appointment slots, and static informational tiles.
- **Level 1 (Default Card Elevation):** `box-shadow: 0 4px 16px -2px rgba(15, 23, 42, 0.05), 0 2px 6px -1px rgba(30, 58, 138, 0.03);` with a border of `#f1f5f9`. Used for doctor directory profiles, service highlights, and patient test report lists.
- **Level 2 (Hover & Active Medical Cards):** `box-shadow: 0 12px 28px -4px rgba(15, 23, 42, 0.08), 0 4px 12px -2px rgba(13, 148, 136, 0.06);` Used when hovering over specialty cards or active booking modules.
- **Level 3 (Modals, Triage Sheets, Emergency Floating Actions):** `box-shadow: 0 24px 48px -12px rgba(15, 23, 42, 0.18);` overlaid on a semi-opaque backdrop blur (`backdrop-filter: blur(8px); background: rgba(15, 23, 42, 0.45);`).

## Shapes

The interface balances welcoming empathy with clinical rigor. The primary token is set to `2` (Rounded):
- **Base Components (Inputs, Selectors, Regular Buttons):** `rounded` (8px / `0.5rem`).
- **Primary Patient Cards, Department Containers, Test Panels:** `rounded-xl` (16px to 24px / `rounded-2xl` in CSS utility equivalents) to eliminate sharp clinical coldness and foster patient comfort.
- **Emergency Callouts, Status Indicators, and Department Pills:** Fully rounded / pill-shaped (`9999px`) to immediately communicate quick touch targets and status validation.

## Components

### Buttons
- **Primary Button (Deep Navy):** Background `#1e3a8a`, text `#ffffff`, height 48px, horizontal padding `space-lg`, border-radius 8px. Hover: `#172554`. Focus: 3px ring of `#93c5fd`.
- **Secondary Button (Clinical Teal):** Background `#0d9488`, text `#ffffff`. Used for "Book Appointment", "Consult Online". Hover: `#0f766e`.
- **Emergency Button (24/7 SOS):** Background `#dc2626`, text `#ffffff`, accompanied by a pulsating emergency beacon icon. Hover: `#b91c1c`. Always accessible on mobile header/floating bar.
- **Subtle/Ghost Button:** Background `#f0f9ff`, text `#1e3a8a`, border 1px solid `#bae6fd`. Hover: `#e0f2fe`.

### Cards & Department Panels
- **Multi-Specialty Card:** Surface `#ffffff`, border 1px solid `#e2e8f0`, border-radius 16px (`rounded-2xl`). Header features an icon container with a soft healthcare ice-blue background (`#e0f2fe`) housing a clinical teal (`#0d9488`) icon.
- **Emergency Alert Card:** Surface `#fef2f2`, border 1.5px solid `#fecaca`, border-radius 16px. Typography in `#991b1b` and `#dc2626`.

### Form Fields & Booking Controls
- **Inputs & Selects:** Height 48px, background `#ffffff`, border 1px solid `#cbd5e1`, border-radius 8px, text `#1e293b`, placeholder `#94a3b8`.
- **Focus State:** Border color `#0d9488` with a 3px glow ring of `rgba(20, 184, 166, 0.2)`.
- **Date/Slot Selection Pills:** Default: background `#ffffff`, border 1px solid `#e2e8f0`. Selected: background `#1e3a8a`, text `#ffffff`, border-color `#1e3a8a`.

### Status Chips & Badges
- **24/7 Availability Badge:** Pill-shaped, background `#ecfdf5`, border 1px solid `#a7f3d0`, text `#065f46`, leading glowing green dot.
- **Emergency Badge:** Pill-shaped, background `#fef2f2`, border 1px solid `#fecaca`, text `#991b1b`, bold weight.
- **OPD Queue Chip:** Pill-shaped, background `#f0f9ff`, border 1px solid `#bae6fd`, text `#0369a1`.

### Checkboxes & Radios
- Sizing 20x20px, border 1.5px solid `#94a3b8`, border-radius 4px for checkboxes, full circle for radios. Checked fill `#1e3a8a` with crisp white checkmark/dot.

### Doctor Profile Row & Quick Vitals List
- Divided by hairline borders (`#f1f5f9`), with alternating soft hover states using `#f8fafc`. Doctor qualification tags presented in `label-sm` with `#0f172a` badge tags.