---
name: Modern Engineering Portfolio
colors:
  surface: '#0f131d'
  surface-dim: '#0f131d'
  surface-bright: '#353944'
  surface-container-lowest: '#0a0e18'
  surface-container-low: '#171b26'
  surface-container: '#1c1f2a'
  surface-container-high: '#262a35'
  surface-container-highest: '#313540'
  on-surface: '#dfe2f1'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dfe2f1'
  inverse-on-surface: '#2c303b'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#adc6ff'
  on-tertiary: '#002e6a'
  tertiary-container: '#71a1ff'
  on-tertiary-container: '#00367a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#0f131d'
  on-background: '#dfe2f1'
  surface-variant: '#313540'
  surface-base: '#0B0F19'
  surface-card: '#111827'
  surface-card-hover: '#1F2937'
  border-subtle: rgba(255, 255, 255, 0.08)
  border-active: rgba(16, 185, 129, 0.4)
  text-primary: '#F9FAFB'
  text-secondary: '#9CA3AF'
  text-muted: '#6B7280'
  glow-emerald: rgba(16, 185, 129, 0.15)
  glow-cyan: rgba(6, 182, 212, 0.15)
  tag-kotlin: '#7F52FF'
  tag-compose: '#4285F4'
  tag-flutter: '#02569B'
  tag-webrtc: '#FF6B6B'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.05em
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
  margin: 2rem
  margin-mobile: 1rem
  margin-desktop-max: 80rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4.5rem
---

## Brand & Style

This design system establishes an executive, production-grade visual language for a Senior Mobile Application Developer. It transitions traditional CV documentation into a high-octane, dark-mode software engineering showcase. The tone is authoritative, technically precise, and unmistakably modern. 

The aesthetic synthesizes **deep charcoal and slate surfaces** with **neon electric luminescence** (emerald, cyan, and electric blue) and **frosted glassmorphism**. The UI radiates technical mastery through sharp structural boundaries, high-contrast typography, and glowing telemetry indicators. Every element feels compiled, optimized, and engineered for high-performance mobile and real-time computing contexts.

## Colors

The color system operates on an absolute dark-mode foundation. Deep slate `#0B0F19` serves as the canvas substrate, while `#111827` structures card primitives and containment surfaces. 

- **Primary (`#10B981` Emerald)**: Represents active runtime status, production readiness, and primary interactive affordances.
- **Secondary (`#06B6D4` Cyan)**: Drives architecture callouts, metrics, and secondary interactive flows.
- **Tertiary (`#3B82F6` Electric Blue)**: Signifies networking, platform capabilities, and external hyperlinks.
- **Specialized Tech Badges**: Specific accents (Kotlin Purple, Compose Blue, Flutter Navy, WebRTC Coral) are isolated within badge contexts to maintain visual hierarchy without polluting overall UI cohesion.

## Typography

The type scale combines three distinct typefaces to enforce hierarchy:
1. **Plus Jakarta Sans** provides a geometric, executive headline presence with tight tracking to express confidence and senior-level seniority.
2. **Inter** ensures clarity and readability for long-form case studies, app feature breakdowns, and professional background.
3. **JetBrains Mono** acts as the technical voice of the portfolio, styling metadata, architecture tags (MVI, Clean Arch, Coroutines), terminal snippets, and numeric milestones.

## Layout & Spacing

The layout structure relies on a strict 12-column responsive fluid grid with a maximum content container width of `80rem` (1280px). 

- **Desktop (>= 1024px)**: 12 columns, `1.5rem` (24px) gutters, `2rem` (32px) margins. Section anchors use `space-3xl` (72px) vertical rhythms to maintain high breathing room between distinct career areas.
- **Tablet (768px - 1023px)**: 8 columns, `1.5rem` gutters, `1.5rem` outer margins.
- **Mobile (< 768px)**: 4 columns, `1rem` (16px) gutters, `1rem` outer canvas padding. Grids collapse into vertical stacks with `space-lg` card separators.

## Elevation & Depth

Depth is established through physical glass layering and subtle illumination cones rather than heavy, opaque drop shadows:

- **Level 0 (Canvas substrate)**: Solid `#0B0F19`.
- **Level 1 (Default Containers & Cards)**: Translucent `#111827` at 70% opacity backed by a `12px` Gaussian backdrop blur. Framed by a 1px border `rgba(255, 255, 255, 0.08)`.
- **Level 2 (Active/Hover Cards)**: `#1F2937` at 85% opacity with `16px` backdrop blur, 1px border highlighted to `rgba(16, 185, 129, 0.4)`, complemented by a diffused ambient drop shadow: `0 10px 30px -10px rgba(16, 185, 129, 0.25)`.
- **Level 3 (Modals & Command Palettes)**: High-translucency overlay with `24px` backdrop blur, crisp top highlight (`1px solid rgba(255, 255, 255, 0.2)`), and deep ambient base shadow (`0 25px 50px -12px rgba(0, 0, 0, 0.7)`).

## Shapes

The geometric signature uses consistent, balanced radii (`roundedness: 2`). Standard interactive targets, code containers, and card primitives employ an 8px (`0.5rem`) radius. Elevated project containers, interactive modals, and showcase panels scale up to 16px (`1rem`). 

Status indicators and tech badges apply pill contours (`9999px`) to immediately signal categorized, non-textual data points.

## Components

### Buttons
- **Primary Action**: Electric emerald background (`#10B981`) with deep contrast text (`#0B0F19`), font `label-lg`, rounded-md (`0.5rem`). Subtle emerald aura glow on hover (`box-shadow: 0 0 20px rgba(16, 185, 129, 0.4)`).
- **Secondary / Glass**: Translucent slate background (`rgba(17, 24, 39, 0.6)`), 1px border (`border-subtle`), text `#F9FAFB`. Shifts border to cyan (`#06B6D4`) on hover.
- **Ghost / Link**: Unbordered, JetBrains Mono font, emerald underline on hover with dynamic arrow translation icon.

### Project & Experience Cards
- Built using **Level 1 Glassmorphism** styling.
- Header contains app title and platform icons (Android, WebRTC, Jetpack Compose).
- Body renders primary engineering contributions with high legibility.
- Footer features inline tag groupings and direct outbound repository/store action triggers.

### Technology Chips & Status Badges
- Utilizes `label-sm` font in JetBrains Mono.
- Encased in a pill-shaped translucent wrapper (`rgba(255, 255, 255, 0.04)`) with an accented 1px border matching the respective tech category color.
- Available active states feature a pulsating 6px circular indicator dot (e.g., green dot for "Live on Play Store" or "Available for Architecture Consultation").

### Metric Telemetry Modules
- Grid modules built for showcasing key performance statistics (e.g., "1M+ Downloads", "99.9% Crash-Free", "Sub-100ms Latency").
- Headline number rendered using `headline-xl` in electric gradient (emerald to cyan), paired with a `label-md` description.

### Input & Contact Fields
- Low-profile inputs using background `#111827` at 80% opacity, 1px border (`border-subtle`), placeholder text `#6B7280`.
- Focus state activates an electric cyan hairline stroke with `0 0 0 1px #06B6D4` and cyan focus ring aura.
