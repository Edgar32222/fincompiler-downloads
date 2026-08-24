# FinCompiler for Windows

FinCompiler is a local-first finance close assistant for turning messy Excel and CSV exports into reviewable reconciliations and management reporting.

This repository is the official public download and feedback page. The application source code and user data are not stored here.

## Download

Download the latest Windows x64 portable build:

[FinCompiler 0.6.0 alpha 1](https://github.com/Edgar32222/fincompiler-downloads/releases/download/v0.6.0-alpha.1/FinCompiler-0.6.0-alpha.1-windows-x64-portable.zip)

SHA-256:

```text
BAF3D305B480524DE39D5E4A664B4A852B8580937F4BD6F9A1DFC7FFDFA6C220
```

## Start in three steps

1. Download and extract the full ZIP file.
2. Double-click `FinCompiler.exe`. Python and administrator access are not required.
3. Keep the small FinCompiler control window open while using the browser interface. Close it when finished.

Start with the included synthetic demo before using your own files.

## What the alpha can do

- Import Excel and CSV exports for Sales, Trial Balance, Budget, OPEX, AR, Inventory and Cost.
- Require human review for low-confidence or ambiguous mappings.
- Remember approved mappings and detect schema drift in later periods.
- Trace reported values back to file, sheet, source field and calculation chain.
- Investigate Sales-to-GL differences down to candidate records and reasons.
- Calculate Budget vs Actual and price-volume-mix drivers deterministically.
- Resolve currencies and cache cited exchange-rate evidence while keeping the finance calculations deterministic.
- Create a reviewable Management Pack and exception list.

## Privacy and safety

FinCompiler runs on your computer. Uploaded files, mapping memory, rate cache and outputs are written to the `FinCompiler Data` folder next to the executable. FinCompiler does not upload these files to a FinCompiler server.

This build is an unsigned private alpha. Windows SmartScreen may show a warning. Verify that the filename and SHA-256 match this page before running it. Do not use sensitive production data for the first test; use synthetic or anonymized data.

Read the [privacy notes](PRIVACY.md) and [security guidance](SECURITY.md) before testing.

## Alpha limits

FinCompiler is decision-support software, not an accounting system of record. Finance review remains required. It does not post journals or silently force unreconciled numbers to balance.

The current alpha supports Windows x64 and English finance workflows. ERP-specific connectors, code signing and enterprise controls are still in development.

## Feedback

- [Report a problem](https://github.com/Edgar32222/fincompiler-downloads/issues/new?template=bug-report.yml)
- [Share workflow feedback](https://github.com/Edgar32222/fincompiler-downloads/issues/new?template=workflow-feedback.yml)

Please remove company names, customer details, account numbers and financial values before attaching screenshots or examples.

Copyright 2026 FinCompiler. All rights reserved. Evaluation use only during the alpha.
