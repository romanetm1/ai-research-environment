---
name: renamepdf
description: Rename PDFs, EPUBs, and other document files according to the user's academic file-naming conventions for books, journal papers, book chapters, and edited volumes, including colon and invalid-character handling. Use whenever asked to rename a PDF/EPUB/document, or when downloading or naming a new one.
---

# Renaming PDFs and other documents

When asked to rename PDFs (or similar documents), follow these conventions exactly. If a source doesn't cleanly fit one of these patterns (unclear authorship, illegal filename characters beyond a title's own colon, missing edition/editor info, etc.), ask before renaming rather than guessing.

Colons in titles/subtitles are not valid in Windows filenames — render `Title: Subtitle` as `Title_ Subtitle` (colon replaced by underscore, single space preserved before the subtitle).

"?" marks and other signs that cannot be included in a file name must be replaced by an underscore "_".

These same conventions (author/title formatting, colon and invalid-character handling) apply equally when downloading or naming .epub files and other text formats, not just PDFs.

## Books

- One author: `SURNAME, Name. Title_ Subtitle`
- Two–three authors: `SURNAME1, Name1; SURNAME2, Name2. Title_ Subtitle`
- Four+ authors: `SURNAME, Name et al. Title_ Subtitle`
- Edited/organized volumes: same author-count rules above, with `(ed.)`/`(eds.)` or `(org.)`/`(orgs.)` appended to the author segment as appropriate, e.g. `SURNAME, Name (ed.). Title_ Subtitle`

## Journal papers

- One author: `SURNAME, Name. Paper title`
- Two–three authors: `SURNAME1, Name1; SURNAME2, Name2. Paper title`
- Four+ authors: `SURNAME, Name et al. Paper title`

## Book chapters

- In an edited volume: `SURNAME, Name. Chapter title. in_ Editor1 Name1; Editor2 Name2 (eds.). Book title`
- In the author's own book: `SURNAME, Name. Chapter title. in_ Book title`

Keep the original file extension. When in doubt about how a specific source maps onto these patterns, ask the user first instead of improvising a variant.
