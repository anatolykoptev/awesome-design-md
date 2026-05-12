# Design System: Grade School Color Palette

## 1\. Visual Theme & Atmosphere

Landing page using grade school primary colors — the kind you remember from crayons and traffic signs. Ideal for startups consumer, apps educacionais, ecommerce jovem, plataformas de comunidade, marketing de produto, food delivery. AI-ready template.

*   Density: 5/10 — Balanced
*   Variance: 7/10 — Dynamic
*   Motion: 4/10 — Subtle

## 2\. Color Palette & Roles

*   **Laranja Dominante** (#FF6B00) — Warm accent, call-to-action secondary
*   **Vermelho Vivo** (#E53935) — Error states, destructive actions
*   **Azul Puro** (#1E88E5) — Accent highlight, links and focus states
*   **Amarelo Vibrante** (#FDD835) — Warning states, attention indicators
*   **Verde Folha** (#43A047) — Success states, positive indicators
*   **Laranja Escuro** (#E65100) — Deep contrast surface
*   **Creme Quente** (#FFF8E1) — Extended palette, decorative use
*   **Cinza Suave** (#F5F5F5) — Secondary text, borders, muted elements

## 3\. Typography Rules

*   **Display / Hero:** Nunito — Weight 700, tight tracking, used for headline impact
*   **Accent:** Poppins — Used for decorative or emphasis text
*   **Body:** Nunito — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** Nunito — 0.875rem, weight 500, slight letter-spacing
*   **Monospace:** JetBrains Mono — Used for code, metadata, and technical values

Scale:

*   Hero: clamp(2.5rem, 5vw, 4rem)
*   H1: 2.25rem
*   H2: 1.5rem
*   Body: 1rem / 1.6
*   Small: 0.875rem

## 4\. Component Stylings

*   **Primary Button:** Rounded (16px) shape. Accent color fill. Hover: 8% darken + subtle lift shadow. Active: -1px translate tactile press. Font weight 600. No outer glows.
*   **Secondary / Ghost Button:** Outline variant. 1.5px border in muted color. Text in primary color. Hover: subtle background fill.
*   **Cards:** Rounded (16px) corners. Surface background. Subtle shadow (0 2px 12px rgba(0,0,0,0.06)). 1px border stroke.
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

Design a landing page using grade school primary colors — the kind you remember from crayons and traffic signs. ORANGE is the DOMINANT color replacing traditional corporate blue as the primary action color. Use pure red #E53935, blue #1E88E5, yellow #FDD835, green #43A047 as supporting colors. Apply modern tints and shades to prevent childish appearance — subtle saturation adjustments, soft colored shadows. Generous border-radius (12-20px). Bold friendly typography (rounded sans-serif like Nunito or Poppins). Large solid color blocks as section backgrounds. Warm cream #FFF8E1 as base. Colored box-shadows matching element colors at 20% opacity. Hover states increase saturation. The overall feel should be warm, energetic, and action-oriented — NOT childish.

Last synced: 4/1/2026
