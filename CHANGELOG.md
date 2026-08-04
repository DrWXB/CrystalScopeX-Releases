# CrystalScopeX changelog

**Last updated:** 2026-08-04

## 0.3.3 — 2026-08-04

- Fixed bugs that affected core functionality.
- Redesigned the feature bar and menus.
- Improved application performance.

## 0.3.2 — 2026-08-02 — stable 0.3 generation

### Added

- A separate 3D molecular editing draft for adding, replacing, moving, and
  deleting atoms; creating and removing bonds; undo and redo; and explicit XYZ
  export without changing the opened source.
- Automatic common-framework structure alignment plus atom-guided alignment
  for symmetric, ambiguous, or scientifically selected correspondences.
- Atom-defined planes and atom-to-plane, line-to-plane, and plane-to-plane
  measurements alongside distance, angle, and dihedral tools.
- A structured SHELXL INS/RES instruction workspace with line numbers, semantic
  spacing, syntax styling, PART visibility controls, and optional refinement
  through a user-supplied local SHELXL executable.
- Optional local calculation preparation and result review through a
  user-supplied compatible ORCA installation.
- Gaussian Cube folder import with ordered frontier orbitals, optional Alpha
  and Beta spin channels, a shared numeric isovalue, surface-opacity control,
  and camera-stable orbital switching.
- Live rotation preview with selectable view, projection, angle, speed, axis,
  and direction.
- Complete 4K PNG orbital export, one-pass frontier-orbital presentation
  export, and a current-orbital turntable export in clean HEVC 4K at 120 fps.
- Depth Fade, global hydrogen visibility, and contextual reveal of all atoms
  adjacent to a selected non-hydrogen atom.
- Restoration of useful window, workspace-panel, placement, zoom, and molecular
  view settings between launches.
- Common PDB, PDBx/mmCIF, and bounded SDF reading alongside the established
  CIF, XYZ/Extended XYZ, MOL, INS/RES, and Gaussian Cube workflows.

### Improved

- Molecular lighting, orbital-surface material, depth separation, and the
  visual transition between atoms and bonds.
- Panel-aware Fit and Reset framing so the complete molecule uses the actually
  unobscured canvas.
- Rotation pivots after Fit, Reset, panel changes, and orbital changes so the
  molecule no longer drifts around a stale screen center.
- Tool and panel transitions so changing a scientific operation does not make
  the molecule jump across the viewport.
- Reset motion with a longer, smoother settle and exact final camera state.
- Comparison guidance and status text; completed alignment remains still until
  the user explicitly requests rotation.
- INS/RES readability through crystallographic column structure rather than an
  undifferentiated list of numbers.
- Frontier-orbital ordering, LUMO-first menu presentation, and separate spin
  selection for compatible unrestricted data.
- QuickTime compatibility through an explicit full-frame-rate playback intent
  in both 120-fps orbital movie formats.
- Export organization through a stable per-structure destination and an
  explicit Show Export Folder action. Public installations use
  `Documents/CrystalScopeX Exports` as the visible default root.
- Keyboard navigation, VoiceOver descriptions, Larger Text behavior, Reduce
  Motion behavior, and clear source-unchanged status language.

### Performance and reliability

- Cube folder parsing and surface preparation run as bounded, cancellable
  background work instead of blocking normal molecular interaction.
- Orbital switching preserves the camera and publishes the new surface only
  after its data is ready.
- Batch PNG and movie exporters use fixed cameras, shared scientific settings,
  atomic file replacement, and deterministic naming.
- Molecular fitting uses the visible canvas and stable scene bounds rather than
  a panel-obscured window rectangle.
- Parsing, comparison, editing, camera, rendering, export, calculation, and
  application-state paths have expanded automated regression coverage.

### File, privacy, and third-party boundaries

- Opening structures remains read-only; edits, refinements, calculations,
  images, and videos are separate explicit outputs.
- Public release artifacts contain no private structures, calculations, source
  code, development history, test data, local path, or source revision.
- CrystalScopeX contains no telemetry, advertising, analytics, or cloud-account
  requirement.
- ORCA and SHELXL remain optional, separately licensed, user-supplied local
  programs and are not bundled or redistributed.

## 0.2.2 — 2026-07-29 — final stable 0.2 generation

- Native Apple-silicon molecular and crystal visualization.
- Ball-and-stick, space-filling, wireframe, unit-cell, symmetry, occupancy,
  disorder, label, and thermal-ellipsoid presentation.
- Distance, angle, and dihedral measurements.
- XYZ and Extended XYZ trajectory playback.
- Read-only Gaussian Cube isosurfaces and high-resolution scientific PNG
  export.
