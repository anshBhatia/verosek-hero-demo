# Verosek Hero Demo

Scroll-driven hero prototype for Verosek. A pinned 500vh section where the
apps/AI layers fade away and the four Verosek slabs explode out of the stack,
each one activating a callout as it scrolls into its act.

## Files

| File | Purpose |
| --- | --- |
| `verosek-prototype.html` | The demo. Self-contained — images are embedded as base64, GSAP + ScrollTrigger load from CDN. |
| `slab 01–04.png` | Source slab renders (shield, gateway, audit, MCP). |
| `your apps.png`, `ai.png` | Source renders for the top and bottom layer groups. |
| `vercel.json` | Serves the prototype at `/`. |

## Slab order

Top to bottom in the exploded state:

1. **Gateway** — `slab 02.png`
2. **Shield** — `slab 01.png`
3. **MCP Tools** — `slab 04.png`
4. **Audit Vault** — `slab 03.png`

## Running locally

Open `verosek-prototype.html` directly in a browser — no build step, no server
needed.
