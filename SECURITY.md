# Security guidance

## Verify the download

Only download FinCompiler from this repository's Releases page. For version 0.6.0 alpha 1, the SHA-256 of the ZIP must be:

```text
BAF3D305B480524DE39D5E4A664B4A852B8580937F4BD6F9A1DFC7FFDFA6C220
```

On Windows PowerShell, users can verify it with:

```powershell
Get-FileHash -Algorithm SHA256 .\FinCompiler-0.6.0-alpha.1-windows-x64-portable.zip
```

Do not run the file if the value differs.

## Unsigned alpha

The current executable is not code-signed. Windows SmartScreen or an organization's endpoint policy may warn or block it. Do not weaken organization-wide security controls to run the alpha. Ask the organization's IT or security owner before testing it on a managed device.

## Safe pilot use

- Begin with the included synthetic demo.
- Use anonymized exports for pilot testing.
- Do not treat generated output as an approved journal or statutory report.
- Review exceptions, lineage and reconciliation status before relying on a result.
- Keep the extracted application and `FinCompiler Data` folder in a user-controlled location.

## Report a security concern

Open a GitHub issue containing only non-sensitive reproduction details. Do not post real financial files, credentials, personal data or exploitable details publicly. State that the issue is security-related and request a private follow-up channel.
