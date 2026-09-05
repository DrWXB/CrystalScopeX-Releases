# Third-party interoperability notices

CrystalScopeX is independently authored software. The CrystalScopeX binary
does not contain the third-party scientific programs discussed below.

## CifVis publication drawing reference (no incorporated code)

The native cutaway ellipsoid drawing and difference-density line presentation
were informed by a read-only review of CifVis by Paul Niklas Ruth, commit
`9e055791d25bbe98c52f32e8ba0ebf80618f26e4`. CifVis is licensed under Mozilla
Public License 2.0. Its publication drawing conventions are acknowledged here
as design provenance; no CifVis or Three.js source, shaders, artwork, web view,
or runtime dependency is incorporated. CrystalScopeX implements the geometry,
depth masking, CoreGraphics export and Metal line rendering independently.

- Project: [CifVis](https://github.com/Niolon/cifvis)
- License: [Mozilla Public License 2.0](https://github.com/Niolon/cifvis/blob/9e055791d25bbe98c52f32e8ba0ebf80618f26e4/LICENSE.md)
- Drawing reference: [Publication drawing](https://github.com/Niolon/cifvis/blob/9e055791d25bbe98c52f32e8ba0ebf80618f26e4/docs/gallery/publication-2d.md)

## ORCA

CrystalScopeX can act as an independent graphical front end to an ORCA
installation that the user has already obtained and installed.

- ORCA and its documentation are separate third-party products governed by
  their own license terms.
- No ORCA executable, library, installer, documentation, logo, or other ORCA
  file is contained in or redistributed with CrystalScopeX.
- CrystalScopeX does not obtain ORCA on the user's behalf or make ORCA
  accessible to another person.
- Each user is responsible for obtaining an appropriate ORCA license and
  satisfying applicable permitted-use and citation requirements.
- A CrystalScopeX license or download grants no license to ORCA.

CrystalScopeX is not developed, endorsed, sponsored, or supported by the ORCA
developers or their affiliated institutions. ORCA names and marks belong to
their respective owners. See [ORCA-NOTICE.md](ORCA-NOTICE.md) for citations
and official links.

## SHELXL

CrystalScopeX independently supports INS/RES files and compatible refinement
instruction semantics. In the current release, the optional connection for
executing a user-selected SHELXL program and its settings are temporarily
removed. CrystalScopeX does not invoke a SHELXL executable.

- No SHELXL executable, installer, source code, documentation, logo, or other
  SHELXL file is contained in or redistributed with CrystalScopeX.
- Users who obtain or use SHELXL separately must comply with its own license
  and citation requirements.
- A CrystalScopeX license or download grants no license to SHELXL.
- CrystalScopeX is not developed, endorsed, sponsored, or supported by the
  SHELXL authors or distributors.

The official third-party terms control if this summary and those terms ever
differ. This file describes product boundaries and is not legal advice.
