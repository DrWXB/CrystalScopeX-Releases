# CrystalScopeX 0.3.6

**English** | [Deutsch](README.de.md)

<p align="center">
  <a href="https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.6/CrystalScopeX-0.3.6-macOS-arm64.dmg">
    <img src="media/CrystalScopeX-icon.png" alt="CrystalScopeX app icon" width="144">
  </a>
</p>

<p align="center">
  <strong><a href="https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.6/CrystalScopeX-0.3.6-macOS-arm64.dmg">Download CrystalScopeX 0.3.6 for macOS arm64</a></strong>
</p>

CrystalScopeX brings crystal structures to life in a fluid, visually rich
scientific workspace. Explore complete crystallographic models—from ions and
solvent molecules to symmetry-generated components, disorder, and anisotropic
displacement parameters—in interactive 3D, then measure, edit, refine, and
shape publication-ready results within one focused interface designed to keep
ideas moving.

## Installation

Version **0.3.6 (build 9)** targets arm64 systems running macOS 26.0 or later
with Metal support.

Download the DMG from the [v0.3.6 release](https://github.com/DrWXB/CrystalScopeX-Releases/releases/tag/v0.3.6)
and verify its [SHA-256 checksum](SHA256SUMS.txt).

This build is ad-hoc code-signed, but it is **not Developer ID-signed or
notarized**. Follow the [installation guide](INSTALLATION.md) for the standard
**Privacy & Security → Open Anyway** procedure. Do not disable Gatekeeper
globally.

## Demo

[![CrystalScopeX demo](media/CrystalScopeX-0.3.2-Demo1-gold-standard-preview.png)](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.2/CrystalScopeX-0.3.2-Demo1-gold-standard-4K120.mp4)

**[Watch or download the 4K/120-fps demo video](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.2/CrystalScopeX-0.3.2-Demo1-gold-standard-4K120.mp4)**

## Developer log 0.3.6

- Added an all-new native arm64 crystal-refinement workflow. Compatibility with
  SHELXL semantics and instructions is under active development; the feature
  remains in beta. The current beta has passed compilation tests across more
  than 5,000 crystallographic cases.

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
