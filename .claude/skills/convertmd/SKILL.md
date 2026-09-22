---
name: convertmd
description: Convert a PDF or other source document into Markdown — reconstructing tables as real Markdown tables, preserving figures/charts as embedded images, skipping running headers/footers/page-number chrome, sanity-checking reconstructed tables, and flagging anything that can't be reconstructed with confidence. Use whenever asked to convert a PDF/document to Markdown or .md.
---

# Converting PDFs and other sources to Markdown

- Reconstruct tables as real Markdown tables (proper rows/columns), even when the source has no visible gridlines or is rotated/scanned at an angle. Never flatten a table into prose.
- Preserve genuine figures/charts as embedded images; never describe-and-discard them as text.
- Skip decorative or repeated page furniture: running headers/footers, logos, watermarks, page numbers used purely as chrome.
- Before finalizing, sanity-check reconstructed tables (row/column counts consistent across the table, no dropped cells). If any table or figure cannot be reconstructed with confidence, explicitly flag it in the output rather than silently approximating it.
- State when necessary information is missing or impossible to retrieve.
