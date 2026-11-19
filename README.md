# sca-vuln-dotnet-nuget

> **WARNING: Intentionally vulnerable.** Test fixture for Software Composition Analysis (SCA) tools.
> Do not deploy. Dependencies are pinned to versions with known CVEs.

**Ecosystem:** NuGet (.NET)

## Expected findings (non-exhaustive)
- Newtonsoft.Json 12.0.1: GHSA-5crp-9r3c-p9vr (DoS)
- System.Text.Encodings.Web 4.5.0: CVE-2021-26701 (RCE)
- Microsoft.AspNetCore.Http 2.1.0: CVE-2020-1045
- System.Net.Http 4.3.0: CVE-2018-8292
- SharpZipLib 1.2.0: CVE-2021-32840 (zip slip)
- log4net 2.0.8: CVE-2018-1285 (XXE)
- System.Data.SqlClient 4.8.0: CVE-2022-41064
