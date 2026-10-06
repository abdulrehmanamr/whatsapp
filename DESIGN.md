---
name: Calm Operator Workspace
colors:
  surface: '#f5faff'
  surface-dim: '#d1dbe4'
  surface-bright: '#f5faff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eaf5fe'
  surface-container: '#e5eff8'
  surface-container-high: '#dfeaf2'
  surface-container-highest: '#d9e4ec'
  on-surface: '#131d23'
  on-surface-variant: '#404944'
  inverse-surface: '#283238'
  inverse-on-surface: '#e8f2fb'
  outline: '#707973'
  outline-variant: '#bfc9c2'
  surface-tint: '#2c6951'
  primary: '#003323'
  on-primary: '#ffffff'
  primary-container: '#054c36'
  on-primary-container: '#7ebb9f'
  inverse-primary: '#95d4b6'
  secondary: '#006b5f'
  on-secondary: '#ffffff'
  secondary-container: '#8cf1e1'
  on-secondary-container: '#006f64'
  tertiary: '#003413'
  on-tertiary: '#ffffff'
  tertiary-container: '#004d1f'
  on-tertiary-container: '#08c95d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b1f0d1'
  primary-fixed-dim: '#95d4b6'
  on-primary-fixed: '#002115'
  on-primary-fixed-variant: '#0d513a'
  secondary-fixed: '#8ff4e3'
  secondary-fixed-dim: '#72d8c8'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005047'
  tertiary-fixed: '#66ff8e'
  tertiary-fixed-dim: '#3de273'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005322'
  background: '#f5faff'
  on-background: '#131d23'
  surface-variant: '#d9e4ec'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: -0.005em
  title-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: '0'
  body-lg:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: '0'
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.02em
  caption-timestamp:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 14px
    letterSpacing: '0'
  code-snippet:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: '0'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 0.75rem
  gutter-desktop: 1rem
  margin: 1rem
  margin-desktop: 1.5rem
  space-xxs: 0.125rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
  space-2xl: 2rem
---

## Brand & Style

This design system is engineered for dense, high-concurrency customer support operations where clarity, emotional composure, and speed-to-action are paramount. Built around the familiar spatial logic of WhatsApp Web, it translates instant messaging affordances into an enterprise-grade productivity environment.

The design movement combines **Corporate Modernism** with **Calm Utility**:
- **Zero-Cognitive Friction:** The interface recedes into the background so support agents can process hundreds of interactions without visual exhaustion.
- **Differentiated Actors:** Distinct visual vocabularies identify incoming customer requests, automated AI drafts, and human operator interventions instantly.
- **Tactile Density:** Snappy transitions, micro-badges, and tight vertical rhythm maximize screen real estate across widescreen monitors without clutter.
- **Authoritative Restraint:** Rich emerald accents replace loud notification reds, reinforcing trust, system health, and resolution focus.

## Colors

The palette balances WhatsApp's signature functional greens with an executive-grade slate and canvas architecture. 

### Core Hierarchy
- **Primary (`#054C36`):** Deep evergreen for primary action bars, persistent navigation states, primary buttons, and key interactive highlights.
- **Secondary (`#128C7E`):** Mid-tone teal-emerald reserved for active states, link anchors, verified badges, and operator focus rings.
- **Tertiary Accent (`#25D366`):** Vibrant WhatsApp green applied strictly to live connectivity pings, online indicators, and delivered receipt ticks.
- **Neutral Dark (`#111B21`):** High-contrast deep slate for primary typography and high-priority message copy.

### Functional Message Canvas & Actors
- **Customer Incoming (`#FFFFFF`):** High-purity white message bubbles with subtle border separation (`#E9EDEF`) to ensure optimal contrast against the canvas.
- **Customer Outgoing (`#D9FDD3`):** Classic soft green tint indicating dispatched customer replies.
- **Operator Intervention (`#E2F7CB`):** Delicate mint tint providing unmistakable recognition for human handoff actions.
- **AI Copilot Container:** Surface `#E7F8F0`, accent highlight `#D1F4E4`, border `#A8E5C8`, and text `#0A5C36` to denote machine-suggested responses and automated routing workflows.
- **Workspace Canvas (`#F0F2F5`):** Restful cool-gray foundational shell that prevents eye strain across multi-hour shifts. Conversation viewport utilizes a subtle tint (`#EFEAE2` at 40% blend) referencing classic chat surfaces.
- **Structural Dividers (`#E2E8F0` / `#E9EDEF`):** Hairline borders establishing razor-sharp spatial divisions.

## Typography

The typographic hierarchy is executed exclusively in **Inter** to ensure maximum legibility at micro-scales, dense tabular alignments, and fast conversational scanning.

- **Conversation Weight Distribution:** Primary message content uses `body-md` (14px/20px) with Regular (400) weight for unstrained reading. Sender handles, channel badges, and thread subjects use `title-sm` (13px/18px) with Semi-Bold (600) for distinct anchoring.
- **Micro-Badging & Status:** Metadata, SLA count-downs, delivery stamps, and AI confidence ratings leverage `label-sm` (11px/14px) and `caption-timestamp` to remain subservient to message copy.
- **Tabular Numerics:** All timestamps, queue counts, unread counter badges, and phone numbers must activate tabular numeric glyphs (`font-feature-settings: "tnum"`) to eliminate layout jitter during high-throughput updates.

## Layout & Spacing

The workspace implements a structured multi-pane operator layout designed to eliminate context-switching.

### Structural Layout Model
- **Three-Column Productivity Canvas:**
  1. **Global App Rail (56px fixed):** Icon-only access to queues, analytics, channel routing, and settings.
  2. **Thread Master List (320px–380px fixed):** Search bar, triage filters, and virtualized conversation items.
  3. **Active Conversation Viewport (Flex 1, min 480px):** Dynamic message timeline and rich input dock.
  4. **Context / Copilot Inspector (340px–400px collapsible):** Customer CRM context, WhatsApp template selectors, AI drafting tools, and notes.

### Spacing Rhythm
- Compact internal component spacing is strictly locked to a 4px/8px modular rhythm.
- Vertical thread gaps between adjacent messages from the same sender use `space-xs` (4px); transitions between distinct senders use `space-sm` (8px).
- Internal message bubble padding is asymmetric: `space-sm` (8px) top, `space-md` (12px) horizontal, and `space-xs` (4px) bottom to integrate the inline floating timestamp.

### Responsive Breakpoints & Reflow
- **Desktop (≥ 1440px):** Full four-pane workspace active simultaneously.
- **Compact Desktop / Laptop (1024px – 1439px):** Inspector defaults to collapsible fly-out drawer activated by the top bar.
- **Tablet / Split View (< 1024px):** Thread master list and active chat viewport toggle via standard master-detail stack navigation.

## Elevation & Depth

Visual separation relies on **tonal contrast** and **crisp 1px borders** rather than diffuse drop shadows. This maintains a clean, low-latency feel characteristic of focused operating consoles.

### Elevation Hierarchy
- **Level 0 (Base Canvas):** Background foundation (`#F0F2F5`). Completely matte with no depth.
- **Level 1 (Panels & Surfaces):** Left navigation, conversation header, and side inspectors rendered in pure `#FFFFFF` or pale slate-white, bounded by 1px solid `#E9EDEF` dividers.
- **Level 2 (Floating Bubbles & Cards):** Message bubbles float over the background canvas with a targeted micro-shadow: `0 1px 0.5px rgba(11, 20, 26, 0.12)`.
- **Level 3 (AI Suggestion Docks & Overlays):** Copilot suggestion banners and internal floating quick-action docks use an ambient shadow: `0 4px 12px rgba(5, 76, 54, 0.08)` paired with an emerald tinted border (`#A8E5C8`).
- **Level 4 (Modals, Popovers & Context Menus):** High overlays employ `0 8px 24px rgba(17, 27, 33, 0.14)` bounded by a crisp `#E2E8F0` border.

## Shapes

The design system utilizes **Soft** corner architecture (`roundedness: 1`), keeping components structured and enterprise-ready, while applying rounded pill structures strictly for micro-badges and interactive action capsules.

### Shape Geometry Rules
- **Panels, Panels Cards & Inputs:** Radius `0.375rem` (6px) or `0.25rem` (4px) to retain maximum linear screen efficiency.
- **Message Bubbles:** Asymmetric rounding:
  - Incoming customer bubble: `0.5rem` (8px) on all corners except top-left (`0.125rem` / 2px anchor notch).
  - Outgoing operator/agent bubble: `0.5rem` (8px) on all corners except top-right (`0.125rem` / 2px anchor notch).
- **Status Pills, Unread Badges & SLA Counters:** Pure pill form (`rounded-full` / `9999px`) to immediately contrast with rectangular message geometry.
- **Avatars:** Circular (`50%` radius) for end-customers; squircle (`0.5rem` / 8px radius) with an emerald icon for automated AI bots to differentiate human from synthetic actors.

## Components

### Buttons
- **Primary Action:** Solid deep emerald `#054C36` background, crisp white `#FFFFFF` text, `0.375rem` border radius. Hover state transitions to `#0F5132`. Active scale remains firm without bouncing.
- **AI Generate / Copilot Action:** Subtle gradient background from `#E7F8F0` to `#D1F4E4`, border 1px solid `#A8E5C8`, text `#0A5C36`. Accompanied by a 14px sparkle icon.
- **Ghost Utility Buttons:** Pure transparent surface with `#667781` icon/text, switching to `#F0F2F5` on hover.

### Chips & Micro-Badges
- **Unread Counter:** Solid `#25D366` circular or pill badge, high-contrast white text, `700` weight, 11px font size.
- **SLA Alert Badge:** High-urgency tickets receive an amber-tinted badge (`#FEF3C7` background, `#92400E` text) or critical red (`#FEE2E2` background, `#991B1B` text).
- **Channel Indicator:** 14px WhatsApp brand icon positioned at the bottom-right corner of the customer avatar.

### Message Timeline
- **Customer Bubble:** Background `#FFFFFF`, text `#111B21`, border hairline `#E9EDEF`. Timestamp placed bottom-right in `#8696A0`.
- **Outgoing Dispatch Bubble:** Background `#D9FDD3`, text `#111B21`. Includes double-tick receipt icon (`#53BDEB` for read, `#8696A0` for delivered).
- **AI Suggestion Draft Bubble:** Dashed border (`1.5px` dashed `#A8E5C8`) with background `#E7F8F0`. Displays two inline micro-buttons: "Approve & Send" (emerald) and "Edit Draft" (ghost).

### Lists (Thread Items)
- Height: Fixed 72px dense layout.
- States: Active thread item features an active accent border (`3px` solid `#054C36`) on the left border edge with an active background fill of `#F0F2F5`. Hover uses `#F5F6F6`.
- Typography: Contact name truncated in `title-sm`, last message snippet in `body-sm` (`#667781`).

### Input Fields & Message Composer
- **Search Bar:** Height 36px, background `#F0F2F5`, borderless with inset focus ring: `1px solid #128C7E`.
- **Chat Dock Composer:** Multi-line expander with `#FFFFFF` background, subtle upper border `#E2E8F0`, quick template picker trigger button (`/` slash command auto-complete), and audio/attachment triggers.

### Cards & Inspector Panels
- **Customer CRM Profile Card:** Surface `#FFFFFF`, clean divider lines `#E9EDEF`, key-value attributes rendered with `label-sm` for field keys and `body-sm` for editable values.