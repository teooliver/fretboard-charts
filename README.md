# Guitar Fretboard Chart

A collection of printable guitar fretboard grid templates for practice and learning.

## Overview

This project provides HTML-based guitar fretboard diagrams that can be printed on A4 paper. These templates are useful for:
- Practicing scales and patterns
- Visualizing chord shapes
- Mapping out music theory concepts
- Taking notes during practice sessions

## Files

### fretboard-grids.html
A grid of 16 small fretboard diagrams (4x4 layout) with:
- 6 strings
- 5 frets per grid
- Compact size ideal for quick sketches

### fretboard-scale-grid.html
4 larger horizontal fretboard diagrams optimized for scale practice with:
- 6 strings (running horizontally)
- 12 frets (running vertically)
- Larger size for detailed notation
- Perfect for practicing scale patterns across the neck

## Generating PDFs

Use the included Node.js script to generate PDF versions:

```bash
node generate-pdf.js
```

This will create PDF files ready for printing on A4 paper.

### Requirements
- Node.js
- Puppeteer (install with `npm install puppeteer`)

## Usage

1. Open the HTML files in a web browser
2. Print directly or use the PDF generation script
3. Fill in the grids with notes, scales, chords, or patterns

## Print Settings

For best results when printing:
- Paper size: A4
- Margins: None/Minimal
- Print backgrounds: Enabled
