# AI Implementation Notes

This project is a visually calibrated Three.js interaction. Treat the existing source as the reference implementation when reproducing, extending, or customizing it.

## Preserve by default

Unless a requested change specifically targets animation behavior, preserve:

- Three.js version and module-loading behavior
- camera field of view and camera position
- helix radius, pitch, start position, travel distance, and dip equation
- nine-card helix order and motion
- column-by-column card deformation along the helix
- helix card dimensions
- guide-line geometry, path, timing, spacing, opacity, and depth ordering
- upper guide line behind the cards
- lower guide line above the cards
- opening dark-to-light transition
- large transition-title sequence
- `Codex +` and `Three.js` entrance, hold, and exit sequence
- spacing, scale, and vertical alignment of the `+`
- 3-column × 2-row closing grid
- grid card dimensions, spacing, and ordering
- overlapping grid-card entrances
- sheet-like deformation and progressive settling
- closing light-to-dark footer transition
- responsive behavior

## Safe customization areas

Content-oriented changes can usually be limited to:

- card artwork
- visible copy
- brand colors
- CTA text
- labels or project names

Do not alter animation constants solely to accommodate content changes.

## Implementation approach

When working in a file-capable coding environment:

1. Inspect the reference files before editing.
2. Reproduce the existing file structure and behavior faithfully when creating a new working copy.
3. Keep changes narrowly scoped to the requested outcome.
4. Avoid unnecessary framework or dependency substitutions.
5. Use the simplest preview method available in the current environment.
6. Validate the finished result against `VALIDATION.md`.

If the reference source cannot be accessed, do not invent a substitute implementation and present it as equivalent.
