# Design System: Bento Grid Tech Minimalist

## 1\. Visual Theme & Atmosphere

Bento grid landing page, apple style aesthetic, modular layout, rounded cards, clean minimalist tech, organized grid system. Ideal for landing pages, modern websites. AI-ready template. Bento Grid Tech Minimalist style represents a modern trend in UI/UX web design focused on technical.

*   Density: 3/10 — Airy
*   Variance: 2/10 — Structured
*   Motion: 4/10 — Subtle

## 2\. Color Palette & Roles

*   **Background** (#FFFFFF) — Primary background surface
*   **Text** (#1D1D1F) — Primary text color
*   **Accent** (#9562E3) — Primary accent, CTAs and interactive elements
*   **Light Grey** (#F5F5F7) — Secondary text, borders, muted elements
*   **Dark Grey** (#86868b) — Deep contrast surface
*   **Soft Blue** (#0071e3) — Secondary accent

## 3\. Typography Rules

*   **Display / Hero:** Segoe UI — Weight 700, tight tracking, used for headline impact
*   **Accent:** -apple-system — Used for decorative or emphasis text
*   **Body:** Segoe UI — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** Segoe UI — 0.875rem, weight 500, slight letter-spacing
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

bento grid landing page, apple style aesthetic, modular layout, rounded cards, clean minimalist tech, organized grid system.

Last synced: 4/1/2026
