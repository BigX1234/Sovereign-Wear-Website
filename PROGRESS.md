# SVRN — Progress Log

All changes logged here as an audit trail.

---

## 2026-06-18 — Session 1 (Claude Code, claude-draft branch)

### Context
Picked up from Cursor session (hit limit). Original work on `main` branch preserved.
Working on `claude-draft` branch to avoid mixing directions.

### Completed
- [x] Created `claude-draft` git branch from `main`
- [x] Created `CLAUDE.md` — brand conventions and always-do rules
- [x] Created `PROGRESS.md` — this file
- [x] Rewrote `index.html` to match brand system:
  - Brand name corrected: "Sovereign Wear" → "SVRN / Sovereign"
  - Tagline corrected: "Wear your sovereignty" → "Master yourself."
  - Positioning updated to activewear (not general apparel)
  - Added scrolling marquee: "DISCIPLINE OVER COMFORT · SVRN · MASTER YOURSELF"
  - Added brand statement section: "Discipline over comfort."
  - Added About section with stats (400gsm, 4-way stretch, AU-designed)
  - Renamed contact section to Waitlist (pre-launch focus)
  - Updated footer with domain reference (sovereignwear.com.au)
- [x] Rewrote `css/styles.css` to match locked design system:
  - Colours: Ink #0b0b0b, Bone #f0ece1, Graphite #2a2d32, Pearl #ededed (gold accent removed)
  - Fonts: Archivo 800/600 for display, Inter 400/600 for body (Cormorant Garamond removed)
  - Full mobile-first responsive layout
  - Ghost button variant added
  - Marquee animation added

### Next Up
- [ ] Drop logo files into `/assets/` once provided
- [ ] Set up Shopify CLI and connect to store
- [ ] Build Shopify pre-launch page (waitlist capture)
- [ ] Build full Shopify store structure (nav, collections, product pages, about, contact)
- [ ] Implement design system across all Shopify theme files
- [ ] Connect sovereignwear.com.au domain
- [ ] Configure Shopify Payments
