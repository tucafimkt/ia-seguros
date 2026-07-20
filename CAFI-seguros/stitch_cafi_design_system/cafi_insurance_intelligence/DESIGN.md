---
name: CAFI Insurance Intelligence
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#464653'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#767684'
  outline-variant: '#c6c5d5'
  surface-tint: '#4b53bc'
  primary: '#00003c'
  on-primary: '#ffffff'
  primary-container: '#000080'
  on-primary-container: '#777eea'
  inverse-primary: '#bfc2ff'
  secondary: '#006e2f'
  on-secondary: '#ffffff'
  secondary-container: '#6bff8f'
  on-secondary-container: '#007432'
  tertiary: '#220000'
  on-tertiary: '#ffffff'
  tertiary-container: '#4d0000'
  on-tertiary-container: '#d96756'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e0e0ff'
  primary-fixed-dim: '#bfc2ff'
  on-primary-fixed: '#00006e'
  on-primary-fixed-variant: '#3239a3'
  secondary-fixed: '#6bff8f'
  secondary-fixed-dim: '#4ae176'
  on-secondary-fixed: '#002109'
  on-secondary-fixed-variant: '#005321'
  tertiary-fixed: '#ffdad4'
  tertiary-fixed-dim: '#ffb4a8'
  on-tertiary-fixed: '#410000'
  on-tertiary-fixed-variant: '#82271c'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
  brand-navy: '#000080'
  brand-green: '#22C55E'
  status-critical: '#EF4444'
  status-warning: '#F59E0B'
  status-urgent: '#F97316'
  status-neutral: '#0F172A'
  surface-bg: '#F8FAFC'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  mono-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  container-padding: 24px
  gutter-grid: 20px
  card-gap: 16px
  section-margin: 32px
---

## Brand & Style

The design system is built on a foundation of **Modern Corporate Minimalism**. It aims to evoke a sense of absolute reliability, speed, and intelligence, transforming the complex task of insurance renewal into a streamlined, automated experience.

The visual language borrows from the "Productive Professionalism" found in platforms like HubSpot and Pipedrive—prioritizing clarity of data and efficiency of action. It balances a high-trust financial aesthetic with contemporary SaaS sensibilities: heavy use of whitespace, refined typography, and a "breathable" interface that prevents cognitive overload during high-volume operations.

Key aesthetic drivers include:
- **Clarity over Decoration:** Every element serves a functional purpose in the renewal funnel.
- **Trust-Centric:** Use of stable, deep tones balanced by clean, optimistic accents.
- **Automated Precision:** Visual cues that distinguish between human actions and AI-driven processes (ElevenLabs/WhatsApp).

## Colors

The palette is anchored by the **Navy Blue** of the brand logo, symbolizing institutional stability and financial security. This is contrasted with a vibrant **Success Green** that represents renewal, growth, and completion.

- **Primary (Navy):** Used for global navigation, primary headings, and high-level structural elements.
- **Secondary (Green):** Reserved for "success" states, completed renewals, and primary action triggers.
- **Background Strategy:** The system utilizes a "Paper-on-Cloud" approach, where cards and containers are pure white (`#FFFFFF`) against a very soft grey-blue background (`#F8FAFC`) to create depth without using heavy shadows.
- **The Traffic Light System:** A dedicated functional palette for policy urgency:
    - **Safe (>30d):** Green
    - **Warning (15-30d):** Yellow/Gold
    - **Urgent (7-15d):** Orange
    - **Critical (<7d):** Red
    - **Expired:** Deep Black/Slate

## Typography

This design system uses a dual-font strategy to balance character with utility. 

**Hanken Grotesk** is used for headlines and KPIs. Its sharp, contemporary geometry provides a "fintech" feel that feels modern and precise. 

**Inter** is the workhorse for all UI elements, data tables, and body text. It is chosen for its exceptional legibility in data-dense environments (like policy lists and CRM transcripts).

- **Hierarchy:** Maintain a clear distinction between data labels (small, uppercase, high tracking) and data values (standard weight, high contrast).
- **KPIs:** Large numbers in Hanken Grotesk Bold are the primary focal point of the dashboard.

## Layout & Spacing

The system follows a **12-column Fixed-Fluid Hybrid Grid**. 
- **Sidebar:** Fixed at 260px for navigation and administrative tools.
- **Main Content:** Fluid container with a max-width of 1600px to ensure legibility on ultra-wide monitors.
- **Spacing Rhythm:** Uses a 4px baseline grid. Most components use 16px (4x) or 24px (6x) increments to maintain a spacious, "HubSpot-like" feel.

**Responsive Behavior:**
- **Desktop (1280px+):** Full 12-column layout.
- **Tablet (768px - 1024px):** Sidebar collapses to icons only; 2-column card layouts for KPIs.
- **Mobile:** Not the primary use case, but the layout reflows to a single column with simplified data tables (horizontal scroll enabled for policy rows).

## Elevation & Depth

To maintain a clean, professional aesthetic, this design system avoids heavy shadows in favor of **Tonal Layering** and **Soft Ambient Occlusion**.

- **Level 0 (Background):** `#F8FAFC` - The canvas.
- **Level 1 (Cards/Tables):** `#FFFFFF` - White surfaces with a 1px border of `#E2E8F0` and a very soft 4px blur shadow (`0 2px 4px rgba(0,0,0,0.02)`).
- **Level 2 (Hover/Active):** Slightly more pronounced shadow (`0 10px 15px rgba(0,0,0,0.05)`) to indicate interactivity.
- **Depth Metaphor:** Elements that represent "AI Intelligence" (like ElevenLabs summaries) may use a subtle colored glow or a light gradient border to distinguish them from standard manual data entry.

## Shapes

The design uses a **Medium Rounded** approach (8px / 0.5rem) to soften the "institutional" feel of insurance software and make it feel more like a modern tool.

- **KPI Cards:** Use `rounded-lg` (16px) to stand out as primary dashboard objects.
- **Buttons and Inputs:** Use standard 8px corners.
- **Status Pills:** Use fully rounded (pill-shaped) geometry to differentiate them from clickable buttons.

## Components

### KPIs & Indicators
Cards should feature a large Hanken Grotesk value, a small label, and a trend indicator or a color-coded top-border representing the specific category (e.g., Red for "Vencidas").

### Data Tables (The "Semáforo")
- Rows should have a subtle left-border (4px) color-coded by the "Días restantes" logic.
- Backgrounds should remain white; avoid full-row background colors to maintain readability.
- **Action Icons:** Use clean, stroke-based icons (Lucide or Phosphor) for "Call," "WhatsApp," and "View Profile."

### Switches (Automation)
Switches for AI rules should be larger than standard UI toggles, using the brand-green for the 'on' state. Include a "Status" label next to the switch (e.g., "Activo / Inactivo").

### Buttons
- **Primary:** Solid Brand Navy, white text.
- **Secondary:** White background, Brand Navy border and text.
- **Success/Automation:** Solid Brand Green for "Send Now" or "Start Campaign."

### AI Transcription Cards
Use a distinct light-blue background (`#F0F9FF`) or a specific "AI" icon badge to separate human notes from machine-generated summaries. Use a monospace font variant for transcripts if needed for a "raw data" feel.