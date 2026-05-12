# Design System: Culinária Afetiva Brasileira

## 1\. Visual Theme & Atmosphere

Warm and authentic landing page for a homemade and affective recipe sharing platform, inspired by Brazilian vernacular culture. Ideal for landing pages, saas. AI-ready template. Culinária Afetiva Brasileira style represents a modern trend in UI/UX web design focused on general.

*   Density: 5/10 — Balanced
*   Variance: 4/10 — Moderate
*   Motion: 8/10 — Cinematic

## 2\. Color Palette & Roles

*   **Amarelo Milho** (#FFD700) — Warning states, attention indicators
*   **Verde Erva** (#6B8E23) — Secondary surface or text color
*   **Laranja Cenoura** (#ED7014) — Warm accent, call-to-action secondary
*   **Branco** (#FFFFFF) — Light surface, card backgrounds
*   **Vermelho Tomate** (#FF6347) — Error states, destructive actions
*   **Azul Céu** (#87CEEB) — Secondary accent
*   **Marrom Terra** (#8B4513) — Extended palette, decorative use
*   **Cinza Claro** (#F0F0F0) — Secondary text, borders, muted elements

## 3\. Typography Rules

*   **Display / Hero:** Caveat — Weight 700, tight tracking, used for headline impact
*   **Body:** Caveat — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** Caveat — 0.875rem, weight 500, slight letter-spacing
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

Design a warm and authentic landing page for a homemade and affective recipe sharing platform, inspired by Brazilian vernacular culture. Use: chita tablecloth and old kitchen utensil textures, handwritten/notebook recipe-style typography, photographs of homemade dishes focusing on coziness, visual "steam" or "aroma" hover micro-interactions, smooth "flipping through a cookbook" section transitions, corn yellow and herb green accents, community and friendly feel.

Last synced: 4/1/2026
