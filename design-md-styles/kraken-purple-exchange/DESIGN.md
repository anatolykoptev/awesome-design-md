# Design System: Kraken Purple Exchange

## 1\. Visual Theme & Atmosphere

Kraken-inspired crypto exchange landing page. Ideal for exchanges crypto, trading, plataformas financeiras, defi. AI-ready template.

*   Density: 3/10 — Airy
*   Variance: 3/10 — Restrained
*   Motion: 4/10 — Subtle

## 2\. Color Palette & Roles

*   **Kraken Purple** (#7132f5) — Accent color, emphasis elements
*   **Branco** (#ffffff) — Light surface, card backgrounds
*   **Near Black** (#101114) — Dark surface, primary background
*   **Cool Gray** (#686b82) — Secondary text, borders, muted elements
*   **Purple Dark** (#5741d8) — Deep contrast surface
*   **Silver Blue** (#9497a9) — Secondary accent
*   **Verde** (#149e61) — Success states, positive indicators
*   **Purple Subtle** (rgba(133,91,251,0.16)) — Accent color, emphasis elements

## 3\. Typography Rules

*   **Display / Hero:** system-ui — Weight 700, tight tracking, used for headline impact
*   **Body:** system-ui — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** system-ui — 0.875rem, weight 500, slight letter-spacing
*   **Monospace:** JetBrains Mono — Used for code, metadata, and technical values

Scale:

*   Hero: clamp(2.5rem, 5vw, 4rem)
*   H1: 2.25rem
*   H2: 1.5rem
*   Body: 1rem / 1.6
*   Small: 0.875rem

## 4\. Component Stylings

*   **Primary Button:** Generously rounded (1.5rem) shape. Accent color fill. Hover: 8% darken + subtle lift shadow. Active: -1px translate tactile press. Font weight 600. No outer glows.
*   **Secondary / Ghost Button:** Outline variant. 1.5px border in muted color. Text in primary color. Hover: subtle background fill.
*   **Cards:** Generously rounded (1.5rem) corners. Surface background. Subtle shadow (0 2px 12px rgba(0,0,0,0.06)). 1px border stroke.
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

Design a Kraken-inspired crypto exchange landing page. Kraken Purple (#7132f5) as commanding brand accent. White canvas with cool blue-gray neutral scale (#686b82, #9497a9). Brand font at 48px weight 700, letter-spacing -1px for display. Product font at 16px weight 400-600 for body/UI. 12px border-radius on all buttons — rounded but not pill. Whisper shadows (rgba(0,0,0,0.03) 0px 4px 24px). Purple subtle buttons (rgba(133,91,251,0.16) background). Green success badges (#149e61 at 16% opacity).

Last synced: 4/1/2026
