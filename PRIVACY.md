# Privacy notes

## Local-first processing

FinCompiler is designed to process finance files locally on the user's Windows computer. Uploaded files, mapping memory, cached exchange-rate evidence and generated outputs remain in the `FinCompiler Data` folder next to the application.

The alpha does not require a FinCompiler cloud account and does not upload source workbooks to a FinCompiler-operated server.

## External exchange-rate requests

When online exchange-rate retrieval is enabled, FinCompiler may request public reference-rate data for a currency pair and date. The request should contain the currencies and date required for the rate lookup, not the contents of the user's workbook. Retrieved rate evidence is cached locally for repeatability and review.

## Pilot-data guidance

For the first evaluation, use the included synthetic demo or anonymized exports. Remove company names, personal information, bank details, customer identifiers and commercially sensitive descriptions before sharing examples or issue attachments.

## User control

Users can stop FinCompiler by closing its control window. Local application data can be reviewed in the `FinCompiler Data` folder. Back up any output that must be retained before removing the application or its data folder.

This document describes the current alpha behavior and is not a substitute for an organization's own security, privacy or records-retention review.
