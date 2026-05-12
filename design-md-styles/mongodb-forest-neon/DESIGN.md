# Design System: MongoDB Forest Neon

## 1\. Visual Theme & Atmosphere

MongoDB-inspired forest-dark landing page. Ideal for databases, infraestrutura de dados, plataformas developer, apis de dados. AI-ready template.

*   Density: 5/10 — Balanced
*   Variance: 4/10 — Moderate
*   Motion: 4/10 — Subtle

## 2\. Color Palette & Roles

*   **Forest Black** (#001e2b) — Dark surface, primary background
*   **Verde MongoDB** (#00ed64) — Secondary surface or text color
*   **Verde Escuro** (#00684a) — Dark surface, primary background
*   **Branco** (#ffffff) — Light surface, card backgrounds
*   **Azul Ação** (#006cfa) — Secondary accent
*   **Azul Hover** (#3860be) — Secondary accent
*   **Cinza Teal** (#b8c4c2) — Secondary text, borders, muted elements
*   **Cinza Cool** (#5c6c75) — Secondary text, borders, muted elements

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

*   **Physics:** Ease-out curves, 200-300ms duration. Smooth and predictable.
*   **Entry animations:** Fade + translate-Y (16px → 0) over 420ms ease-out. Staggered cascades for lists: 80ms between items.
*   **Hover states:** Subtle color shift + shadow adjustment over 200ms.
*   **Page transitions:** Fade only (200ms).
*   **Performance:** Only transform and opacity animated. No layout-triggering properties.

## 7\. Anti-Patterns (Banned)

*   No emojis in UI — use icon system only (Lucide, Heroicons)
*   No pure white (#FFFFFF) backgrounds — use off-white or dark surfaces
*   No oversaturated accent colors (saturation cap: 80%)
*   No 3-column equal-width feature layouts — use zig-zag or asymmetric grid
*   No `h-screen` — use `min-h-[100dvh]`
*   No AI copywriting clichés: "Elevate", "Seamless", "Unleash", "Next-Gen"
*   No broken external image links — use picsum.photos or inline SVG
*   No generic lorem ipsum in demos

## AI Prompt

Design a MongoDB-inspired forest-dark landing page. Teal-black canvas (#001e2b) — forest-dark, not space-dark. Neon MongoDB Green (#00ed64) as singular electric accent for highlights and underlines. Serif display font at 96px weight 400 for hero headlines. Source Code Pro uppercase labels with 1px-3px letter-spacing. Teal-tinted shadows (rgba(0,30,43,0.12) 0px 26px 44px). Dual-mode: dark teal hero + white content sections. Pill buttons (100px radius) with #00684a green borders. Body text at weight 300 (light).

Last synced: 4/1/2026
