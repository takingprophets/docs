# Taking Prophets Documentation — Project Instructions

## About this project

- Documentation site for **Taking Prophets**, a futures trading indicator software company
- Built on [Mintlify](https://mintlify.com) — pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## About the product

Taking Prophets builds custom **Pine Script indicators** for TradingView, targeting futures day traders. The product has two main tracks:

- **In-house indicators** — Proprietary suite sold via a $45/month membership (`indicators/` section)
- **Partner indicators** — Custom indicators co-developed with trading influencers, sold to their audiences (`partners/` section)

Key context:
- Indicators run on TradingView as private invite-only Pine Script scripts
- Primary instruments: ES, NQ, MES, MNQ (CME futures)
- Live trading sessions run daily Mon–Fri, 9–11 AM ET
- Community lives on Discord (~2,000 members)

## Terminology

- Use **"indicator"** not "tool" or "script" when referring to our Pine Script indicators
- Use **"members"** not "users" or "customers"
- Use **"invite link"** not "license key" or "access code"
- Use **"partner indicator"** not "third-party indicator"
- Use **"futures"** not "stocks" — this product is futures-only
- Refer to the daily stream as **"live session"** or **"live trading session"**

## Style preferences

- Active voice, second person ("you")
- One idea per sentence — keep it concise
- Sentence case for headings
- Bold for UI elements: Click **Indicators**
- Code formatting for file names, commands, paths: `docs.json`
- Don't over-explain — assume the reader is a competent trader, not a beginner

## Content boundaries

- Document indicators only after reading their Pine Script source files
- Do not make up signal names, logic, or settings — derive everything from the source
- Do not document internal pricing, partner revenue splits, or business operations
- Support/troubleshooting content should always point to Discord as the first line of help
