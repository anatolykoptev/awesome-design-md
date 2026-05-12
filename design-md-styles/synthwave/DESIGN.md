# Design System: Synthwave

## 1\. Visual Theme & Atmosphere

Synthwave landing page with dramatic neon sunset gradients and retro-futuristic 80s aesthetics. Ideal for capas de álbuns, promoções de marca, visuais neon, eventos de música eletrônica. AI-ready template.

*   Density: 5/10 — Balanced
*   Variance: 7/10 — Dynamic
*   Motion: 8/10 — Cinematic

## 2\. Color Palette & Roles

*   **Sunset Orange** (#FF6B35) — Warm accent, call-to-action secondary
*   **Neon Pink** (#FF1493) — Primary text color
*   **Deep Purple** (#2D1B69) — Accent color, emphasis elements
*   **Horizon Blue** (#1B1464) — Accent highlight, links and focus states
*   **Neon Cyan** (#00FFFF) — Secondary accent
*   **Chrome Silver** (#C0C0C0) — Extended palette, decorative use
*   **Hot Magenta** (#FF00FF) — Decorative accent, highlight elements
*   **Dark Navy** (#0A0A2E) — Deep contrast surface

## 3\. Typography Rules

*   **Display / Hero:** Orbitron — Weight 700, tight tracking, used for headline impact
*   **Body:** Orbitron — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** Orbitron — 0.875rem, weight 500, slight letter-spacing
*   **Monospace:** JetBrains Mono — Used for code, metadata, and technical values

Scale:

*   Hero: clamp(2.5rem, 5vw, 4rem)
*   H1: 2.25rem
*   H2: 1.5rem
*   Body: 1rem / 1.6
*   Small: 0.875rem

## 4\. Component Stylings

*   **Primary Button:** Subtly rounded (0.5rem) shape. Accent color fill. Hover: 8% darken + subtle lift shadow. Active: -1px translate tactile press. Font weight 600. No outer glows.
*   **Secondary / Ghost Button:** Outline variant. 1.5px border in muted color. Text in primary color. Hover: subtle background fill.
*   **Cards:** Subtly rounded (0.5rem) corners. Surface background. Subtle shadow (0 2px 12px rgba(0,0,0,0.06)). 1px border stroke.
*   **Inputs:** Label above input. 1px border stroke. Focus ring: 2px accent color offset 2px. Error text below in semantic red. No floating labels.
*   **Navigation:** Primary surface background. Active item: accent color indicator. Font weight 500 when active.
*   **Skeletons:** Shimmer animation matching component dimensions. No circular spinners.
*   **Empty States:** Icon-based composition with descriptive text and action button.

## 5\. Layout Principles

*   **Grid:** CSS Grid primary. Max-width containment: 1280px centered with 1.5rem side padding.
*   **Spacing rhythm:** Balanced. Base unit: 0.5rem (8px).
*   **Section vertical gaps:** clamp(4rem, 8vw, 8rem).
*   **Hero layout:** Asymmetric composition.
*   **Feature sections:** Asymmetric grid with varied card sizes. No 3-equal-columns.
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
*   No pure white (#FFFFFF) backgrounds — use off-white or dark surfaces
*   No oversaturated accent colors (saturation cap: 80%)
*   No 3-column equal-width feature layouts — use zig-zag or asymmetric grid
*   No `h-screen` — use `min-h-[100dvh]`
*   No AI copywriting clichés: "Elevate", "Seamless", "Unleash", "Next-Gen"
*   No broken external image links — use picsum.photos or inline SVG
*   No generic lorem ipsum in demos

## AI Prompt

Design a synthwave landing page with dramatic neon sunset gradients and retro-futuristic 80s aesthetics. Use sunset orange, neon pink, deep purple, horizon blue. Apply neon perspective grid floor, sunset gradient sky, neon monoline borders with glow, palm tree SVG silhouettes, chrome text effects, retro scanlines. Typography should be bold and futuristic. Outrun arcade atmosphere.

Last synced: 4/1/2026
