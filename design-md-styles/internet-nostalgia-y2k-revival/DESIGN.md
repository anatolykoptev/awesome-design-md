# Design System: Internet Nostalgia Y2K Revival

## 1\. Visual Theme & Atmosphere

Landing page with full Windows 95/98 internet nostalgia aesthetic. Ideal for portfolios criativos retro, jogos indie, eventos tematicos, blogs pessoais nostalgicos, lancamentos de produto ironicos, comunidades de nicho. AI-ready template.

*   Density: 5/10 — Balanced
*   Variance: 7/10 — Dynamic
*   Motion: 4/10 — Subtle

## 2\. Color Palette & Roles

*   **Cinza Sistema** (#C0C0C0) — Secondary text, borders, muted elements
*   **Azul Titulo** (#000080) — Accent highlight, links and focus states
*   **Branco Janela** (#FFFFFF) — Light surface, card backgrounds
*   **Preto Texto** (#000000) — Dark surface, primary background
*   **Verde Terminal** (#00FF00) — Success states, positive indicators
*   **Ciano DOS** (#00FFFF) — Extended palette, decorative use
*   **Magenta Retro** (#FF00FF) — Decorative accent, highlight elements
*   **Amarelo Alerta** (#FFFF00) — Error states, destructive actions
*   **Prata Borda** (#808080) — Extended palette, decorative use

## 3\. Typography Rules

*   **Display / Hero:** Courier New — Weight 700, tight tracking, used for headline impact
*   **Body:** Courier New — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** Courier New — 0.875rem, weight 500, slight letter-spacing
*   **Monospace:** Courier New — Used for code, metadata, and technical values

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

*   **Physics:** Ease-out curves, 200-300ms duration. Smooth and predictable.
*   **Entry animations:** Fade + translate-Y (16px → 0) over 420ms ease-out. Staggered cascades for lists: 80ms between items.
*   **Hover states:** Subtle color shift + shadow adjustment over 200ms.
*   **Page transitions:** Fade only (200ms).
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

Design a landing page with full Windows 95/98 internet nostalgia aesthetic. Create window-like containers with BEVELED BORDERS (border-style: outset 2px for raised, inset 2px for pressed). Blue title bars (#000080) with white text, minimize/maximize/close buttons as small squares. Classic beveled push buttons that depress on click (outset → inset on :active). Dialog box popups with exclamation/question icons. ASCII art sections using \<pre> tags with monospace font. Pixel art graphics with image-rendering: pixelated and crisp-edges. System gray (#C0C0C0) as the main background color. Custom retro cursors. Scrollbar styling to match Windows 95 look. Table-based visual layout (using CSS grid that LOOKS like tables). 16-bit color palette feel. Geocities-era decorative elements: under construction GIF references, visitor counter, guestbook link. Font: 'Courier New' for ASCII, system-ui for UI elements.

Last synced: 4/1/2026
