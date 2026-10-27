# Cerberus USB Flasher

**[Open the flasher](https://463n7.github.io/Cerberus-Flasher/)**

Install Cerberus Sentinel on the production board's ESP32-S3 and onboard ESP32-C5 using a USB data cable and desktop Chrome or Edge.

The guided installation prepares a temporary USB bridge, installs the C5 radio firmware, installs the S3 touchscreen firmware, then checks startup. It verifies firmware downloads and processor identity and provides BOOT/RESET recovery instructions.

## Status

**[Cerberus Sentinel v1.0.0](https://github.com/463N7/Cerberus-Flasher/releases/tag/v1.0.0)** is the first production release, approved by the owner after successful testing of the existing feature build on 2026-10-27. The matched S3, C5, and bridge images are versioned 1.0.0.

## Privacy

Board identifiers and installation progress stay in browser storage. Downloaded reports include board MAC addresses and diagnostic output; share them only when intended. Starting a new board clears the previous board's progress and log. The installer does not upload device reports.

## Repository contents

This repository contains the compiled website, firmware downloads, and required third-party notices. Firmware and installer development source are maintained separately in a private repository. The browser code and downloadable binaries here are public.

GitHub Pages publishes the root of `main`. Keep `.nojekyll` and `.gitattributes` when updating the compiled files. The latter preserves the exact bytes covered by release checksums. Preserve a future `CNAME` file if a custom domain is added.

Release information is in [firmware/latest.json](firmware/latest.json). Third-party notices are in [notices.txt](notices.txt) and alongside each firmware release.
