# IDR-Assessment
# IDR — Design Rationale

## Logo

The icon uses an **isometric cube** rendered in two-tone treatment: an orange top face (the "known" surface — structured, visible risk) against darker left and right faces (the shadow zones — uncertainty, threat vectors). A small central node marks the convergence point, echoing the institute's role as a nexus between academia and industry. The vertical rule and spaced-caps wordmark in Georgia serif give authority without stuffiness. Both variants (icon-only and icon + wordmark) are legible at 16px favicon size.

**Colour**: Orange (#FF6B1A) on near-black (#0A0A0A) — high contrast, energy, urgency. Orange reads as both caution (risk awareness) and momentum (forward motion). White type bridges the two. No mid-greys in the logo palette; the contrast is deliberate and bold.

**Typography**: Georgia serif for the display abbreviation "IDR" and `DM Serif Display` on the website — a rational, slightly editorial serif that signals academic credibility. Body copy uses `DM Sans`, its purpose-built companion, keeping UI elements clean and readable.

**Symbolism**: The cube is a universal shorthand for structured systems, 3D modelling, and resilience under pressure. The isometric view implies multiple perspectives on the same object — appropriate for risk: every threat has a visible face and hidden surfaces.

## Homepage

- **Aesthetic direction**: Industrial precision — dark ground, orange geometry, grid texture. Not startup-playful; deliberately serious, institutional, and credible.
- **Grid motif**: Subtle 80px dot-grid backgrounds echo technical blueprints and risk matrices.
- **Animation**: Staggered fade-up on hero text; scroll-triggered reveal on sections. CSS-only where possible; no libraries.
- **Pillars grid**: Rendered as a bordered table-like structure (1px gap, shared background) — deliberately austere, like a risk register. Top border activates on hover to orange.
- **Pipeline**: Horizontal on desktop, vertical stacked on mobile — both fully readable.
- **Typography scale**: 5.5rem hero headline → 2.75rem section titles → 1.05rem body. Clear hierarchy.
- **Accessibility**: Semantic HTML5 (header, nav, main, section, footer), ARIA labels on interactive elements, focus-visible on all controls, colour contrast ≥ 4.5:1 on all text.
