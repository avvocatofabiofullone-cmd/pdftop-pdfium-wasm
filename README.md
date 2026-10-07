# PDFTop PDFium WASM

Experimental WebAssembly build infrastructure for PDFTop's browser-side PDF editor.

## Goal

Expose PDFium editing APIs required to modify existing PDF text objects instead of drawing replacement text over the page.

Initial API target:
- FPDFText_GetTextObject
- FPDFTextObj_GetText
- FPDFText_SetText
- FPDFPage_GenerateContent
- document save APIs

No user documents are stored in this repository.

## License

Build glue in this repository is MIT licensed. PDFium and third-party components retain their respective upstream licenses.
