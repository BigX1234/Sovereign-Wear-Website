# SOVEREIGN (SVRN) — Brand Conventions & Always-Do Rules

## Brand Identity
- **Full name:** Sovereign
- **Handle / abbreviation:** SVRN
- **Domain:** sovereignwear.com.au
- **Positioning:** Raw, premium, intense. Tesla/Rolex energy. Discipline over comfort. Not vanity-driven.
- **Target:** Men and women 16–35, gym/sport/outdoor. Gold Coast origin, nationally scaling.
- **Taglines:** "Master yourself." / "Discipline over comfort."

## Design System (LOCKED — do not deviate)

### Colours
| Token      | Hex       | Usage                        |
|------------|-----------|------------------------------|
| Ink        | `#0b0b0b` | Primary background, dark UI  |
| Bone       | `#f0ece1` | Primary text, light surfaces |
| Graphite   | `#2a2d32` | Secondary dark, cards, statement bg |
| Pearl      | `#ededed` | Secondary light, hover states |
| Muted      | `#7a7a7a` | Body copy, subtext, labels   |

**No gold. No other accent colours. Monochrome only.**

### Typography
| Role              | Font              | Weight |
|-------------------|-------------------|--------|
| Display / Headers | Archivo           | 800    |
| Subheadings       | Archivo           | 600    |
| Body text         | Inter             | 400    |
| Body emphasis     | Inter             | 600    |

- Google Fonts: `Archivo:wght@400;600;800` + `Inter:wght@400;600`
- Headers: UPPERCASE, tight tracking (`letter-spacing: -0.02em`)
- Eyebrow labels: Archivo 600, wide tracking (`letter-spacing: 0.2em+`), muted colour

### Logo
- Angular geometric SV monogram — hard edges, no curves
- Three colourways: Ink, Graphite, Bone
- SVRN wordmark in Archivo 800

## Always-Do Rules
1. **Plan before mutating** — outline logic before any file change
2. **Never edit Live theme directly** — always use a draft branch/theme
3. **Draft/Hidden first** — set all products and discounts to draft for review before publishing
4. **Mobile-first** — 70%+ traffic will be mobile. Design for smallest screen first.
5. **Premium test** — every design decision must answer: "Does this look premium? Does it match the Sovereign message?"
6. **No clutter** — minimal UI only. If it doesn't need to be there, remove it.
7. **Editorial feel** — content should feel like a luxury editorial, not a typical Shopify catalogue.

## File & Branch Rules
- Active development branch: `claude-draft`
- Production / Cursor work preserved on: `main`
- Log all changes in `PROGRESS.md`

## Shopify Setup
- Platform: Shopify
- Store: sovereignwear (admin URL TBC)
- Domain: sovereignwear.com.au
- Payments: Shopify Payments (to be configured)
- Theme approach: Dawn base → custom overrides, or custom theme from scratch
