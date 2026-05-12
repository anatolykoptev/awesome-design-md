# Design System: Architectural Portfolio Cinematic

## 1\. Visual Theme & Atmosphere

High-end cinematic 2-page architectural portfolio. Ideal for portfolios de arquitetura, estúdios de design, creative agencies, portfolios pessoais premium, showcases de projetos tech. AI-ready template.

*   Density: 3/10 — Airy
*   Variance: 3/10 — Restrained
*   Motion: 8/10 — Cinematic

## 2\. Color Palette & Roles

*   **Preto Fundo** (#000000) — Primary background surface
*   **Branco Texto** (#FFFFFF) — Light surface, card backgrounds
*   **20 bordas** (rgba(255,255,255,0.2)) — Supporting palette color
*   **5 cards** (rgba(255,255,255,0.05)) — Extended palette, decorative use
*   **10 hover** (rgba(255,255,255,0.1)) — Extended palette, decorative use
*   **60 texto secundário** (rgba(255,255,255,0.6)) — Primary text color
*   **40 labels** (rgba(255,255,255,0.4)) — Extended palette, decorative use

## 3\. Typography Rules

*   **Display / Hero:** Space Grotesk — Weight 700, tight tracking, used for headline impact
*   **Accent:** Orbitron — Used for decorative or emphasis text
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
*   **Entry animations:** Fade + translate-Y (16px → 0) over 540ms ease-out. Staggered cascades for lists: 120ms between items.
*   **Hover states:** Scale(1.03) + shadow lift over 200ms.
*   **Page transitions:** Fade + slide (300ms).
*   **Performance:** Only transform and opacity animated. No layout-triggering properties.

## 7\. Anti-Patterns (Banned)

*   No emojis in UI — use icon system only (Lucide, Heroicons)
*   No decorative gradients — flat color only
*   No shadows heavier than 0 2px 8px rgba(0,0,0,0.08)
*   No pure white (#FFFFFF) backgrounds — use off-white or dark surfaces
*   No oversaturated accent colors (saturation cap: 80%)
*   No 3-column equal-width feature layouts — use zig-zag or asymmetric grid
*   No `h-screen` — use `min-h-[100dvh]`
*   No AI copywriting clichés: "Elevate", "Seamless", "Unleash", "Next-Gen"
*   No broken external image links — use picsum.photos or inline SVG
*   No generic lorem ipsum in demos

## AI Prompt

Build a high-end cinematic 2-page architectural portfolio. Aesthetic: minimalist, dark-themed (black background #000000, white text #FFFFFF), sophisticated typographic hierarchy. Fonts: Orbitron for display headings, Space Grotesk for body text, JetBrains Mono for technical/mono elements. Custom selection color (white bg, black text). Page 1 Hero: Full-screen looping background video of futuristic architecture (use stock video URL). Video: muted, playsInline, loop, preload auto. Overlays: radial vignette on desktop (70% transparent center to 70% black edges), bottom-fade gradient on mobile. Top nav: right-aligned 1/01 counter with progress line and Next Project button in mono font. Main content: large title 'VIKTOR-O // MODERN ARCHITECT' (Orbitron uppercase tracking-tighter), description in Space Grotesk light with max-w-450px. Right column: technical specs list (Stack, Logic, Uptime, Scale) with labels and values separated by thin border-white/20. Bottom: glass-morphism card (bg-white/5 backdrop-blur-xl) with project title 'VK-01: React Engine' and View Project button. Row of pill-shaped tags (TS/JS, V1, Full-Stack, Cloud-Ready) at bottom right. Page 2 Project: Back Home button with arrow icon. Massive display title 'PROJECT ENGINE' (Orbitron leading-0.85 uppercase). Right-aligned description about flagship React engine with Read More link. Two structured info blocks 01 CORE ARCHITECTURE and 02 PERFORMANCE METRICS with uppercase mono subtext. Navigation arrows in circular borders and meta-info block. Implement page transitions with opacity/y-offset animations. On mobile: video occupies top half h-50vh with smooth gradient to content below.

Last synced: 4/1/2026
