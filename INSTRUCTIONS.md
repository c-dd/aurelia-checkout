# AMIA LABS — Prototypes & Instructions

Three standalone age-gate + checkout prototypes. Each `.html` is fully self-contained and
works offline — no server, no internet, no install. **Double-click any file to open it.**

## Files

- **`Obsidian.html`** — dark / electric-cyan, rotating 3-D peptide molecule
- **`Lumen.html`** — cream + amber, gold flow-field
- **`Flux.html`** — acid-green terminal, DNA helix

Keep all three in the same folder — the header menu switches between them.

## Each prototype

1. **Age gate (21+)** — tick the box, click Enter. Remembered per browser; open an incognito
   window to see it again.
2. **Homepage → checkout.** Above the form, a **Standard · Products · Proof** switcher picks
   the checkout type:
   - **Standard** — amount + card
   - **Products** — pick a product (or Custom) + card
   - **Proof** — amount + upload a payment screenshot/PDF (no card)
3. **Thank-you** with an auto-generated reference number.

Tip: **⚡ AUTO-FILL SAMPLE DATA** completes a valid order in one click (in Proof mode it also
attaches a fake receipt) so you can run the whole flow fast.

## Important — these are prototypes

- Payments are **simulated** — no real charge, no card data leaves the browser.
- The Proof-mode autofill fabricates a fake receipt for demoing; remove it before real use.
- Before going live you'll need a real payment processor, a backend (orders, reference
  numbers, proof storage, confirmation email), and confirmed prices + compliance language.
