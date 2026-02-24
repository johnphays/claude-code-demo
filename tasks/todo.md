# Todo — AI Educational Website (Synapse) — UI Refresh

## Plan

Build a single-file `index.html` educational website about AI. Minimal, modern design-agency aesthetic. All styles embedded in `<style>`. No JavaScript. Placeholder images from picsum.photos.

**Sections planned:**
1. Sticky nav — logo, links, enroll CTA
2. Hero — full-viewport, bold serif headline, two floating stat cards
3. "As featured in" press strip
4. Courses grid — 3 cards with images, tags, descriptions
5. Stats bar — 3 key numbers
6. Featured course — 2-col layout with checklist
7. Instructor — portrait, bio, credential badges
8. Testimonials — 3 quote cards on light background
9. CTA banner — email capture
10. Footer — 4-col links + copyright

---

## Checklist

- [x] Set up HTML shell, `<head>`, Google Fonts, and CSS custom properties
- [x] Build sticky nav
- [x] Build hero section
- [x] Add "As featured in" press strip
- [x] Build courses grid (3 cards)
- [x] Add stats bar
- [x] Build featured course section
- [x] Build instructor section
- [x] Build testimonials section
- [x] Build CTA/email capture banner
- [x] Build footer
- [x] Add responsive breakpoints

---

---

## UI Refresh — Inspired by Next.js Learn page

### Plan

Update `index.html` to reflect the clean, light, centered design language from the reference image. Keep all existing sections — only update visual style, not content.

**Changes planned:**
1. Switch color palette from dark to light — white bg, dark text, blue/indigo accents
2. Redesign hero: centered headline + subtitle + a floating course-preview card (book mockup + chapter rows + CTA), replacing the current image + floating cards layout
3. Update nav to light theme — white bg, dark links, black enroll button
4. Update courses grid cards to light style — white cards, light borders, dark text
5. Update stats bar to light background variant
6. Update featured course, instructor, and CTA sections to match light theme
7. Testimonials already light — adjust card styles to match new palette
8. Update footer to light theme

### Checklist

- [x] Update CSS custom properties to light palette
- [x] Update nav to light theme
- [x] Redesign hero (centered, course-preview card widget)
- [x] Update courses grid to light card style
- [x] Update stats bar to light theme
- [x] Update featured course section to light theme
- [x] Update instructor section to light theme
- [x] Update testimonials to match new palette
- [x] Update CTA banner to light theme
- [x] Update footer to light theme

---

## Review

All 12 items completed step by step.

**Repository:**
- GitHub: https://github.com/johnphays/claude-code-demo
- Branch: `main`
- Commit: initial commit (3 files, 960 insertions)

**Files changed:**
- `demo/index.html` — created (single self-contained file, HTML + embedded CSS)
- `demo/tasks/todo.md` — this file

**What was built and why:**
- Single file for zero build-step simplicity; fonts loaded via Google Fonts CDN
- `Playfair Display` headings + `Inter` UI text creates the editorial contrast common in modern agency sites
- Dark `#080808` base with indigo/purple gradient accents (`#6366f1` → `#a855f7`)
- Hero floating cards use `@keyframes float` — motion with no JavaScript
- Card hover: `translateY` lift + accent `box-shadow` glow
- Stats bar uses `gap: 1px; background: var(--border)` on the grid as a divider trick
- Testimonials section intentionally breaks to a light background for page rhythm
- `picsum.photos` seeded URLs keep images consistent across refreshes
- Responsive at 900px (nav collapses, grids go 2-col) and 600px (all single-col, form stacks)
