<p align="center">
  <img src="logo.png" width="128" alt="KwikaLabel" />
</p>

<h1 align="center">KwikaLabel</h1>

<p align="center">
  Label designer for the <b>Epson ColorWorks TM-C3500</b> colour label printer.<br/>
  Design labels with text, images, shapes and barcodes – then print them straight to the printer.
</p>

<p align="center">
  <a href="../../releases/latest"><b>⬇ Download the latest version</b></a>
</p>

---

## Features

- **Visual designer** – drag, resize and rotate text, images, rectangles, ellipses, lines and barcodes on a
  millimetre-accurate canvas with grid, snapping, alignment tools, undo/redo and copy/paste.
- **Barcodes** – Code 128, Code 39, Code 93, EAN-13, EAN-8, UPC-A, UPC-E, ITF, Codabar, QR Code, Data Matrix,
  PDF417 and Aztec, printed as sharp vector graphics.
- **Print-time data** – ask for values when printing (order numbers, weights, dates…), add the current date/time
  with offsets (e.g. best-before +5 days) and automatic counters / serial numbers, all with formatting such as
  `{BestBefore:dd MMM yyyy}`.
- **TM-C3500 set-up** – label stock presets, paper type and print quality straight from the Epson driver,
  print rotation, automatic paper-size matching and a paper/margin check before printing.
- **Calibration** – print an alignment test page and correct the print position to a tenth of a millimetre.
- **Print window** – preview every label of a job, set the quantity and printer settings, then print without
  the Windows print dialog.

## Requirements

- Windows 10 or Windows 11 (64-bit)
- Epson ColorWorks TM-C3500 with the Epson Windows driver installed
- No other software needed – the .NET runtime is included in the installer

## Install

1. Download **KwikaLabel-&lt;version&gt;-Setup.exe** from the [latest release](../../releases/latest).
2. Run it and follow the wizard. Choose whether you want a desktop shortcut and whether `.kwl` label files
   should open in KwikaLabel.
3. Start **KwikaLabel** from the Start menu. A sample label is installed in
   `C:\Program Files\Kwika\KwikaLabel\Samples`.

> **Windows SmartScreen** may show "Windows protected your PC" for new downloads.
> Click **More info → Run anyway** to continue.

**Upgrading:** run the new Setup.exe – it replaces the previous version and keeps your labels.
**Uninstalling:** *Settings → Apps → KwikaLabel → Uninstall*. Your label files are never removed.

**Silent install (IT deployment):**

```
KwikaLabel-1.2.0-Setup.exe /S
"C:\Program Files\Kwika\KwikaLabel\Uninstall.exe" /S
```

**Verify the download (optional):** each release has a `.sha256` file.

```powershell
Get-FileHash .\KwikaLabel-1.2.0-Setup.exe -Algorithm SHA256
```

## Quick start

1. **Set up the label** – press **F4** (*Document settings*): choose your label stock, the printer, the paper type
   and, if needed, *Rotate on print*. Click **Check paper & margins** to confirm the driver will use the
   label size.
2. **Design** – add elements from the *Insert* panel and adjust them in the properties panel on the right.
3. **Add fields** – in a text's properties use **Insert field / date…** or **Ask when printing…**;
   manage all fields with **F6** (*Variables*).
4. **Print** – press **Ctrl+P**, check the preview, set the quantity and click **Print**.

### Calibrating the TM-C3500

In *Document settings → Calibration*, print the **alignment test**. It shows a frame on the label edge, millimetre
rulers and a centre cross. Measure how far the print is shifted and enter the correction (e.g. frame 1.5 mm too
far right → X = -1.5), then print the test again until the frame sits on the label edge.

## Support

- Web: <https://kwika.ca>
- Email: <support@kwika.ca>

When reporting a problem, use **Help → About → Copy details** and paste the result into your email.

---

© 2026 Kwika. All rights reserved. KwikaLabel is proprietary software; this repository contains releases
and documentation only.
Epson and ColorWorks are trademarks of Seiko Epson Corporation. KwikaLabel is not affiliated with or endorsed
by Seiko Epson Corporation. Barcode encoding by ZXing.Net (Apache License 2.0).
