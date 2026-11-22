# Newt releases

**New releases, the install page and new issues are now at
[VargasDevelopment/newt](https://github.com/VargasDevelopment/newt).** Newt's
source is public there, under the MIT license.

- Latest release: <https://github.com/VargasDevelopment/newt/releases/latest>
- Install page: <https://vargasdevelopment.github.io/newt/>
- Report a problem: <https://github.com/VargasDevelopment/newt/issues>

This repository keeps the releases up to v0.2.0, the last one published here.
A Newt that still reads updates from here finds v0.2.0, installs it, and from
then on reads VargasDevelopment/newt. Nothing new is published here.

## Source for these releases

Each release here offers its complete source on request. That offer stands for
at least three years: open an issue in this repository, naming the release
version and build ID. Issues stay open for that.

## What a release contains

- `newt.bin`: the firmware image.
- `newt.manifest`: its version, build ID, size and SHA-256.
- `NOTICES.txt`: the third-party software and fonts it includes, with their
  licenses.

Newt checks the image against its manifest before it installs anything, and
keeps the running version if a check fails.
