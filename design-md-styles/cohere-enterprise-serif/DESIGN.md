# Design System: Cohere Enterprise Serif

## 1\. Visual Theme & Atmosphere

Cohere-inspired enterprise landing page. Ideal for enterprise ai, infraestrutura de dados, plataformas b2b, apis corporativas. AI-ready template.

*   Density: 3/10 — Airy
*   Variance: 2/10 — Structured
*   Motion: 8/10 — Cinematic

## 2\. Color Palette & Roles

*   **Preto** (#000000) — Dark surface, primary background
*   **Branco** (#ffffff) — Light surface, card backgrounds
*   **Azul Interação** (#1863dc) — Accent highlight, links and focus states
*   **Cinza Cool** (#d9d9dd) — Secondary text, borders, muted elements
*   **Quase Preto** (#212121) — Deep contrast surface
*   **Slate** (#93939f) — Extended palette, decorative use
*   **Cinza Claro** (#f2f2f2) — Secondary text, borders, muted elements
*   **Borda** (#e5e7eb) — Extended palette, decorative use

## 3\. Typography Rules

*   **Display / Hero:** Georgia — Weight 700, tight tracking, used for headline impact
*   **Accent:** system-ui for body — Used for decorative or emphasis text
*   **Body:** Georgia — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** Georgia — 0.875rem, weight 500, slight letter-spacing
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

Design a Cohere-inspired enterprise landing page. Bright white canvas with cool gray borders (#d9d9dd). Signature 22px border-radius on all primary cards and containers. Serif display font for headlines at 72px with -1.44px letter-spacing. Ghost/transparent buttons that shift to Interaction Blue (#1863dc) on hover. Deep purple full-width sections for product showcases. Monospace uppercase labels with 0.28px letter-spacing. Nearly colorless palette — black, white, cool grays only.

Last synced: 4/1/2026
