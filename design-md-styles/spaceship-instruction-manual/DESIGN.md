# Design System: Spaceship Instruction Manual

## 1\. Visual Theme & Atmosphere

Landing page that looks like a spaceship instruction manual or engineering blueprint. Ideal for produtos de hardware, startups deep-tech, apis e ferramentas dev, plataformas de engenharia, documentacao tecnica, cybersecurity. AI-ready template.

*   Density: 7/10 — Compact
*   Variance: 4/10 — Moderate
*   Motion: 1/10 — Static

## 2\. Color Palette & Roles

*   **Azul Blueprint** (#0A1628) — Accent highlight, links and focus states
*   **Branco Tecnico** (#E8ECF1) — Light surface, card backgrounds
*   **Ciano Linha** (#00D4FF) — Supporting palette color
*   **Cinza Anotacao** (#6B7B8D) — Secondary text, borders, muted elements
*   **Amarelo Alerta** (#FFB800) — Error states, destructive actions
*   **Verde Status** (#00E676) — Success states, positive indicators
*   **Vermelho Critico** (#FF3D00) — Error states, destructive actions

## 3\. Typography Rules

*   **Display / Hero:** JetBrains Mono — Weight 700, tight tracking, used for headline impact
*   **Accent:** Fira Code — Used for decorative or emphasis text
*   **Body:** JetBrains Mono — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** JetBrains Mono — 0.875rem, weight 500, slight letter-spacing
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

*   Minimal motion design. Hover states use color transitions only (150ms).
*   No entry animations. No page transitions. Instant, utilitarian feedback.
*   Performance: No animation overhead. Static-first approach.

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

Design a landing page that looks like a spaceship instruction manual or engineering blueprint. Use MONOSPACE fonts exclusively (JetBrains Mono, Fira Code, or Space Mono) for all text to convey technical rigor. Dark blueprint background (#0A1628) with cyan (#00D4FF) thin connector lines (callouts) linking data points to visual elements using SVG paths with arrowheads. Small technical labels in UPPERCASE with wide letter-spacing (0.2em) scattered as decorative annotations — even if purely ornamental. Low-fi schematic illustrations mimicking exploded-view technical drawings using CSS borders, lines, and geometric shapes. Visible grid lines in the background (subtle, 5% opacity). Section numbering like a technical manual (01. OVERVIEW, 02. SPECIFICATIONS). Dashed thin borders on containers. Status indicators with colored dots (green=active, yellow=warning, red=critical). The overall aesthetic should scream 'deep engineering credibility'.

Last synced: 4/1/2026
