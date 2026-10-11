# EduSnap Mathematics Toolkit

A responsive, dark-first mathematics toolkit built as a static frontend. Open `index.html` directly, or serve this repository from its root:

    python3 -m http.server 8000

Then visit http://localhost:8000.

## Brand assets

- `public/brand/edusnap-dark.png` is the supplied dark-mode badge with only the outer whitespace cropped. The navbar and local workspace dialog use this single logo.
- `public/brand/edusnap-favicon.png` is a 128px favicon derived from the same circular badge.
- The reusable `<edu-snap-logo size="sm|md|lg">` custom element uses the supplied artwork at 38px, 48px, or 120px. It has no alternate theme or logo variant.

## Included tools

- Graphing calculator with function plotting, pan/zoom, root and intersection scans
- Draggable coordinate geometry triangle with live side lengths, angles, and area
- Matrix calculator for common operations, including determinant, inverse, rank, trace, and multiplication steps
- Statistics calculator with summary measures, histogram, and box plot
- Linear and quadratic equation solver with real/complex roots and working
- Definite integral visualizer with signed area shading and accumulation animation
- Rotatable 3D plane and line scene with zoom and visibility controls
- Probability simulator for coins, dice, cards, and urn draws
- Transformation visualizer for functions, points, lines, triangles, and circles

All calculations run in the browser. Guest mode is open by default. The workspace in this version stores favorites, recent tools, and saved input snapshots in browser storage; it does not connect to an account or backend service.
