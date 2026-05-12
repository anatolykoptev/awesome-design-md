# Design System: Retro Travel Poster

## 1\. Visual Theme & Atmosphere

Retro travel poster interface. Ideal for landing pages, saas. AI-ready template. Retro Travel Poster style represents a modern trend in UI/UX web design focused on general.

*   Density: 5/10 — Balanced
*   Variance: 7/10 — Dynamic
*   Motion: 1/10 — Static

## 2\. Color Palette & Roles

*   **Warm Paper** (#F3EAD3) — Primary surface or dominant color
*   **Dark Brown** (#3E2F26) — Dark surface, primary background
*   **Rust Red** (#A83E36) — Error states, destructive actions
*   **Warm Tan** (#E8B67C) — Supporting palette color
*   **Forest Green** (#5B8A72) — Success states, positive indicators
*   **Sandy Tan** (#D4A574) — Extended palette, decorative use

## 3\. Typography Rules

*   **Display / Hero:** bold serif/sans display — Weight 700, tight tracking, used for headline impact
*   **Body:** bold serif/sans display — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** bold serif/sans display — 0.875rem, weight 500, slight letter-spacing
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
*   **Hero layout:** Asymmetric composition.
*   **Feature sections:** Asymmetric grid with varied card sizes. No 3-equal-columns.
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

Design a retro travel poster interface. Use: simplified landscape shapes, bold geometric forms, vintage typography, screen-printed flat colors, warm paper background (#F3EAD3), limited earth-tone palette, nostalgic mid-century aesthetic, layered depth.

Last synced: 4/1/2026
