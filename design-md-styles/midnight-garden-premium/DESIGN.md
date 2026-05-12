# Design System: Midnight Garden Premium

## 1\. Visual Theme & Atmosphere

Create an elegant, premium UI with a nocturnal botanical garden atmosphere. Ideal for marcas sustentáveis premium, jardins botânicos, cosméticos naturais, wellness de luxo, resorts ecológicos. AI-ready template.

*   Density: 5/10 — Balanced
*   Variance: 8/10 — Expressive
*   Motion: 4/10 — Subtle

## 2\. Color Palette & Roles

*   **Midnight Mirage** (#001F3F) — Dark surface, primary background
*   **Mantis Green** (#74C365) — Secondary surface or text color
*   **Praxeti White** (#F6F7ED) — Light surface, card backgrounds
*   **Spring Lime** (#DBE64C) — Extended palette, decorative use
*   **Book Green** (#00804C) — Success states, positive indicators
*   **Nuit Blanche Blue** (#1E488F) — Secondary accent

## 3\. Typography Rules

*   **Display / Hero:** DM Serif Display — Weight 700, tight tracking, used for headline impact
*   **Accent:** DM Sans — Used for decorative or emphasis text
*   **Body:** DM Serif Display — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** DM Serif Display — 0.875rem, weight 500, slight letter-spacing
*   **Monospace:** JetBrains Mono — Used for code, metadata, and technical values

Scale:

*   Hero: clamp(2.5rem, 5vw, 4rem)
*   H1: 2.25rem
*   H2: 1.5rem
*   Body: 1rem / 1.6
*   Small: 0.875rem

## 4\. Component Stylings

*   **Primary Button:** Rounded (10px) shape. Accent color fill. Hover: 8% darken + subtle lift shadow. Active: -1px translate tactile press. Font weight 600. No outer glows.
*   **Secondary / Ghost Button:** Outline variant. 1.5px border in muted color. Text in primary color. Hover: subtle background fill.
*   **Cards:** Rounded (10px) corners. Surface background. Subtle shadow (0 2px 12px rgba(0,0,0,0.06)). 1px border stroke.
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

Create an elegant, premium UI with a nocturnal botanical garden atmosphere. Use deep midnight blue (#001F3F) as the dominant background with vivid mantis green (#74C365) as the primary accent. Praxeti white (#F6F7ED) for text and surfaces. Incorporate botanical SVG line art, translucent card panels, crisp high-contrast typography, and subtle green glow effects on hover. The feel should be lush, sophisticated, and immersive — like walking through a moonlit garden.

Last synced: 4/1/2026
