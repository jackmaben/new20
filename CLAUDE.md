# Project notes — OptimizeTechStudio site

## Section structures
When building or restructuring any page, reuse the section structures that already exist
anywhere on this site. Do not invent new layout patterns and do not add new CSS unless
there is genuinely no existing structure that fits.

Preference order:
1. **Original structures the user did not change** — these are the preferred/default choice.
2. Newer structures added later — fine to use, mix in for variety.

Vary structures within a page so consecutive sections don't repeat the same pattern.

Known structures (class → where it's used):
- `.ixgrid.three` + `.ix` (`ix-wm`, `ix-glyph`, `ix-p`, `ix-line`) — service card grids
- `.who-grid` + `.who-card` (`label`, h3, p) — service/audience cards, linkable
- `.tilegrid` + `.tile` (`tile-mark`) — short label tiles
- `.diptych` + `.dip-row` (`dip-a`/`dip-tag`, `dip-arrow`, `dip-b`) — problem → response rows
- `.disclose` + `details.dsc` (`dsc-n`, `dsc-t`, `dsc-tag`, `dsc-ico`, `dsc-body`) — accordions
- `.tower[data-tower]` + `.tw-row` (`tw-body`, `tw-node`, `tw-copy`) — stepped process / stacked points
- `.rel-grid` + `.rel-card` (`rel-k`, `rel-go`) — related-page cards
- `.faq` + `details.faq-item` + `.answer` — FAQ
- `.cta-strip`, `.mid-cta` + `.mid-cta-actions`, `.ready-cta` + `.ready-cta-action`, `.cta-note.hl` — CTAs
- `.page-hero` (`crumbs`, `page-hero-grid`, `eyebrow`, `accent-word`, `lede`, `hero-actions`, `hero-trust`)
- `.section-head` (`section-tag` + `num`, h2, `section-intro`); sections alternate `.s` / `.s.soft`
- `.rel-cross-block` — related services link list

## Copy — hard rule
Use ONLY copy from the user's source documents. Never write content of my own (no intros,
stats, headings, or filler) and never cut, shorten, or paraphrase source copy to make it fit.

If the source content does not fit any existing structure, STOP and ask the user for
permission to create a new structure/section for it. Do not decide this alone.

## Shell
Header nav, footer, mobile bar, and script/stylesheet tags are identical across pages —
copy them from an existing page rather than rewriting. Asset version is `?v=g93`.
New pages must be added to: Services dropdown, footer Services list, sitemap.xml.
