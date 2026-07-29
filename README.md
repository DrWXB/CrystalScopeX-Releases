# CrystalScopeX 0.2.2

**English** | [Deutsch](README.de.md)

<p align="center">
  <a href="https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.2.2/CrystalScopeX-0.2.2-macOS-arm64.dmg">
    <img src="media/CrystalScopeX-icon.png" alt="CrystalScopeX app icon" width="144">
  </a>
</p>

<p align="center">
  <strong><a href="https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.2.2/CrystalScopeX-0.2.2-macOS-arm64.dmg">Download CrystalScopeX 0.2.2 for Apple silicon (.dmg)</a></strong>
</p>

Welcome to CrystalScopeX — a native macOS app for exploring crystal structures
and molecules on Apple silicon.

CrystalScopeX opens CIF, XYZ, Extended XYZ, MOL, and SHELXL RES/INS files,
then brings them to life in an interactive 3D workspace. You can inspect
crystal geometry, thermal ellipsoids, orbital surfaces, trajectories, and
measurements, or export high-resolution scientific images. Your imported
structures remain read-only throughout.

Version **0.2.2 (build 7)** is the final stable release of the 0.2 generation.

## Take a look: 4K development preview

[![CrystalScopeX molecular visualization development preview](media/CrystalScopeX-0.2.2-demo-preview.png)](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.2.2/CrystalScopeX-0.2.2-demo-4K.mp4)

**[Watch or download the original 4K development-preview MP4](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.2.2/CrystalScopeX-0.2.2-demo-4K.mp4)**

> **A note about the video:** It offers an early look at functionality that is
> still under active development. These preview features are not part of the
> stable 0.2.2 feature set and are not promised as part of this release.

The video is provided in its original 3840 × 2160 HEVC form without
recompression or resolution reduction.

## Download and get started

Download
**[CrystalScopeX 0.2.2 for Apple silicon](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.2.2/CrystalScopeX-0.2.2-macOS-arm64.dmg)**
from the `v0.2.2` release. Before opening the disk image, compare it with the
published [SHA-256 checksums](SHA256SUMS.txt).

You will need:

- Apple silicon Mac
- macOS 26.0 or later
- Metal-capable GPU

## A quick note before the first launch

CrystalScopeX 0.2.2 is ad-hoc code-signed, but it is **not signed with an Apple
Developer ID and is not notarized by Apple**. Because of this, macOS is
expected to block the first ordinary launch.

If your download came from this repository and its SHA-256 checksum matches,
the [installation guide](INSTALLATION.md) walks you through the standard
**Privacy & Security → Open Anyway** procedure step by step.

There is no need to disable Gatekeeper globally or run Terminal commands from
third-party sites.

## What you can explore

- Native, GPU-accelerated molecular and crystal visualization.
- Ball-and-stick, space-filling, and wireframe representations.
- Unit cells, symmetry, occupancy, disorder, labels, and thermal ellipsoids.
- Distance, angle, and dihedral measurements.
- XYZ and Extended XYZ trajectory playback.
- Read-only Gaussian Cube import with positive and negative orbital
  isosurfaces.
- High-resolution scientific PNG export, including transparent backgrounds.
- Keyboard navigation, VoiceOver support, Larger Text, and Reduce Motion.
- Local-first operation without telemetry, advertising, analytics, or a cloud
  account.

## File-format support

| Format | Stable 0.2.2 support |
| --- | --- |
| CIF | CIF 1.1 and common CIF 2.0 syntax, cells, symmetry, occupancy, disorder, anisotropic displacement data, and periodic geometry bonds |
| XYZ | Standard XYZ structures and concatenated trajectories |
| Extended XYZ | Lattice, properties, periodicity, energy, forces, velocities, charges, magnetic moments, and additional typed properties |
| MDL Molfile | Single-structure V2000 and V3000 coordinates, bond orders, charges, and identifiers |
| SHELXL RES/INS | Cell, lattice, symmetry, SFAC, FVAR/PART occupancy, coordinates, and isotropic or anisotropic displacement data |
| Gaussian Cube | Read-only calculation asset for scalar-field and molecular-orbital isosurfaces |

SHELXL files are interpreted for visualization only. CrystalScopeX does not
execute refinement instructions or write changes back to `.res` or `.ins`
files.

## Your files stay yours

- Imported structure files are never overwritten.
- File integrity is checked before and after opening.
- Recent files use security-scoped, read-only macOS bookmarks.
- Generated calculation data and exported images have separate ownership from
  the source structure.
- No local path, account identifier, or filesystem location is embedded in
  exported PNG metadata.
- CrystalScopeX contains no telemetry or network client.

## Using CrystalScopeX with ORCA

If you already use ORCA, CrystalScopeX can connect to a compatible installation
that you select locally. ORCA is not included, and CrystalScopeX does not
download, install, copy, modify, sublicense, or redistribute it.

To use the optional calculation workflow, obtain ORCA independently from its
official source, accept its license, and choose the local installation from
within CrystalScopeX.

CrystalScopeX is an independent third-party application. It is not developed,
endorsed, sponsored, or supported by the ORCA developers or their affiliated
institutions. See [ORCA-NOTICE.md](ORCA-NOTICE.md).

## Release information

- [Installation guide](INSTALLATION.md)
- [SHA-256 checksums](SHA256SUMS.txt)
- [ORCA notice](ORCA-NOTICE.md)
- [Academic-use license](LICENSE.md)

If you find CrystalScopeX useful in your research, please cite the
[CrystalScopeX GitHub repository](https://github.com/DrWXB/CrystalScopeX-Releases).

This small repository is intentionally focused on downloads and end-user
documentation. Source code, tests, development tools, and private development
history are kept separately.

## License

CrystalScopeX 0.2.2 is distributed under the
[CrystalScopeX Academic Use License 1.0](LICENSE.md):

- Non-commercial academic research, teaching, and education are permitted
  without a license fee.
- Commercial use requires a separate written commercial license.
- Modification, reverse engineering, and redistribution are not permitted
  without prior written permission, except where applicable law does not allow
  such a restriction.

This is proprietary academic-use software, not open-source software. The
license grants no rights to ORCA or other third-party software or materials.

## Competing interests

The developer declares no competing financial interest.

## Scientific provenance

The structural model visualized in the MP4 was derived from the crystal
structure reported by Rösch et al.<sup>1</sup> The molecular orbitals shown in
the video were calculated by CrystalScopeX through its integrated calculation
workflow and rendered by CrystalScopeX; the orbital data were not taken from
the cited publication.

- **DOI:** [10.1038/s41586-021-03401-w](https://doi.org/10.1038/s41586-021-03401-w)
- **Article link:** [Strongly reducing magnesium(0) complexes](https://www.nature.com/articles/s41586-021-03401-w)

**Reference**

1. Rösch, B.; Gentner, T. X.; Eyselein, J.; Langer, J.; Elsen, H.; Harder, S.
   Strongly Reducing Magnesium(0) Complexes. *Nature* **2021**, *592*, 717–721.
   DOI: [10.1038/s41586-021-03401-w](https://doi.org/10.1038/s41586-021-03401-w).
