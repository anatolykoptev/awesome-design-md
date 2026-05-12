# Design System: Kawaii

## 1\. Visual Theme & Atmosphere

Kawaii landing page with soft pastel colors and adorable rounded aesthetics. Ideal for embalagens de brinquedos, vestuário, branding de personagens, gráficos de redes sociais. AI-ready template.

*   Density: 5/10 — Balanced
*   Variance: 7/10 — Dynamic
*   Motion: 6/10 — Expressive

## 2\. Color Palette & Roles

*   **Pastel Pink** (#FFB6C1) — Primary text color
*   **Pastel Blue** (#ADD8E6) — Accent highlight, links and focus states
*   **Pastel Yellow** (#FFFACD) — Warning states, attention indicators
*   **Soft White** (#FFF5F5) — Light surface, card backgrounds
*   **Pastel Mint** (#B2F2BB) — Extended palette, decorative use
*   **Pastel Lavender** (#D8B4FE) — Extended palette, decorative use
*   **Pastel Peach** (#FFDAB9) — Extended palette, decorative use
*   **Soft Grey** (#E8E8E8) — Secondary text, borders, muted elements

## 3\. Typography Rules

*   **Display / Hero:** Quicksand — Weight 700, tight tracking, used for headline impact
*   **Body:** Quicksand — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** Quicksand — 0.875rem, weight 500, slight letter-spacing
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
*   **Hero layout:** Asymmetric composition.
*   **Feature sections:** Asymmetric grid with varied card sizes. No 3-equal-columns.
*   **Mobile collapse:** All multi-column layouts collapse below 768px. No horizontal overflow.
*   **z-index contract:** base (0) / sticky-nav (100) / overlay (200) / modal (300) / toast (500).

## 6\. Motion & Interaction

*   **Physics:** Spring — stiffness 120, damping 20. Confident, weighted transitions.
*   **Entry animations:** Fade + translate-Y (16px → 0) over 480ms ease-out. Staggered cascades for lists: 100ms between items.
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

Design a kawaii landing page with soft pastel colors and adorable rounded aesthetics. Use pastel pink, blue, yellow, soft white. Apply very rounded shapes (24-32px), bouncy overshoot animations, kawaii face SVG decorations (dot eyes, tiny mouth), sparkle/star decorations, cloud-shaped dividers, soft pastel gradients. Typography should be rounded and friendly (Nunito, Quicksand). Adorable, bubbly, Japanese cute culture atmosphere.

Last synced: 4/1/2026
