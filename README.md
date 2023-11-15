# cross-origin-link

Security assessment for links with cross-origin destinations

According to [«Common Vulnerability Scoring System v3.1: Specification Document»](https://www.first.org/cvss/v3.1/specification-document)

Hypothetical CVSS assessment for browsers that don't add the `rel="noopener"` attribute to links with `target="_blank"` and `href` pointing to a different origin.

_AV: Network (N)_ - The attack can be launched through the network.\
_AC: Low (L)_ - The attack complexity is low as it just requires crafting a malicious link.\
_PR: None (N)_ - No privileges are needed.\
_UI: Required (R)_ - The user must interact with the malicious link.\
_S: Unchanged (U)_ - The vulnerability does not affect other resources.\
_C: None (N)_ - Confidentiality is not directly impacted.\
_I: Low (L)_ - There could be a low impact on integrity if it leads to phishing.\
_A: None (N)_ - Availability is not impacted.

[Overall CVSS Score: 4.3](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:L/PR:N/UI:R/S:U/C:N/I:L/A:N&version=3.1)
