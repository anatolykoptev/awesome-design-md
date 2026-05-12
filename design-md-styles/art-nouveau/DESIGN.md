# Design System: Art Nouveau

## 1\. Visual Theme & Atmosphere

Design an Art Nouveau landing page with flowing organic lines and nature-inspired motifs. Ideal for design de pôsteres, capas de livros, branding orgânico e romântico, ilustração editorial. AI-ready template.

*   Density: 5/10 — Balanced
*   Variance: 8/10 — Expressive
*   Motion: 8/10 — Cinematic

## 2\. Color Palette & Roles

*   **Moss Green** (#4A6741) — Primary surface or dominant color
*   **Warm Gold** (#B8860B) — Premium accent, decorative highlights
*   **Cream** (#FFF8DC) — Light surface, card backgrounds
*   **Deep Plum** (#4A1942) — Supporting palette color
*   **Terracotta** (#C67A4B) — Extended palette, decorative use
*   **Sky Blue** (#87CEEB) — Secondary accent
*   **Dusty Rose** (#C9A0A0) — Extended palette, decorative use
*   **Olive** (#6B7B3A) — Extended palette, decorative use

## 3\. Typography Rules

*   **Display / Hero:** Cormorant Garamond — Weight 700, tight tracking, used for headline impact
*   **Body:** Cormorant Garamond — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** Cormorant Garamond — 0.875rem, weight 500, slight letter-spacing
*   **Monospace:** JetBrains Mono — Used for code, metadata, and technical values

Scale:

*   Hero: clamp(2.5rem, 5vw, 4rem)
*   H1: 2.25rem
*   H2: 1.5rem
*   Body: 1rem / 1.6
*   Small: 0.875rem

## 4\. Component Stylings

*   **Primary Button:** Rounded (organic/variable font-family: 'Cormorant Garamond') shape. Accent color fill. Hover: 8% darken + subtle lift shadow. Active: -1px translate tactile press. Font weight 600. No outer glows.
*   **Secondary / Ghost Button:** Outline variant. 1.5px border in muted color. Text in primary color. Hover: subtle background fill.
*   **Cards:** Rounded (organic/variable font-family: 'Cormorant Garamond') corners. Surface background. Subtle shadow (0 2px 12px rgba(0,0,0,0.06)). 1px border stroke.
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
*   No pure black (#000000) — use off-black or charcoal variants
*   No oversaturated accent colors (saturation cap: 80%)
*   No 3-column equal-width feature layouts — use zig-zag or asymmetric grid
*   No `h-screen` — use `min-h-[100dvh]`
*   No AI copywriting clichés: "Elevate", "Seamless", "Unleash", "Next-Gen"
*   No broken external image links — use picsum.photos or inline SVG
*   No generic lorem ipsum in demos

## AI Prompt

Design an Art Nouveau landing page with flowing organic lines and nature-inspired motifs. Use moss green, warm gold, cream, deep plum. Apply flowing SVG whiplash curve borders, floral corner decorations, nature-inspired dividers, rounded flowing typography. Illustration and typography should merge seamlessly. Romantic, handmade, deeply nature-inspired atmosphere.

Last synced: 4/1/2026
