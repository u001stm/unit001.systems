# CROCUS / A4 DOCUMENT MASTER

**Status:** default master for CROCUS one-page A4 documents (v0.3)

## Fixed frame

- A4 portrait, 210 × 297 mm.
- Page margins: 15 mm left/right (43 pt). Content starts below the header, around 35 mm from the top.
- Header: **only the Crocus «C» mark at the upper-right**, fixed position. No oversized product title or additional headers.
- Content: small plain document label, then information in a restrained grid. No boxes or outer frames; light-gray hairline dividers only.
- Footer: fixed baseline at 14 mm from bottom; three technical fields: `DEV.001 / CROCUS` · document identifier · `VERSION · A4 · PAGE`.
- Typography: **Helvetica / IBM Plex family only** for production masters. One family per document where possible; regular and bold only. No mixed display styles or arbitrary font changes.
- MA: generous intentional whitespace; do not fill gaps decoratively. Consistent spacing between repeated sections.

## Reuse policy

All future A4 pages reuse the **same header, footer, margins, grid and type scale**. Only the content area and technical document identifier/version may change. Do not invent a new cover/header/footer per deliverable.

## Current implementation note

The current PDF `CROCUS_User_Roles_A4_v03.pdf` uses a Helvetica-compatible Cyrillic font substitute for correct Cyrillic rendering because the approved font files were unavailable in the PDF environment. When Helvetica/IBM Plex fonts are available, replace the substitute without changing the template geometry.
