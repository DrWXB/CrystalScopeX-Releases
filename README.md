# CrystalScopeX 0.3.5

**English** | [Deutsch](README.de.md)

<p align="center">
  <a href="https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.5/CrystalScopeX-0.3.5-macOS-arm64.dmg">
    <img src="media/CrystalScopeX-icon.png" alt="CrystalScopeX app icon" width="144">
  </a>
</p>

<p align="center">
  <strong><a href="https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.5/CrystalScopeX-0.3.5-macOS-arm64.dmg">Download CrystalScopeX 0.3.5 for macOS arm64</a></strong>
</p>

CrystalScopeX is a native scientific workspace for crystal structures and
molecular data. It presents complete crystallographic models, including ions,
solvent molecules, symmetry-generated components, disorder, and anisotropic
displacement parameters, without rewriting the source file. Interactive 3D
inspection, measurement, structure editing, refinement instructions, and
publication-oriented output share one focused interface.

## Installation

Version **0.3.5 (build 8)** targets arm64 systems running macOS 26.0 or later
with Metal support.

Download the DMG from the [v0.3.5 release](https://github.com/DrWXB/CrystalScopeX-Releases/releases/tag/v0.3.5)
and verify its [SHA-256 checksum](SHA256SUMS.txt).

This build is ad-hoc code-signed, but it is **not Developer ID-signed or
notarized**. Follow the [installation guide](INSTALLATION.md) for the standard
**Privacy & Security → Open Anyway** procedure. Do not disable Gatekeeper
globally.

## Demo

[![CrystalScopeX demo](media/CrystalScopeX-0.3.2-Mg0-orbital-sequence-preview.png)](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.2/CrystalScopeX-0.3.2-Mg0-orbital-sequence-4K120.mp4)

**[Watch or download the 4K/120-fps demo video](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.2/CrystalScopeX-0.3.2-Mg0-orbital-sequence-4K120.mp4)**

## Developer log 0.3.5

- Added optional fixed 16-point labels for non-hydrogen atoms, synchronized with
  the molecular camera for stable high-refresh interaction.
- Kept completed measurement records in the measurement inspector while showing their canvas
  overlays only during Measurement mode, with exact deletion controls.
- Renamed the refinement action to `Refine` while preserving its existing
  function, icon, and position.

## Release information

- [Changelog](CHANGELOG.md)
- [Installation guide](INSTALLATION.md)
- [Third-party notices](THIRD-PARTY-NOTICES.md)
- [License](LICENSE.md)

ORCA and SHELXL are optional, separately licensed, user-supplied programs.
They are not included in CrystalScopeX. This public repository contains release
materials only; private source code, research data, and local development paths
are not published.

## Scientific provenance

The Mg0 example presented above uses a structural model derived from the
crystal structure reported by Rösch et al.<sup>1</sup> Its molecular orbitals
were calculated through the local CrystalScopeX workflow and rendered by
CrystalScopeX. The orbital data were not taken from the cited publication.

- **DOI:** [10.1038/s41586-021-03401-w](https://doi.org/10.1038/s41586-021-03401-w)
- **Article:** [Strongly reducing magnesium(0) complexes](https://www.nature.com/articles/s41586-021-03401-w)

**References**

1. Rösch, B.; Gentner, T. X.; Eyselein, J.; Langer, J.; Elsen, H.; Harder, S.
   Strongly Reducing Magnesium(0) Complexes. *Nature* **2021**, *592*, 717–721.
   DOI: [10.1038/s41586-021-03401-w](https://doi.org/10.1038/s41586-021-03401-w).
2. Neese, F. The ORCA Program System. *WIREs Comput. Mol. Sci.* **2012**, *2*,
   73–78. DOI: [10.1002/wcms.81](https://doi.org/10.1002/wcms.81).
3. Neese, F. Software Update: The ORCA Program System, Version 6.0.
   *WIREs Comput. Mol. Sci.* **2025**, *15* (2), e70019. DOI:
   [10.1002/wcms.70019](https://doi.org/10.1002/wcms.70019).
