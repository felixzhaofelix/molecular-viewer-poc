# Molecular Research Lab — 3Dmol.js POC

An interactive, browser-based 3D molecular structure viewer hosted on GitHub Pages.

This proof of concept uses **PDB 1YCR** (MDM2 bound to a p53 peptide) and [3Dmol.js](https://3dmol.org/) to display chain A as a cartoon with a translucent surface and chain B as sticks.

## Deploy

Go to **Settings → Pages → Build and deployment → Deploy from a branch**, choose **main** and **/(root)**, then save.

Site URL: https://felixzhaofelix.github.io/molecular-viewer-poc/

## Use

Open `index.html` in a browser with internet access. 3Dmol.js is loaded from its public CDN and the molecular coordinates from the public PDB service. Use your mouse/touchpad or touch gestures to rotate and zoom.

## Scientific note

PDB 1YCR is a **static molecular structure**, not a reaction animation. To animate a scientifically meaningful reaction, add structures/coordinates for successive frames of a calculated or measured reaction pathway, with an explanation of their provenance.

Only publish research data that your collaborator approves for public release. Cite the original structure: https://www.rcsb.org/structure/1YCR.
