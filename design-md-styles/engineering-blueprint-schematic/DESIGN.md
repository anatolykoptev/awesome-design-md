# Design System: Engineering Blueprint Schematic

## 1\. Visual Theme & Atmosphere

Engineering landing page, blueprint style, schematic design, technical precision, dark blue background, cyan lines, industrial aesthetic, wireframe graphics. Ideal for landing pages, modern websites. AI-ready template. Engineering Blueprint Schematic style represents a modern trend in UI/UX web design focused on technical.

*   Density: 7/10 — Compact
*   Variance: 2/10 — Structured
*   Motion: 1/10 — Static

## 2\. Color Palette & Roles

*   **Background** (#0b1623) — Primary background surface
*   **Text** (#f0f0f0) — Primary text color
*   **Accent** (#ff9f30) — Primary accent, CTAs and interactive elements
*   **Grid Lines** (#1c2b3a) — Extended palette, decorative use
*   **Dim Text** (#8b9bb4) — Primary text color
*   **Success** (#00ff9d) — Success states, positive indicators
*   **Warning** (#ff9f30) — Warning states, attention indicators

## 3\. Typography Rules

*   **Display / Hero:** JetBrains Mono — Weight 700, tight tracking, used for headline impact
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
*   No pure white (#FFFFFF) backgrounds — use off-white or dark surfaces
*   No oversaturated accent colors (saturation cap: 80%)
*   No 3-column equal-width feature layouts — use zig-zag or asymmetric grid
*   No `h-screen` — use `min-h-[100dvh]`
*   No AI copywriting clichés: "Elevate", "Seamless", "Unleash", "Next-Gen"
*   No broken external image links — use picsum.photos or inline SVG
*   No generic lorem ipsum in demos

## AI Prompt

engineering landing page, blueprint style, schematic design, technical precision, dark blue background, cyan lines, industrial aesthetic, wireframe graphics.

Last synced: 4/1/2026
