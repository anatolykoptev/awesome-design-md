# Design System: Democratized Fancy Animations

## 1\. Visual Theme & Atmosphere

Visually stunning landing page with democratized fancy animations using CSS and lightweight WebGL-inspired effects. Ideal for landing pages premium, portfolios criativos, lancamentos de produto tech, agencias digitais, experiencias imersivas, showcases de design. AI-ready template.

*   Density: 5/10 — Balanced
*   Variance: 4/10 — Moderate
*   Motion: 8/10 — Cinematic

## 2\. Color Palette & Roles

*   **Preto Profundo** (#050510) — Primary background surface
*   **Azul Cosmico** (#1a1a4e) — Accent highlight, links and focus states
*   **Branco Luminoso** (#F0F0FF) — Light surface, card backgrounds
*   **Roxo Shader** (#7B2FBE) — Accent color, emphasis elements
*   **Ciano Glow** (#00E5FF) — Extended palette, decorative use
*   **Rosa Plasma** (#FF4081) — Decorative accent, highlight elements
*   **Dourado Particula** (#FFD54F) — Premium accent, decorative highlights

## 3\. Typography Rules

*   **Display / Hero:** Space Grotesk — Weight 700, tight tracking, used for headline impact
*   **Accent:** Inter — Used for decorative or emphasis text
*   **Body:** Space Grotesk — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** Space Grotesk — 0.875rem, weight 500, slight letter-spacing
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

Design a visually stunning landing page with democratized fancy animations using CSS and lightweight WebGL-inspired effects. Create fluid distortion backgrounds using CSS filters and SVG turbulence (feTurbulence + feDisplacementMap). Volumetric light effects with radial-gradient layers and animation. Chromatic aberration on hover using text-shadow with RGB offset. Particle-like floating elements using CSS @keyframes with random delays and positions. Blob tracking effect — a soft gradient circle that follows mouse position via CSS custom properties updated by minimal JS (mousemove event). Section transitions with smooth morphing shapes (clip-path animations). Parallax depth layers reacting to cursor position. Use dark cosmic background (#050510) with glowing accent colors (cyan #00E5FF, purple #7B2FBE, pink #FF4081). All animations should feel fluid at 60fps with will-change and transform: translate3d for GPU acceleration. Story-driven motion — each scroll reveals content with purposeful choreographed animation.

Last synced: 4/1/2026
