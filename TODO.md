# TODO

## General

- Start tracking some of the samples about how they behave in various PDF viewers:
  Adobe Reader, Acrobat, Sumatra, Preview.app, Ghostscript, MuPDF, Evince, XPDF, Chrome's internal PDF viewer, PDF.js, Windows 10 builtin Reader,...
- Maybe write some simple Python scripts which auto-generate the `xref` and the `trailer` given a file that already has PDF header and body of objects?
- Other helper tools for creating hand-written PDFs:
  Python script which encode/decode arbitrary blobs of data (`/ASCIIHexDecode`, `/ASCII85Decode`, `/LZWDecode`, `/DCTDecode`, `/FlateDecode`, `/RunLengthDecode`, `/JBIG2Decode`, `/CCITTFaxDecode`, `/JPXDecode`, `/Crypt`).
  Not all at once, though...

## File Wishlist

- TODO: (almost) empty template(s) to kickstart hand-making PDFs
    * Text (1-page, 2-page, 4-page)
    * Images (1-page, 2-page, 4-page)
    * Vector drawings (1-page, 2-page, 4-page)
- TODO: OCG / Layers: visible - invisible - printable
- TODO: Watermarks (efficient)
- TODO: text hidden by other object
- TODO: cropped object (LaTeX illustrations)
- TODO: JavaScript in a PDF
- TODO: internal links in PDF
- TODO: fillable forms in a PDF
- TODO: bookmarks in a PDF
- TODO: annotations in a PDF
- TODO: redaction (good + bad)

&nbsp;

- DONE: different ways to show "text" on page    
  SEE: `004_text_display.pdf`

- DONE: some sort of challenge/riddle for TROOPERS in a PDF ?    
  SEE: `115_little-riddle.pdf`

- DONE: incrementally updated PDF file    
  SEE: `114_incrementally-updated.pdf`

- DONE: JPEG image in a PDF    
  SEE: `107_perspectives-by-banksy.pdf`

- DONE: "text" by drawing outlines     
  SEE: `102_A-vectorized.pdf`

- DONE: "text" with font NOT embedded     
  SEE: `104_fonts-not-embedded.pdf`

- DONE: "text" with font embedded     
  SEE: `106_hello-troopers.pdf`    
  SEE: `108_text-rendering-modes.pdf`    
  SEE: `112_play-with-tounicodetable.pdf`    
  SEE: `113_stegano-with-tounicodetable.pdf`

- DONE: CTM demo + playground     
  SEE: `105_transformation-matrix.pdf`     
  SEE: `111_current-transformation-matrix-ctm.pdf`
