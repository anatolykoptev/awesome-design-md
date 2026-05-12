# Design System: Aura Premium WebGL & Iconify

## 1\. Visual Theme & Atmosphere

Premium dark-themed landing page with advanced animations and interactions. Ideal for portfolios de luxo, estúdios de arquitetura, marcas premium, móveis de alto padrão, wellness premium, creative agencies. AI-ready template.

*   Density: 5/10 — Balanced
*   Variance: 4/10 — Moderate
*   Motion: 6/10 — Expressive

## 2\. Color Palette & Roles

*   **Preto Profundo** (#0A0A0A) — Primary background surface
*   **Branco Puro** (#FFFFFF) — Light surface, card backgrounds
*   **Cinza Escuro** (#1A1A2E) — Dark surface, primary background
*   **Azul Elétrico** (#3B82F6) — Secondary accent
*   **Violeta Neon** (#8B5CF6) — Accent color, emphasis elements
*   **Âmbar Quente** (#F59E0B) — Extended palette, decorative use
*   **Esmeralda** (#10B981) — Extended palette, decorative use
*   **Rosa Vibrante** (#EC4899) — Decorative accent, highlight elements

## 3\. Typography Rules

*   **Display / Hero:** Inter — Weight 700, tight tracking, used for headline impact
*   **Body:** Inter — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** Inter — 0.875rem, weight 500, slight letter-spacing
*   **Monospace:** JetBrains Mono — Used for code, metadata, and technical values

Scale:

*   Hero: clamp(2.5rem, 5vw, 4rem)
*   H1: 2.25rem
*   H2: 1.5rem
*   Body: 1rem / 1.6
*   Small: 0.875rem

## 4\. Component Stylings

*   **Primary Button:** Pill-shaped (9999px) shape. Accent color fill. Hover: 8% darken + subtle lift shadow. Active: -1px translate tactile press. Font weight 600. No outer glows.
*   **Secondary / Ghost Button:** Outline variant. 1.5px border in muted color. Text in primary color. Hover: subtle background fill.
*   **Cards:** Pill-shaped (9999px) corners. Surface background. Subtle shadow (0 2px 12px rgba(0,0,0,0.06)). 1px border stroke.
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
*   **Entry animations:** Fade + translate-Y (16px → 0) over 480ms ease-out. Staggered cascades for lists: 100ms between items.
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

Design a premium dark-themed landing page with advanced animations and interactions. Use Iconify Solar Duotone Bold icons throughout. For the site logo, use Iconify Solar Linear plus lettermark with tracking-tighter text. Use Iconify Simple Icons for company logos (Nasa, SpaceX, Uber, Visa, Grab, Bose, Discover, DJI, Nikon, Craftsman, Sony) at 64x64 instead of text logos. Use \<iconify-icon> instead of full SVG code. For avatars and testimonials, use headshot photos instead of placeholder letters. Add vertical container-size lines as decorative elements. Add 01 02 03 number details on sections. Add a 1px border beam animation around pill-shaped buttons on hover. Add vertical text clip slide down animation letter by letter. Add sonar animation and decorations. Add a subtle flashlight effect on hover/mouse position to both background and border of cards. Animate marquee in infinite loop with alpha mask slowly. Add 4-column clip animate sliding down for all images using WebGL. Full-screen images sliced into 4 vertical columns with staggered scroll speeds and motion blur trails that snap to alignment when scroll stops.

Last synced: 4/1/2026
