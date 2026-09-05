# CrystalScopeX 0.3.7

**English** | [Deutsch](README.de.md)

<p align="center">
  <a href="https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.7/CrystalScopeX-0.3.7-macOS-arm64.dmg">
    <img src="media/CrystalScopeX-icon.png" alt="CrystalScopeX app icon" width="144">
  </a>
</p>

<p align="center">
  <strong><a href="https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.7/CrystalScopeX-0.3.7-macOS-arm64.dmg">Download CrystalScopeX 0.3.7 for macOS arm64</a></strong>
</p>

<p align="justify">
CrystalScopeX brings crystal structures to life in a fluid, visually rich
scientific workspace. Explore complete crystallo&shy;graphic models in
inter&shy;active 3D, from small molecules to symmetry-generated components,
disorder, twinning, and aniso&shy;tropic displacement para&shy;meters. Then
measure, refine, and shape publication-ready results within one focused
interface designed to keep ideas moving.
</p>

## Installation

<div align="justify">

Version **0.3.7 (build 10)** targets arm64 systems running macOS 26.0 or later with Metal support.

</div>

<div align="justify">

Download the DMG from the [v0.3.7 release](https://github.com/DrWXB/CrystalScopeX-Releases/releases/tag/v0.3.7) and verify its [SHA-256 checksum](SHA256SUMS.txt).

</div>

<div align="justify">

This build is ad-hoc code-signed, but it is **not Developer ID-signed or notarized**. Follow the [installation guide](INSTALLATION.md) for the standard **Privacy & Security → Open Anyway** procedure. Do not disable Gatekeeper globally.

</div>

## Demo

![CrystalScopeX refinement workspace](media/Demo3_png.png)

## Developer log 0.3.7

<div align="justify">

- Prepare Fo−Fc difference-density maps on first load when matching reflections and supported model data are available, without running refinement or changing the input structure. Fresh maps no longer reuse contour metadata from an earlier map.
- Corrected CIF ADP assignment and symmetry-transformed ellipsoid orientation, and refined cutaway ellipsoid and difference-density wireframe presentation.
- Unified Light/Dark Mode across interface surfaces and improved Refine editor contrast while preserving molecular colors.
- Refine now toggles its workspace; Fit and Reset keep panel layout stable. Structure Edit is temporarily hidden. The built-in CRC 2026 refinement workflow remains in beta.

</div>

## Release information

- [Changelog](CHANGELOG.md)
- [Installation guide](INSTALLATION.md)
- [Third-party notices](THIRD-PARTY-NOTICES.md)
- [License](LICENSE.md)

<div align="justify">

ORCA<sup>2,3</sup> and SHELXL (temporarily removed) are optional, separately licensed, user-supplied programs. They are not included in CrystalScopeX. This public reposi&shy;tory contains release materials only; private source code, research data, and local develop&shy;ment paths are not published. The first ARM64-native small-molecule refinement program for Apple silicon will soon be released as a standalone open-source project.

</div>

## References

1. Sheldrick, G. M. A short history of *SHELX*. *Acta Crystallogr. A* **2008**, *64*, 112–122. DOI: [10.1107/S0108767307043930](https://doi.org/10.1107/S0108767307043930).
2. Neese, F. The ORCA program system. *WIREs Comput. Mol. Sci.* **2012**, *2*, 73–78. DOI: [10.1002/wcms.81](https://doi.org/10.1002/wcms.81).
3. Neese, F. Software update: The ORCA program system, version 6.0. *WIREs Comput. Mol. Sci.* **2025**, *15* (2), e70019. DOI: [10.1002/wcms.70019](https://doi.org/10.1002/wcms.70019).
