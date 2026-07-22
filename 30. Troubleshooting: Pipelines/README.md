# Red Hat OpenShift AI — Troubleshooting: Pipelines — Corporate L3

This package contains 20 detailed Markdown runbooks.

## Package characteristics

- Numbered filenames exactly follow the requested topic order.
- Every topic file contains between 3,500 and 5,000 lines.
- Each file includes architecture, build-from-scratch lab, failure injection, diagnosis, remediation, validation, monitoring, incident simulations, interview questions, and hands-on exercises.
- Examples are version-aware and use discovery commands instead of assuming fixed generated pod names.
- Destructive tests are intended only for disposable projects.

## Files

- `01. Pipeline server not created.md` — 4,437 lines
- `02. Pipeline UI unavailable.md` — 4,446 lines
- `03. Pipeline run failed.md` — 4,446 lines
- `04. Pipeline pod Pending.md` — 4,446 lines
- `05. Pipeline component failed.md` — 4,446 lines
- `06. Pipeline image pull failed.md` — 4,446 lines
- `07. Pipeline artifact upload failed.md` — 4,446 lines
- `08. S3 bucket access denied.md` — 4,446 lines
- `09. Invalid S3 credentials.md` — 4,446 lines
- `10. Pipeline logs missing.md` — 4,446 lines
- `11. Pipeline run stuck.md` — 4,446 lines
- `12. Recurring run not triggered.md` — 4,446 lines
- `13. Pipeline permission denied.md` — 4,455 lines
- `14. Service account issue.md` — 4,446 lines
- `15. PVC issue.md` — 4,455 lines
- `16. Object storage latency.md` — 4,464 lines
- `17. Pipeline metadata issue.md` — 4,437 lines
- `18. Pipeline cleanup issue.md` — 4,464 lines
- `19. Pipeline YAML error.md` — 4,446 lines
- `20. KFP SDK compatibility issue.md` — 4,446 lines

## Recommended study sequence

1. Build the common lab from the first runbook.
2. Establish a healthy canary baseline.
3. Study one failure domain at a time.
4. Perform only one failure injection per exercise.
5. Capture evidence before remediation.
6. Write a root-cause statement and prevention action after every lab.

## Security

Never place decoded Secrets, bearer tokens, browser cookies, private keys, or presigned URLs in evidence bundles.
