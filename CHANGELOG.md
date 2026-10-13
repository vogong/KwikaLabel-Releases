# Changelog

## 1.3.0 – 2026-10-13

- **Design with AI (F7)**: describe a label in plain language and an OpenRouter model lays it out, or
  changes the open label. Preview and refine before applying; applying is one undo step. API key stored
  encrypted (Windows DPAPI); any OpenRouter model can be used.
- Image properties: **Choose image…** sets or replaces the picture of an image element.
- Label files tolerate numbers written as strings.

## 1.2.0 – 2026-10-11

First public release.

- Visual label designer: text, images, shapes and 13 barcode types; move, resize, rotate, align, z-order,
  lock, grid and snapping, undo/redo, copy/paste (including images from the clipboard).
- Document settings: label size and stock presets for the Epson ColorWorks TM-C3500, paper type, print
  quality and other driver options, print rotation, Epson driver settings stored with the label.
- Automatic matching of the label size to the driver's paper sizes, plus a paper & margin check.
- Fields and variables: values asked at print time, date/time with offsets, counters, .NET-style formatting.
- Print window with page-by-page preview, quantity, printer settings and direct printing.
- Alignment test page and X/Y print offset calibration.
- PNG export, sample label, application icon, About box, Windows installer.
