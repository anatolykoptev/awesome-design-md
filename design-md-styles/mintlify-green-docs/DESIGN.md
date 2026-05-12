# Design System: Mintlify Green Docs

## 1\. Visual Theme & Atmosphere

Mintlify-inspired documentation landing page. Ideal for documentação, developer portals, plataformas de docs, knowledge bases. AI-ready template.

*   Density: 3/10 — Airy
*   Variance: 2/10 — Structured
*   Motion: 4/10 — Subtle

## 2\. Color Palette & Roles

*   **Quase Preto** (#0d0d0d) — Dark surface, primary background
*   **Branco** (#ffffff) — Light surface, card backgrounds
*   **Verde Brand** (#18E299) — Primary accent, CTAs and interactive elements
*   **Verde Claro** (#d4fae8) — Supporting palette color
*   **Cinza 700** (#333333) — Secondary text, borders, muted elements
*   **Cinza 500** (#666666) — Secondary text, borders, muted elements
*   **Cinza 200** (#e5e5e5) — Secondary text, borders, muted elements
*   **Verde Deep** (#0fa76e) — Success states, positive indicators

## 3\. Typography Rules

*   **Display / Hero:** Inter — Weight 700, tight tracking, used for headline impact
*   **Body:** Inter — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** Inter — 0.875rem, weight 500, slight letter-spacing
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

*   **Physics:** Ease-out curves, 200-300ms duration. Smooth and predictable.
*   **Entry animations:** Fade + translate-Y (16px → 0) over 420ms ease-out. Staggered cascades for lists: 80ms between items.
*   **Hover states:** Subtle color shift + shadow adjustment over 200ms.
*   **Page transitions:** Fade only (200ms).
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

Design a Mintlify-inspired documentation landing page. White canvas with Brand Green (#18E299) accent for CTAs and hover states. Atmospheric green-white gradient hero. Ultra-round corners: 16px containers, 24px featured, 9999px buttons. Subtle 5% opacity borders. Inter at 64px weight 600 with -1.28px letter-spacing. Geist Mono uppercase labels with 0.6px letter-spacing. Three weights: 400 body, 500 UI, 600 headings.

Last synced: 4/1/2026
