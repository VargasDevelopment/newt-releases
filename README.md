# Newt releases

Release builds of Newt, an e-paper reading firmware for the Xteink X3, built on
[FreeInk](https://github.com/Free-Ink/freeink-sdk).

Newt is in alpha. Its source is not public yet, so this repository holds release
builds only.

## Versions

Versions follow [Semantic Versioning 2.0.0](https://semver.org/). Each release is
tagged `v<version>`, for example `v0.1.0-alpha.2`. While the version starts with
`0.`, any release may change behavior.

## What a release contains

- `newt.bin`: the firmware image.
- `newt.manifest`: its version, build ID, size and SHA-256.

Newt checks the image against its manifest before it installs anything, and keeps
the running version if a check fails.

## Install from the SD card

1. Download `newt.bin` and `newt.manifest` from a release.
2. Copy both files to `/Newt/Update/` on the card.
3. Connect USB power, then open Settings → Update on the X3.

## Licenses

Newt includes third-party software and fonts under their own licenses. Each
release lists them.
