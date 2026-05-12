# Design System: Analytics Metric Flow

## 1\. Visual Theme & Atmosphere

Design uma landing page analytics SaaS em scroll contínuo: hero fullscreen com headline 'Every number that matters. Ideal for saas analytics, dashboards de métricas, plataformas de dados, ferramentas de integração. AI-ready template.

*   Density: 8/10 — Dense
*   Variance: 2/10 — Structured
*   Motion: 4/10 — Subtle

## 2\. Color Palette & Roles

*   **Verde escuro** (#14532D) — Dark surface, primary background
*   **Verde CTA** (#16A34A) — Primary accent, CTAs and interactive elements
*   **Branco quente** (#F7F8F3) — Light surface, card backgrounds
*   **Cinza texto** (#111827) — Primary text color
*   **Cinza suave** (#E5E7EB) — Secondary text, borders, muted elements
*   **Verde claro** (#DCFCE7) — Success states, positive indicators
*   **Cinza tabela** (#F3F4F6) — Secondary text, borders, muted elements

## 3\. Typography Rules

*   **Display / Hero:** SF Pro Text — Weight 700, tight tracking, used for headline impact
*   **Accent:** Segoe UI — Used for decorative or emphasis text
*   **Body:** SF Pro Text — Weight 400, 16px/1.6 line-height, max 72ch per line
*   **UI Labels / Captions:** SF Pro Text — 0.875rem, weight 500, slight letter-spacing
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

Design uma landing page analytics SaaS em scroll contínuo: hero fullscreen com headline 'Every number that matters. All in one place.', ilustração abstrata de dados em pontos verdes à direita, navbar superior simples, seção de métricas com 3 KPIs (ex: 1.845, $125K, 92%), seção 'Connects with every tool' com grid de ícones de integrações em cards arredondados, seção tabela de transações recentes com linhas alternadas, e CTA final 'Your data is waiting' com botão verde. Use muito espaço em branco, fundo off-white, e verde como cor principal de ação.

Last synced: 4/1/2026
