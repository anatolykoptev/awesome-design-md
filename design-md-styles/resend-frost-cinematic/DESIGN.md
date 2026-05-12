# Design System: Resend Frost Cinematic

## 1\. Visual Theme & Atmosphere

Resend-inspired cinematic dark landing page. Ideal for apis de email, infraestrutura developer, saas técnico, plataformas de comunicação. AI-ready template.

*   Density: 5/10 — Balanced
*   Variance: 4/10 — Moderate
*   Motion: 8/10 — Cinematic

## 2\. Color Palette & Roles

*   **Preto Void** (#000000) — Dark surface, primary background
*   **Branco Near** (#f0f0f0) — Light surface, card backgrounds
*   **Branco Puro** (#ffffff) — Light surface, card backgrounds
*   **Silver** (#a1a4a5) — Supporting palette color
*   **Laranja** (#ff801f) — Warm accent, call-to-action secondary
*   **Verde** (#22ff99) — Success states, positive indicators
*   **Azul** (#3b9eff) — Secondary accent
*   **Borda Frost** (rgba(214,235,253,0.19)) — Extended palette, decorative use

## 3\. Typography Rules

*   **Display / Hero:** Georgia for hero — Weight 700, tight tracking, used for headline impact
*   **Body:** Georgia for hero — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** Georgia for hero — 0.875rem, weight 500, slight letter-spacing
*   **Monospace:** JetBrains Mono — Used for code, metadata, and technical values

Scale:

*   Hero: clamp(2.5rem, 5vw, 4rem)
*   H1: 2.25rem
*   H2: 1.5rem
*   Body: 1rem / 1.6
*   Small: 0.875rem

## 4\. Component Stylings

*   **Primary Button:** Pill-shaped (9999px) shape. Accent color fill. Hover: 8% darken + subtle lift shadow. Active: -1px translate tactile press. Font weight 600. No outer glows.
*   **Secondary / Ghost Button:** Outline variant. 1.5px border in muted color. Text in primary color. Hover: subtle background fill.
*   **Cards:** Pill-shaped (9999px) corners. Surface background. Subtle shadow (0 2px 12px rgba(0,0,0,0.06)). 1px border stroke.
*   **Inputs:** Label above input. 1px border stroke. Focus ring: 2px accent color offset 2px. Error text below in semantic red. No floating labels.
*   **Navigation:** Primary surface background. Active item: accent color indicator. Font weight 500 when active.
*   **Skeletons:** Shimmer animation matching component dimensions. No circular spinners.
*   **Empty States:** Icon-based composition with descriptive text and action button.

## 5\. Layout Principles

*   **Grid:** CSS Grid primary. Max-width containment: 1280px centered with 1.5rem side padding.
*   **Spacing rhythm:** Balanced. Base unit: 0.5rem (8px).
*   **Section vertical gaps:** clamp(4rem, 8vw, 8rem).
*   **Hero layout:** Split-screen (text left, visual right).
*   **Feature sections:** Zig-zag alternating text+image rows. No 3-equal-columns.
*   **Mobile collapse:** All multi-column layouts collapse below 768px. No horizontal overflow.
*   **z-index contract:** base (0) / sticky-nav (100) / overlay (200) / modal (300) / toast (500).

## 6\. Motion & Interaction

*   **Physics:** Spring — stiffness 120, damping 20. Confident, weighted transitions.
*   **Entry animations:** Fade + translate-Y (16px → 0) over 540ms ease-out. Staggered cascades for lists: 120ms between items.
*   **Hover states:** Scale(1.03) + shadow lift over 200ms.
*   **Page transitions:** Fade + slide (300ms).
*   **Performance:** Only transform and opacity animated. No layout-triggering properties.

## 7\. Anti-Patterns (Banned)

*   No emojis in UI — use icon system only (Lucide, Heroicons)
*   No pure black (#000000) — use off-black or charcoal variants
*   No oversaturated accent colors (saturation cap: 80%)
*   No 3-column equal-width feature layouts — use zig-zag or asymmetric grid
*   No `h-screen` — use `min-h-[100dvh]`
*   No AI copywriting clichés: "Elevate", "Seamless", "Unleash", "Next-Gen"
*   No broken external image links — use picsum.photos or inline SVG
*   No generic lorem ipsum in demos

## AI Prompt

Design a Resend-inspired cinematic dark landing page. Pure black void (#000000) background. Frost blue-tinted borders (rgba(214,235,253,0.19)) on all structural lines. Serif display font at 96px weight 400, line-height 1.00, letter-spacing -0.96px for hero. Geometric sans-serif at 56px with -2.8px letter-spacing for sections. Inter for body. Pill buttons (9999px) with transparent background and frost border. Multi-color accent system: orange (#ff801f), green (#22ff99), blue (#3b9eff). Ring shadow rgba(176,199,217,0.145) 0px 0px 0px 1px.

Last synced: 4/1/2026
