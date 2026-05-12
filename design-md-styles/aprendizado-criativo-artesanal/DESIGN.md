# Design System: Aprendizado Criativo Artesanal

## 1\. Visual Theme & Atmosphere

Creative and engaging hand-drawn landing page for an online art and creativity course platform. Ideal for landing pages, modern websites. AI-ready template. Aprendizado Criativo Artesanal style represents a modern trend in UI/UX web design focused on handdrawn.

*   Density: 5/10 — Balanced
*   Variance: 8/10 — Expressive
*   Motion: 4/10 — Subtle

## 2\. Color Palette & Roles

*   **Verde Menta** (#98FB98) — Primary surface or dominant color
*   **Roxo Lavanda** (#E6E6FA) — Accent color, emphasis elements
*   **Amarelo Pastel** (#FFFACD) — Warning states, attention indicators
*   **Branco** (#FFFFFF) — Light surface, card backgrounds
*   **Azul Céu** (#87CEEB) — Secondary accent
*   **Rosa Pêssego** (#FFDAB9) — Decorative accent, highlight elements
*   **Marrom Claro** (#D2B48C) — Extended palette, decorative use
*   **Cinza Lápis** (#A9A9A9) — Secondary text, borders, muted elements

## 3\. Typography Rules

*   **Display / Hero:** Gochi Hand — Weight 700, tight tracking, used for headline impact
*   **Body:** Gochi Hand — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** Gochi Hand — 0.875rem, weight 500, slight letter-spacing
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

Design a creative and engaging hand-drawn landing page for an online art and creativity course platform. Use: hand-drawn art element illustrations (brushes, paints), artistic handwritten-style typography, canvas and watercolor textures, brushstroke-effect borders, "sketch" animation hover micro-interactions, "blank canvas" section transitions, mint green and lavender accents, inspiring and expressive feel.

Last synced: 4/1/2026
