# Installing CrystalScopeX 0.3.2 on macOS

## Before opening the application

1. Review the [CrystalScopeX Academic Use License 1.0](LICENSE.md).
   Non-commercial academic use is permitted without a license fee; commercial
   use requires a separate written license.
2. Download `CrystalScopeX-0.3.2-macOS-arm64.dmg` only from the official
   CrystalScopeX release.
3. Compare the downloaded file's SHA-256 checksum with `SHA256SUMS.txt`.
4. Open the disk image and drag `CrystalScopeX.app` to the Applications
   shortcut.

## First launch

CrystalScopeX 0.3.2 is ad-hoc code-signed and has not been notarized by Apple.
The first ordinary launch is therefore expected to be blocked by Gatekeeper.

After that blocked launch:

1. Choose **Apple menu → System Settings**.
2. Select **Privacy & Security**.
3. Scroll down to **Security**.
4. Confirm that the blocked application is named **CrystalScopeX**.
5. Click **Open Anyway**, authenticate with the Mac login password, and
   confirm **Open**.

Apple makes the **Open Anyway** control available for approximately one hour
after the blocked launch attempt. macOS then stores an exception for that
specific application copy.

### Finder shortcut, when available

Some Macs also allow the same per-application exception from Finder:

1. In **Applications**, Control-click `CrystalScopeX.app`.
2. Choose **Open**, then confirm **Open** if macOS offers the confirmation.

If Finder does not offer that confirmation or still blocks the application,
use the **Privacy & Security → Open Anyway** procedure above. A Mac managed by
an organization may disable the Finder shortcut.

Do not disable Gatekeeper globally and do not run Terminal commands copied
from third-party sites. If the filename, source, or checksum does not match the
official release, do not override the warning.

Apple's current instructions:
[Open a Mac app from an unknown developer](https://support.apple.com/guide/mac-help/mh40616/mac)

## What the warning means

This release was produced without a paid Apple Developer ID membership.
Consequently, Apple has not notarized or reviewed this release and macOS cannot
establish an Apple-registered developer identity for it. The warning is
expected for this distribution method; it is not presented as proof that the
application is either safe or malicious.
