# VP Studio - releases

Installers for **VP Studio**, the variable-data print suite for TNR Developments VP series inkjet
printers.

- `update.json` is the update feed. Installed copies of VP Studio read it to find out whether a
  newer version exists. It is written automatically when a release is published.
- Each release has one asset, `VpStudio-Setup.exe`, and the SHA-256 in `update.json` is checked
  by VP Studio before an update is installed.

This repository holds published builds only - no source code.

TNR Developments, LLC - (585) 201-8290 - info@tnrdevelopments.com