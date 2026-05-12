# Design System: SaaS Signature Gradient

## 1\. Visual Theme & Atmosphere

Design the quintessential SaaS/AI startup landing page with THE signature tech gradient. Ideal for startups saas, ai tools, plataformas de desenvolvedores, landing pages tech, produtos b2b modernos, apis e sdks. AI-ready template.

*   Density: 5/10 — Balanced
*   Variance: 4/10 — Moderate
*   Motion: 8/10 — Cinematic

## 2\. Color Palette & Roles

*   **Roxo Base** (#6C3AED) — Primary background surface
*   **Azul Profundo** (#2563EB) — Primary background surface
*   **Fundo Escuro** (#0B0F1A) — Primary background surface
*   **Ciano Destaque** (#06B6D4) — Primary accent, CTAs and interactive elements
*   **Verde-Agua Teal** (#14B8A6) — Success states, positive indicators
*   **Branco Texto** (#F1F5F9) — Secondary surface
*   **Roxo Claro** (#A78BFA) — Accent color, emphasis elements
*   **Azul Claro** (#60A5FA) — Secondary accent

## 3\. Typography Rules

*   **Display / Hero:** Inter — Weight 700, tight tracking, used for headline impact
*   **Accent:** Plus Jakarta Sans — Used for decorative or emphasis text
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
*   No pure white (#FFFFFF) backgrounds — use off-white or dark surfaces
*   No oversaturated accent colors (saturation cap: 80%)
*   No 3-column equal-width feature layouts — use zig-zag or asymmetric grid
*   No `h-screen` — use `min-h-[100dvh]`
*   No AI copywriting clichés: "Elevate", "Seamless", "Unleash", "Next-Gen"
*   No broken external image links — use picsum.photos or inline SVG
*   No generic lorem ipsum in demos

## AI Prompt

Design the quintessential SaaS/AI startup landing page with THE signature tech gradient. Primary gradient flows from purple (#6C3AED) to blue (#2563EB) with mandatory cyan (#06B6D4) and teal (#14B8A6) accent highlights. Dark background (#0B0F1A). Create floating ORBS — soft 3D spheres using radial-gradient with blur (filter: blur(60-100px)) that drift slowly with CSS @keyframes animation. Mesh gradient BLOBS using multiple overlapping radial-gradients with different colors at varying positions. These orbs/blobs should lose opacity at edges (mask-image: radial-gradient(circle, black 40%, transparent 70%)). Apply subtle NOISE TEXTURE overlay using SVG feTurbulence at 3-5% opacity for a frosted/grainy feel. Glassmorphism cards with backdrop-filter: blur(20px) and background: rgba(255,255,255,0.05). Simulated NEON GLOW on key elements: text-shadow: 0 0 20px rgba(purple, 0.5) and box-shadow: 0 0 30px rgba(cyan, 0.3). VISUAL RHYME — repeat the same curved shapes and gradient family consistently across logo area, buttons, card corners, and decorative elements for absolute cohesion. Typography: clean geometric sans-serif (Inter or Plus Jakarta Sans).

Last synced: 4/1/2026
