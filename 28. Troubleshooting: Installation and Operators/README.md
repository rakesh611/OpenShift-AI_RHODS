# Troubleshooting: Installation and Operators — Red Hat OpenShift AI Corporate L3

This bundle contains 20 separate Corporate L3 Markdown guides.

Baseline used for terminology:

- Red Hat OpenShift Container Platform 4.19
- Red Hat OpenShift AI Self-Managed 3.5
- OLM Classic resources where applicable

Always validate the exact supported product version, channel, architecture, platform, and dependent Operator versions before applying a production change.

## Files

| # | Topic | Lines | File |
|---:|---|---:|---|
| 01 | OpenShift AI Operator not installing | 4309 | [01. OpenShift AI Operator not installing.md](<01. OpenShift AI Operator not installing.md>) |
| 02 | Subscription issue | 4309 | [02. Subscription issue.md](<02. Subscription issue.md>) |
| 03 | InstallPlan issue | 4309 | [03. InstallPlan issue.md](<03. InstallPlan issue.md>) |
| 04 | CSV stuck Pending | 4314 | [04. CSV stuck Pending.md](<04. CSV stuck Pending.md>) |
| 05 | Operator degraded | 4313 | [05. Operator degraded.md](<05. Operator degraded.md>) |
| 06 | DataScienceCluster not ready | 4311 | [06. DataScienceCluster not ready.md](<06. DataScienceCluster not ready.md>) |
| 07 | DSCInitialization issue | 4313 | [07. DSCInitialization issue.md](<07. DSCInitialization issue.md>) |
| 08 | Component not enabled | 4314 | [08. Component not enabled.md](<08. Component not enabled.md>) |
| 09 | Dashboard pod failure | 4313 | [09. Dashboard pod failure.md](<09. Dashboard pod failure.md>) |
| 10 | Dashboard route issue | 4314 | [10. Dashboard route issue.md](<10. Dashboard route issue.md>) |
| 11 | Certificate issue | 4313 | [11. Certificate issue.md](<11. Certificate issue.md>) |
| 12 | Proxy issue | 4315 | [12. Proxy issue.md](<12. Proxy issue.md>) |
| 13 | Image pull issue | 4314 | [13. Image pull issue.md](<13. Image pull issue.md>) |
| 14 | Registry authentication issue | 4315 | [14. Registry authentication issue.md](<14. Registry authentication issue.md>) |
| 15 | Disconnected install issue | 4312 | [15. Disconnected install issue.md](<15. Disconnected install issue.md>) |
| 16 | Namespace missing | 4315 | [16. Namespace missing.md](<16. Namespace missing.md>) |
| 17 | RBAC issue | 4317 | [17. RBAC issue.md](<17. RBAC issue.md>) |
| 18 | CRD missing | 4314 | [18. CRD missing.md](<18. CRD missing.md>) |
| 19 | Version mismatch | 4314 | [19. Version mismatch.md](<19. Version mismatch.md>) |
| 20 | Upgrade failure | 4312 | [20. Upgrade failure.md](<20. Upgrade failure.md>) |

## Included supporting files

- `manifest.json` — actual line counts, byte sizes, and SHA-256 checksums.
- `line-count-report.csv` — spreadsheet-friendly verification report.

## Safety

- Collect evidence and export YAML before mutation.
- Do not delete OpenShift AI CRDs as a failure-injection exercise.
- Do not permanently disable TLS verification.
- Redact credentials, bearer tokens, pull-secret contents, and private keys.
- Red Hat documentation and support guidance take precedence for version-specific recovery actions.
