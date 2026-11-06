---
name: Football Fan Arena
colors:
  surface: '#051424'
  surface-dim: '#051424'
  surface-bright: '#2c3a4c'
  surface-container-lowest: '#010f1f'
  surface-container-low: '#0d1c2d'
  surface-container: '#122131'
  surface-container-high: '#1c2b3c'
  surface-container-highest: '#273647'
  on-surface: '#d4e4fa'
  on-surface-variant: '#bacbb9'
  inverse-surface: '#d4e4fa'
  inverse-on-surface: '#233143'
  outline: '#859585'
  outline-variant: '#3b4a3d'
  surface-tint: '#00e475'
  primary: '#75ff9e'
  on-primary: '#003918'
  primary-container: '#00e676'
  on-primary-container: '#00612e'
  inverse-primary: '#006d35'
  secondary: '#bdf4ff'
  on-secondary: '#00363d'
  secondary-container: '#00e3fd'
  on-secondary-container: '#00616d'
  tertiary: '#ffdddc'
  on-tertiary: '#680014'
  tertiary-container: '#ffb6b6'
  on-tertiary-container: '#ab0028'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#62ff96'
  primary-fixed-dim: '#00e475'
  on-primary-fixed: '#00210b'
  on-primary-fixed-variant: '#005226'
  secondary-fixed: '#9cf0ff'
  secondary-fixed-dim: '#00daf3'
  on-secondary-fixed: '#001f24'
  on-secondary-fixed-variant: '#004f58'
  tertiary-fixed: '#ffdad9'
  tertiary-fixed-dim: '#ffb3b3'
  on-tertiary-fixed: '#400009'
  on-tertiary-fixed-variant: '#920021'
  background: '#051424'
  on-background: '#d4e4fa'
  surface-variant: '#273647'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
  stat-display:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 32px
    letterSpacing: -0.02em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
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

This design system channels the electric, raw tension of match night under stadium floodlights. Designed for an impassioned, global football supporter base, the aesthetic bridges cutting-edge sports tech with communal terrace culture. It evokes high adrenaline, loyalty, and sharp tactical clarity while remaining clean and focused.

The visual style blends **Atmospheric Dark Glassmorphism** with **High-Contrast Athletic Modernism**. Translucent charcoal surfaces float over deep navy voids, enriched with razor-thin structural borders and laser-focused neon accents. The environment avoids gratuitous noise, channeling the visual precision of live broadcast scoreboards and the communal vitality of the pitch.

## Colors

The palette establishes an immersive stadium night atmosphere:

- **Foundation Layers**: Deep stadium navy (`#0B0F19`) anchors the canvas background. Surface elevation tiers move up to deep pitch charcoal (`#111827`, `#1A2234`) and interactive element surfaces (`#1F293D`).
- **Primary Accent (`#00E676`)**: Electric Pitch Green drives primary actions, live minute counters, winning prediction indicators, and active navigation nodes.
- **Secondary & Tactical Accents**: 
  - Electric Cyan (`#00E5FF`): Spotlights community banter, live polls, and tactical transfer updates.
  - Rivalry Crimson (`#FF1744`): Designates red cards, derby alerts, negative forms, and critical friction states.
  - Warning Amber (`#FFB300`): Highlights bookings, imminent match kickoffs, and coin/odds multipliers.
- **Text & Contrast Structure**: Off-white primary text (`#F8FAFC`) delivers maximum legibility on dark layers, while muted slate (`#94A3B8`) handles meta labels and timestamps. Borders leverage crisp hairline alpha states (`rgba(255, 255, 255, 0.08)` and `rgba(0, 230, 118, 0.2)`).

## Typography

The typographic hierarchy couples the punchy, geometric weight of Plus Jakarta Sans for club names, scoreboard heads, and match titles with the clinical legibility of Inter for continuous banter threads, stats feeds, and odds.

- **Tabular Numerics**: Activate `font-feature-settings: "tnum" on, "cv05" on` across all match tickers, table standings, prediction sliders, and player ratings to prevent layout shift during live score updates.
- **Upper-Case Accents**: Match statuses (`LIVE`, `HT`, `FT`), badge labels, and tournament rounds are styled in uppercase using `label-sm` with tight letter spacing for an authentic stadium broadcast feel.

## Layout & Spacing

The layout is built upon a responsive, fluid container grid configured for mobile matchday speed and desktop analytical depth:

- **Mobile Viewport (up to 767px)**: Single-column stack with dynamic safe areas, 16px lateral padding (`margin`), and 16px gutters (`gutter`). Fast horizontal swipe rails are used for live scores and fixtures.
- **Tablet (768px – 1023px)**: 8-column layout with 24px margins. Content shifts to paired match card arrangements and integrated banter panels.
- **Desktop (1024px+)**: 12-column layout capped at a maximum width of 1440px with 40px outer margins. The page splits into a three-column operational stadium dashboard: Left Navigation / Tables (3 cols), Center Live Matchfeed & Predictions (6 cols), and Right Fan Banter Arena (3 cols).

## Elevation & Depth

Visual hierarchy relies on backdrop diffusion and multi-stop luminescence rather than heavy, opaque drop shadows:

- **Base Layer**: Pure canvas at `#0B0F19`.
- **Level 1 (Card & Board Tile)**: Background fill of `rgba(26, 34, 52, 0.65)` layered with `backdrop-filter: blur(16px)` and an ambient inner outline of `1px solid rgba(255, 255, 255, 0.08)`.
- **Level 2 (Hover & Active Match Tally)**: Background fill of `rgba(31, 41, 61, 0.85)` with `backdrop-filter: blur(24px)` and a subtle directional top-edge highlight of `1px solid rgba(255, 255, 255, 0.16)`.
- **Level 3 (Modals, Overlays & Elevated Drawers)**: Deep charcoal fill `rgba(17, 24, 39, 0.95)`, `backdrop-filter: blur(32px)`, bordered by `1px solid rgba(255, 255, 255, 0.12)`, floating on a soft shadow of `0 20px 40px -10px rgba(0, 0, 0, 0.6)`.
- **Luminescent Accent Glows**: Focused elements (such as match-winning predictions or live radio signals) emit a localized accent aura: `box-shadow: 0 0 20px -4px rgba(0, 230, 118, 0.35)`.

## Shapes

The design system employs a **pill-dominant and softened geometry** (`roundedness: 3`). 

Interactive buttons, prediction chips, score capsules, and status tags feature continuous pill curvature (`9999px` or standard scale tokens) to ensure rapid touch target identification on mobile. Structured data containers, stadium feed cards, and video wrappers utilize the softened `rounded-lg` (2rem / 32px) and standard cards use `rounded` (1rem / 16px), establishing a contemporary sports broadcast interface without harsh corners.

## Components

### Buttons
- **Primary Pill Action**: High-energy `#00E676` background with dark `#0B0F19` bold typography (`label-lg`). Hover shifts saturation with an ambient neon green outer glow.
- **Secondary Glass Button**: Pill shape with `rgba(255, 255, 255, 0.06)` fill, 1px border `rgba(255, 255, 255, 0.12)`, and off-white text (`#F8FAFC`). Hover lifts border illumination to `rgba(255, 255, 255, 0.25)`.
- **Rivalry / Danger Pill**: `#FF1744` background with crisp white typography for high-stakes derby actions or red-alert match events.

### Match Prediction Tally Cards
- Built as frosted glass panels (`rgba(26, 34, 52, 0.65)`).
- Two-team row arrangement with high-resolution crests flanking tabular scores.
- Interactive prediction sliders or three-way outcome buttons (Home / Draw / Away) shaped as full pills. The selected outcome highlights with a 1px border glow of `rgba(0, 230, 118, 0.4)` and a soft fill of `rgba(0, 230, 118, 0.12)`.
- Visual odds / percentage distribution displayed as a segmented progress bar with electric green, slate, and electric cyan segments.

### Chips & Badges
- **Status Badges**: Ultra-compact pills (`label-sm`) featuring a live pulsing dot (e.g., 8px circular indicator pulsating `#00E676` for live matches).
- **Fan Banter Filter Chips**: Ghost pill containers that transition into an electric cyan background with dark text upon selection.

### Bottom Navigation Bar (Mobile)
- Docked glass bar pinned to the viewport base with `rgba(11, 15, 25, 0.85)` background, `backdrop-filter: blur(20px)`, and a 1px top hairline border `rgba(255, 255, 255, 0.08)`.
- Active navigation item features an electric green icon, matching label, and an ambient top or bottom neon green glow indicator line.

### Input Fields & Fan Chat
- Single-line banter inputs and search fields use pill or 16px radius containers filled with `rgba(255, 255, 255, 0.04)` and 1px border `rgba(255, 255, 255, 0.1)`.
- Focused state transitions the border to `rgba(0, 230, 118, 0.5)` with an inner soft green luminescence, while retaining white text entry at 16px to prevent mobile zoom scaling.

### Lists & Leaderboards
- Dense, highly scannable rows separated by `1px solid rgba(255, 255, 255, 0.04)`.
- Supporter ranking positions (1–3) highlighted with metallic micro-badges; dynamic match form displayed using consecutive 5-dot arrays (Green = Win, Slate = Draw, Red = Loss).