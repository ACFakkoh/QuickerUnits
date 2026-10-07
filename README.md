# QuickerUnits

Unit converter built for civil and structural engineering, in English and French.

**Version 0.4 · Anthony Chéruel · 2026-10-06**

**Live app:** https://acfakkoh.github.io/QuickerUnits/

## Concept

A single HTML file with no dependencies: it opens in any browser and works fully offline. It is also published on GitHub Pages.

## Features

- 7 main columns: length, force, line load, moment, pressure/stress, area, mass.
- 9 extra columns: volume, density (per volume, per area, per length), moment of inertia I, section modulus S, stiffness K, speed, acceleration, temperature, land area. I and S include the CISC handbook units (10⁶ mm⁴, 10³ mm³).
- Quick convert bar (press `/`): type `25 ksi to MPa`, `3/4 in` or `100 °C to °F` and get the answer instantly; Enter opens the matching column.
- Every box is editable; the source box is highlighted and everything converts live.
- SI units first, then imperial, with a clear divider.
- Consistent significant figures and French notation in French mode (decimal comma, space thousands separator).
- Optional conversion factors under each box.
- Clickable table of common equivalences.
- Expressions accepted (`2*600`, `1.5e3`), keyboard navigation, one-click copy.

## Usage

Open `QuickerUnits-v0.4-2026-10-06.html` in a browser. `index.html` simply redirects to the latest version.

Factors are exact (1959 international definitions, NIST SP 811; g = 9.80665 m/s²).
