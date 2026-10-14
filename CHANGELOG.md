# Changelog

## 1.4.0 – 2026-10-14

- **Millimetres or inches**: choose the unit on the toolbar (mm | in), in *View → Units* or in Document
  settings. All sizes, positions, offsets, captions, the status bar and printer messages follow it. Any
  length box also accepts the other unit as you type it: `2in`, `1/2"`, `4 1/4`, `50mm` or `5cm`.
  Labels are still stored in millimetres, so existing files open unchanged.
- **Alignment overlay (F8, or hold O)**: draws the die-cut outline, the rounded corners and the grid
  transparently on top of the artwork, and shades the corner areas that the die-cut will trim, so
  you can see whether square-cornered images line up. Toggle it with the toolbar *Overlay* button or
  F8, or hold **O** to show it only while the key is down.
- Major grid lines are every 10 mm, or every 1 inch when working in inches.
- Arrow-key nudge and mouse-wheel steps follow the chosen unit.
- Install instructions explain the Windows SmartScreen warning for the unsigned installer.

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
