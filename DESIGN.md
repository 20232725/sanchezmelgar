---
name: Institutional Intelligence
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c5c5d3'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#8f909d'
  outline-variant: '#444651'
  surface-tint: '#b6c4ff'
  primary: '#b6c4ff'
  on-primary: '#05297a'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#4059aa'
  secondary: '#93ccff'
  on-secondary: '#003351'
  secondary-container: '#3198dc'
  on-secondary-container: '#002c47'
  tertiary: '#4edea3'
  on-tertiary: '#003824'
  tertiary-container: '#004a31'
  on-tertiary-container: '#27c38a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#cce5ff'
  secondary-fixed-dim: '#93ccff'
  on-secondary-fixed: '#001d31'
  on-secondary-fixed-variant: '#004b73'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.025em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  title-sm:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '600'
    lineHeight: 1.5rem
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
  body-sm:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: 1rem
  label-md:
    fontFamily: Inter
    fontSize: 0.8125rem
    fontWeight: '500'
    lineHeight: 1.125rem
  label-sm:
    fontFamily: Inter
    fontSize: 0.6875rem
    fontWeight: '600'
    lineHeight: 0.875rem
    letterSpacing: 0.05em
  metric-val:
    fontFamily: Inter
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.02em
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
  margin-lg: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 1.75rem
---

## Brand & Style

This design system establishes an institutional-grade visual foundation tailored for mission-critical machine learning, quantitative finance, and deep data analytics. Designed for quantitative researchers, data engineers, and risk officers, the interface communicates algorithmic certainty, precision, and auditability.

The visual style unites **Corporate / Modern** rigor with high-density data architecture:
- **Calm, Deliberate Restraint**: Deep institutional navy foundations suppress visual noise, allowing critical analytical outputs and data artifacts to surface immediately.
- **Scientific Utility**: Dense metric groupings, explicit mathematical labeling, and tabular hierarchy prioritize rapid scanability over decorative trends.
- **Instrument Precision**: Interactions feel exact, snappy, and predictable, mirroring high-throughput financial consoles and laboratory instruments.

## Colors

The palette is engineered specifically for long-duration analytical work in dark mode, strictly minimizing retinal fatigue while maximizing signal differentiation.

### Palette Architecture
- **Primary (`#1E3A8A`)**: Institutional Navy anchor. Dictates interactive authority, primary command triggers, navigation states, and baseline selected surfaces.
- **Secondary (`#0284C7`)**: Electric Cerulean. Powers predictive model inferences, confidence boundaries, regression pathways, and secondary interactions.
- **Tertiary (`#10B981`)**: Emerald Precision. Highlights validated hypotheses, true positives, positive financial delta, and model convergence.
- **Neutral (`#0F172A`)**: Deep Slate Matrix. Forms the structural spine, providing low-luminance contrast steps across layered dashboards.

### Signal & Diagnostic Roles
- **Negative / Anomaly (`#F43F5E`)**: Coral Crimson. Used exclusively for loss metrics, false positives, out-of-distribution drift, and critical risk thresholds.
- **Attention / Uncertainty (`#F59E0B`)**: Amber Warning. Reserved for indeterminate states, active model drift warnings, and data queue latency.
- **Informational Metric (`#06B6D4`)**: High-luminance Cyan accent used strictly for data visualization series, vector clusters, and real-time telemetry markers.

### Surface Tiers
- **Canvas Base**: `#080D1A` (Foundational background)
- **Surface Level 1**: `#0F172A` (Metric containers, data grids, sidebars)
- **Surface Level 2**: `#1E293B` (Nested cards, inspector drawers, modal overlays)
- **Border Subtle**: `rgba(255, 255, 255, 0.08)`
- **Border Focus / Active**: `rgba(56, 189, 248, 0.40)`

## Typography

Typography prioritizes micro-legibility at variable display scales. Inter delivers neutral, systematic clarity across both data tables and large numerical dashboard cards.

### Tabular Numerical Configuration
All metric readouts, table columns, statistical indices, and latency trackers must activate tabular lining figures (`font-variant-numeric: tabular-nums lining-nums;`). This guarantees strict vertical column alignment across rapidly updating streaming data.

### Structural Roles
- **Display & Headlines**: Used strictly for model identifiers, pipeline status, and primary operational screens. Character spacing is drawn inward to maintain compactness.
- **Metric Value (`metric-val`)**: Optimized for high-impact KPI summary cards, displaying probabilities, F1 scores, loss curves, and asset exposures.
- **Labels (`label-sm`)**: Styled with uppercase casing and subtle letter spacing (`0.05em`) for dataset headers, model checkpoints, matrix dimensions, and badge classifications.

## Layout & Spacing

The layout philosophy follows a high-density, multi-pane workbench paradigm engineered for continuous visual telemetry and exploratory model diagnostics.

### Grid Framework
- **Desktop (1440px+)**: 12-column fluid grid with `1.5rem` gutters and `2rem` margins. Supports split-pane operations (e.g., parameter inspection panels alongside real-time ROC curves and confusion matrices).
- **Tablet / Laptop (1024px - 1439px)**: 8-column layout with `1rem` gutters, reflowing complex multi-metric views into vertically stacked analytical panels.
- **Mobile (< 1024px)**: 4-column layout with `1rem` margins. Dense table interfaces collapse into structured stacked key-value summaries; secondary inspection panes become sliding bottom drawers.

### Spacing Rhythms
- Use `space-xs` (4px) and `space-sm` (8px) for tightly grouped mathematical markers, tags, and inline label-value pairs.
- Use `space-md` (12px) for internal padding within card modules, inputs, and button groups.
- Use `space-lg` (20px) and `space-xl` (28px) exclusively for major diagnostic panel divisions and canvas sector margins.

## Elevation & Depth

Visual hierarchy is maintained through structured **tonal layers** paired with **low-contrast outlines**, avoiding heavy drop shadows that clutter analytical displays.

### Layer Hierarchy
- **Canvas (`#080D1A`)**: Baseline operational plane for page-level structural wrappers.
- **Level 1 Containers (`#0F172A`)**: Standard baseline cards, metric wrappers, and table rows. Outlined with `1px solid rgba(255, 255, 255, 0.08)`.
- **Level 2 Elevators (`#1E293B`)**: Interactive hovered elements, floating control bars, and contextual tooltips. Outlined with `1px solid rgba(255, 255, 255, 0.14)`.
- **Level 3 Overlays (`#24324D`)**: Modal dialogs, filter dropdown menus, and algorithmic configuration sheets. Elevated using a subtle institutional blue ambient shadow: `0 12px 32px -4px rgba(2, 6, 23, 0.7), 0 0 0 1px rgba(255, 255, 255, 0.12)`.

### Visualization Depth
Data visualization marks (lines, points, area charts) employ selective multi-layered opacity fills (e.g., 15% opacity primary fills under 100% opacity hairline strokes) to show model confidence intervals without obscuring grid baselines.

## Shapes

The design system enforces a **Soft (`1`)** shape language. This conservative curve architecture provides immediate professional sobriety while preventing harsh geometric visual fatigue.

### Radius Assignments
- **Micro Radii (`0.25rem` / 4px)**: Applied to table cells, inline chips, status pills, input controls, action buttons, and mathematical tags.
- **Container Radii (`0.5rem` / 8px)**: Applied to main analytic metric cards, charts, inspectors, and data grid viewports.
- **Overlay Radii (`0.75rem` / 12px)**: Applied to global dialogs, model inference configuration drawers, and application-level floating command bars.

## Components

### Buttons
- **Primary**: Solid institutional navy fill (`#1E3A8A`), high-contrast text (`#FFFFFF`), `0.25rem` radius, subtle top-highlight border (`rgba(255, 255, 255, 0.15)`). Hover state shifts brightness smoothly without chromatic shift.
- **Secondary / Ghost**: Transparent fill, `1px solid rgba(255, 255, 255, 0.12)`, text `#E2E8F0`. Hover triggers background fill of `#1E293B`.
- **Destructive**: Subdued coral boundary with semi-transparent coral tint (`rgba(244, 63, 94, 0.1)`), escalating to solid `#F43F5E` on confirmed execution.

### Metric Cards & Key-Value Blocks
- Encapsulated within `#0F172A` containers, 1px border.
- Structure: Micro uppercase label (`label-sm`) at the top, tabular numerical metric (`metric-val`) in the center, and baseline delta indicator at the bottom.
- Visual trend indicator uses tertiary `#10B981` (positive delta) or coral `#F43F5E` (negative delta) accompanied by directional SVG micro-arrows and baseline epoch comparisons.

### Chips & Mathematical Badge Indicators
- Fixed height `22px`, `0.25rem` radius, horizontal padding `6px`.
- Rendered with low-opacity semantic background (12%) and solid foreground text.
- Formats:
  - **Class Labels**: YES (`rgba(16, 185, 129, 0.12)` text `#34D399`) vs NO (`rgba(244, 63, 94, 0.12)` text `#FB7185`).
  - **Model Metrics**: Precision, Recall, and ROC AUC pills displaying formatted mathematical pairs (e.g., `AUC: 0.984`).

### Data Grids & Tabular Views
- Header: `#0F172A`, text `#94A3B8`, `label-sm` uppercase, sticky positioning with bottom divider line `rgba(255, 255, 255, 0.08)`.
- Rows: Monospaced or tabular-proportional alignment, height `40px` for optimal density. Alternate row banding is avoided; rows delineate via subtle `1px` bottom borders and hover transitions to `#1E293B`.
- Integrated sparklines and mini distribution histograms render inline within designated columns using `#0284C7`.

### Input Fields & Parameter Controls
- Background `#0B132B`, border `1px solid rgba(255, 255, 255, 0.12)`, text `#F8FAFC`.
- Focus state applies a crisp cyan glow: `border-color: #38BDF8; box-shadow: 0 0 0 1px #38BDF8`.
- Hyperparameter numeric steppers display increment/decrement triggers inline with mono-spaced readouts.

### Checkboxes & Radios
- Square with micro radius `2px` for checkboxes; circular for radios.
- Unchecked: `1px solid rgba(255, 255, 255, 0.25)` over dark slate surface.
- Checked: Solid `#1E3A8A` background containing crisp white micro-check vector or center dot.