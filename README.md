# Mechanism Lab — stepwise 3D benzene nitration PoC

**[Open the interactive website](https://felixzhaofelix.github.io/molecular-viewer-poc/)**

An educational proof of concept for showing **a chemical mechanism through sequential 3D stages**, instead of morphing one static molecule into another. Built in a single `index.html` using [3Dmol.js](https://3dmol.org/) and hosted by GitHub Pages.

## Demonstration reaction

**Benzene + nitronium ion → nitrobenzene** via electrophilic aromatic substitution (EAS).

The animation has five labeled stages:
1. **Reactants** — benzene, nitronium (NO₂⁺), and water as an illustrative generic base.
2. **Approach** — NO₂⁺ moves toward an aromatic π bond; gold markers indicate electron-pair movement.
3. **σ-complex** — formation of a carbon–nitrogen bond, loss of aromaticity, and a positively charged arenium intermediate.
4. **Deprotonation** — the base accepts the proton; the C–H bond electron pair restores π bonding.
5. **Product** — nitrobenzene and a protonated base are represented.

Controls: Play/pause, timeline scrubbing, direct stage navigation, previous/next, camera reset, model rotation and zoom.

## Important scientific limits

This is a **schematic mechanism visualization**, not a calculated molecular-dynamics trajectory, and not your collaborator's as-yet-unspecified reaction.

- Gold spheres show the approximate *direction of electron-pair flow*. Electrons are **not** modeled as literal classical particles moving along these trajectories.
- Aromatic and resonance bonding is simplified. The σ-complex is resonance-delocalized; the simplified ring representation does not resolve all contributors or formal charges.
- Animated geometries, bond changes and playback timing are illustrative, **not** calculated coordinates or transition states.
- Nitronium is assumed to already be present; its formation from nitric acid and sulfuric acid is not simulated.
- Water appears as a **generic proton-accepting base** to explain the deprotonation step; this does not specify the actual proton acceptor under a particular nitration condition.
- In this example the **ring carbon remains carbon**. A ring hydrogen is replaced by the nitrogen-containing nitro group. An actual **C→N substitution of a ring atom** would be a different transformation and mechanism.
- The model uses simplified atoms and implicit ring hydrogens, and does not imply measured kinetics, energetics, or reaction conditions.

Reference educational mechanism: [University of Calgary — Electrophilic Aromatic Substitution](https://www.chem.ucalgary.ca/courses/353/Carey5th/Ch12/ch12-3.html).

## Publishing to GitHub Pages

Repository **Settings → Pages → Deploy from a branch → main → /(root)**.

There is no build command, backend, or dependency installation. A browser with WebGL and internet access is required for the externally loaded 3Dmol.js library.

## Replacing the example with research

Request her actual **reactant/product structures, elementary steps and intermediates**, and ideally atom mappings and computationally derived geometry frames (e.g. XYZ, SDF, MOL or IRC/NEB output). Encode her stages and annotate uncertain electron-flow assumptions explicitly, with permission and citations.

Keep scientific mechanism claims separate from interpolated visual effects.
