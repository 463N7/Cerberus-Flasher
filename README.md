# Cerberus USB Flasher

**[Open the flasher](https://463n7.github.io/Cerberus-Flasher/)**

Install Cerberus Sentinel on the production board's ESP32-S3 and onboard ESP32-C5 using a USB data cable and desktop Chrome or Edge.

The guided installation prepares a temporary USB bridge, installs the C5 radio firmware, installs the S3 touchscreen firmware, then checks startup. It verifies firmware downloads and processor identity and provides BOOT/RESET recovery instructions.

## Status

Development preview. A complete installation and interrupted-flash recovery must still be validated on a physical Cerberus before production batch use.

## Repository contents

This repository contains the compiled website, firmware downloads, and required third-party notices. Firmware and installer development source are maintained separately in a private repository. The browser code and downloadable binaries here are public.

GitHub Pages publishes the root of `main`. Keep `.nojekyll` and `.gitattributes` when updating the compiled files. The latter preserves the exact bytes covered by release checksums. Preserve a future `CNAME` file if a custom domain is added.

Release information is in [firmware/latest.json](firmware/latest.json). Third-party notices are in [notices.txt](notices.txt) and alongside each firmware release.
