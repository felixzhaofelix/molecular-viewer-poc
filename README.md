# ChemMorph — interactive 3D aromatic transformation POC

[**View live site**](https://felixzhaofelix.github.io/molecular-viewer-poc/)

A lightweight, client-side molecular visualization proof of concept using [3Dmol.js](https://3dmol.org/) and GitHub Pages.

## Demo

A visual comparison between:
- **Fluorobenzene (C₆H₅F)**: a six-membered aromatic ring with a fluorine substituent.
- **4-Chloropyridine (C₅H₄ClN)**: one ring carbon replaced by nitrogen (position 4 relative to chlorine), and the fluorine replaced with chlorine.

The molecular display supports **drag-to-rotate, zoom, play/pause, timeline scrubbing, end-state jump buttons, reset camera, and auto-rotation**.

### Scientific accuracy disclaimer

**This is not a verified chemical reaction or mechanistic animation.** The interpolated color/radius changes are an *illustrative structural morph*. Atoms do not literally change elements in a substitution mechanism. It omits explicit hydrogens, shows schematic aromatic bonding, and does not represent transition states, energetics, reaction conditions, mechanisms, or physically meaningful intermediates.

The chosen transformations are only a stand-in for an incompletely specified research idea. Replace with approved molecular structures, reaction context, and scientifically grounded trajectories before using it to present actual research.

## Technology and deployment

- `index.html`: self-contained site with HTML, CSS, JavaScript, and 3Dmol.js loaded from a public CDN
- No frontend build system or backend
- **GitHub Pages**: Settings → Pages → Deploy from a branch → main → /(root)

## Next steps

Ask the chemist for the exact reactant and product (name, SMILES, SDF, MOL, XYZ), and ideally IRC/NEB/molecular dynamics trajectory coordinates if this is intended as an actual reaction-path animation.

The POC can then be adapted to display the correct molecular structure(s), evidence, and citable research context.
