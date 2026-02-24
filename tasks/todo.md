# Todo — AI Educational Website (Synapse)

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
