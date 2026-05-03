# SMKN1 Flowchart Displayer

A single-page Mermaid flowchart editor with an Office-style ribbon UI, live preview, zoom controls, and PDF export.

## Features

- Ribbon-style interface with Home, View, and Design tabs
- Live Mermaid diagram preview
- Office-like flowchart color style presets
- Visible diagram theme swatches for Default, Dark, Forest, and Neutral
- Legacy custom brand color controls tucked into a collapsed options menu
- Zoom in, zoom out, and reset controls
- Diagram title editing
- Print-friendly PDF export via browser print

## How to Use

1. Open `index.html` in a browser.
2. Edit the Mermaid code in the left panel.
3. Switch to the View tab to adjust zoom.
4. Switch to the Design tab to choose a flowchart style.
5. Open Legacy Options if you want to manually override brand colors.
6. Use Export PDF to print or save the diagram.

## Flowchart Styles

The Design tab includes preset flowchart styles displayed as swatches:

- Corporate Blue
- Emerald
- Graphite
- Warm Accent

These presets control the diagram theme and are intended to be the main styling option.

The Design tab also includes diagram theme swatches for the Mermaid canvas/background:

- Default
- Dark
- Forest
- Neutral

These are shown as visual tiles so the theme changes are easier to preview.

## Legacy Options

The custom color pickers are still available, but they are hidden under Legacy Options.
Use them only if you want manual color overrides instead of the preset styles.
The Mermaid theme dropdown is also tucked into Legacy Options for manual selection.

## Files

- `index.html` - Main application
- `README.md` - Project overview and usage

## Notes

- Mermaid is loaded from a CDN.
- PDF export uses the browser print dialog, which usually gives the best SVG output.
