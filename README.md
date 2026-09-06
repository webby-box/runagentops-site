# @runagentops — trust landing

Static page. Opens locally. Live Shieldz pay buttons for Loom / Autopsy / Kit.

## Files

| File | What |
|------|------|
| `index.html` | Trust landing — open this |
| `styles.css` | Layout, type, borders |
| `standup-onepager.md` | Free daily standup sheet (markdown) |
| `README.md` | This note |

## Open locally

```bash
# from this directory
open index.html
# or
python3 -m http.server 8765
# then visit http://127.0.0.1:8765/
```

## Offers (live Shieldz)

| Offer | Price | Role |
|-------|-------|------|
| Loom Review | $49 | Primary (featured) |
| Agent Autopsy | $29 | Secondary |
| Agent Ops Kit | $39 | Tertiary |

Pay links are hardcoded in `index.html` (`target="_blank"` + `rel="noopener noreferrer"`).

## Brand rules (keep)

- Voice: human, not AI slop. Tagline stays as-is.
- Brand only `@runagentops` — no invented company/legal names.
- Intake-first tone OK; CTAs are live Shieldz buttons.
- Free standup sheet linked (`standup-onepager.md` + X).
- **No** wallet addresses, KYC/phone forms, crypto jargon walls, Polar/Gumroad.

## Deploy note

Any static host works (GitHub Pages, Netlify, Cloudflare Pages, raw S3). Ship `index.html` + `styles.css` together; `standup-onepager.md` is optional public companion / DM attach.
