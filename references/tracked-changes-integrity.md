# Tracked Changes and DOCX Integrity

## Preservation Rules

Preserve:

- existing `w:ins`, `w:del`, move, and formatting-change markup;
- existing comments and comment authors;
- content controls and citation fields;
- `SEQ`, `REF`, `PAGEREF`, TOC, bibliography, and reference-manager fields;
- drawing, chart, image, equation, footnote, endnote, and hyperlink relationships;
- paragraph and character styles;
- section properties, headers, footers, and page numbering.

## Minimal Redlines

- Track only the smallest necessary range.
- Avoid replacing entire paragraphs or table cells for local corrections.
- Preserve surrounding run properties in inserted text.
- For punctuation edits, track the punctuation rather than the sentence when technically safe.
- Do not flatten fields to make editing easier.

## Clean Copy

Generate the clean copy from the tracked output. Accept insertions, deletions, moves, and formatting revisions in the clean derivative. Remove comments only from the clean derivative unless instructed otherwise.

## Structural Checks

Compare source, tracked, and clean files for:

- package part inventory;
- tables, images, fields, hyperlinks, comments, and revisions;
- sections and headers/footers;
- footnotes/endnotes;
- visible text length and unexpected character changes.

## Visual Checks

Render every page. Inspect:

- text clipping, overlap, and blank pages;
- table row splitting, cell overflow, and caption separation;
- figures and image resolution;
- equations, symbols, subscripts, superscripts, and Greek letters;
- reference indentation and line wrapping;
- tracked-change readability;
- headers, footers, and page numbers.
