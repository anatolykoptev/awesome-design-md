# Design System: Memphis

## 1\. Visual Theme & Atmosphere

Memphis-style landing page with vibrant bold colors, geometric shapes (triangles, circles, squiggles), postmodern 80s aesthetic. Ideal for branding retro, peças editoriais, embalagens funky, campanhas jovens. AI-ready template.

*   Density: 5/10 — Balanced
*   Variance: 7/10 — Dynamic
*   Motion: 6/10 — Expressive

## 2\. Color Palette & Roles

*   **Hot Pink** (#FF1493) — Primary text color
*   **Electric Blue** (#0066FF) — Accent highlight, links and focus states
*   **Bright Yellow** (#FFD700) — Warning states, attention indicators
*   **Vivid Red** (#FF3333) — Error states, destructive actions
*   **Mint Green** (#00E5A0) — Success states, positive indicators
*   **Coral** (#FF7F50) — Extended palette, decorative use
*   **Purple** (#9B59B6) — Accent color, emphasis elements
*   **Turquoise** (#1ABC9C) — Extended palette, decorative use

## 3\. Typography Rules

*   **Display / Hero:** Poppins — Weight 700, tight tracking, used for headline impact
*   **Body:** Poppins — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** Poppins — 0.875rem, weight 500, slight letter-spacing
*   **Monospace:** JetBrains Mono — Used for code, metadata, and technical values

Scale:

*   Hero: clamp(2.5rem, 5vw, 4rem)
*   H1: 2.25rem
*   H2: 1.5rem
*   Body: 1rem / 1.6
*   Small: 0.875rem

## 4\. Component Stylings

*   **Primary Button:** Sharp edges (0px) shape. Accent color fill. Hover: 8% darken + subtle lift shadow. Active: -1px translate tactile press. Font weight 600. No outer glows.
*   **Secondary / Ghost Button:** Outline variant. 1.5px border in muted color. Text in primary color. Hover: subtle background fill.
*   **Cards:** Sharp edges (0px) corners. Surface background. Subtle shadow (0 2px 12px rgba(0,0,0,0.06)). 1px border stroke.
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

Design a Memphis-style landing page with vibrant bold colors, geometric shapes (triangles, circles, squiggles), postmodern 80s aesthetic. Use hot pink, electric blue, bright yellow. Apply scattered geometric decorations, zigzag and dotted pattern backgrounds, playful rotation on elements, bold sans-serif typography. Energetic, fun and anti-minimalist.

Last synced: 4/1/2026
