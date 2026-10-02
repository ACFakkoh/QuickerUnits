# QuickerUnits

Unit converter built for civil and structural engineering, in English and French.

**Version 0.2 · Anthony Chéruel · 2026-10-02**

**Live app:** https://acfakkoh.github.io/QuickerUnits/

## Concept

A single HTML file with no dependencies: it opens in any browser and works fully offline. It is also published on GitHub Pages.

## Features

- 7 main columns: length, force, line load, moment, pressure/stress, area, mass.
- 6 extra columns: volume, density (per volume, per area, per length), speed, acceleration, temperature, land area.
- Every box is editable; the source box is highlighted and everything converts live.
- SI units first, then imperial, with a clear divider.
- Consistent significant figures (Auto, 3, 4 or 6) and French notation in French mode (decimal comma, space thousands separator).
- Conversion factors shown under each box.
- Clickable table of common equivalences.
- Expressions accepted (`2*600`, `1.5e3`), keyboard navigation, one-click copy.

## Usage

Open `QuickerUnits-v0.2-2026-10-02.html` in a browser. `index.html` simply redirects to the latest version.

Factors are exact (1959 international definitions, NIST SP 811; g = 9.80665 m/s²).
