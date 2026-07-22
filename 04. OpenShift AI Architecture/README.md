# OpenShift AI Architecture — Corporate L3 Training Pack

This pack contains 25 independently usable Markdown guides, numbered exactly according to the requested topic order.

## Baseline

- Production baseline: Red Hat OpenShift AI Self-Managed 3.4.2 GA as checked on 2026-07-21.
- OpenShift AI 3.5 Early Access is treated as evaluation-only, not production-supported.
- Every custom resource example includes a version-validation warning. Run `oc api-resources`, `oc explain`, and `oc apply --dry-run=server` on the actual cluster.

## Files

| No. | Topic | Lines | File |
|---:|---|---:|---|
| 01 | OpenShift AI dashboard | 3,840 | `01. OpenShift AI dashboard.md` |
| 02 | Data science projects | 3,842 | `02. Data science projects.md` |
| 03 | Workbench architecture | 3,842 | `03. Workbench architecture.md` |
| 04 | Notebook controller | 3,847 | `04. Notebook controller.md` |
| 05 | Pipeline server | 3,841 | `05. Pipeline server.md` |
| 06 | Kubeflow Pipelines integration | 3,838 | `06. Kubeflow Pipelines integration.md` |
| 07 | Model serving platform | 3,844 | `07. Model serving platform.md` |
| 08 | KServe architecture | 3,843 | `08. KServe architecture.md` |
| 09 | ServingRuntime | 3,839 | `09. ServingRuntime.md` |
| 10 | InferenceService | 3,842 | `10. InferenceService.md` |
| 11 | Model registry | 3,839 | `11. Model registry.md` |
| 12 | TrustyAI | 3,838 | `12. TrustyAI.md` |
| 13 | Object storage integration | 3,840 | `13. Object storage integration.md` |
| 14 | S3-compatible storage | 3,838 | `14. S3-compatible storage.md` |
| 15 | OpenShift Data Foundation integration | 3,839 | `15. OpenShift Data Foundation integration.md` |
| 16 | GPU operator integration | 3,838 | `16. GPU operator integration.md` |
| 17 | Node Feature Discovery integration | 3,838 | `17. Node Feature Discovery integration.md` |
| 18 | Monitoring integration | 3,840 | `18. Monitoring integration.md` |
| 19 | OpenShift console integration | 3,847 | `19. OpenShift console integration.md` |
| 20 | OpenShift authentication integration | 3,838 | `20. OpenShift authentication integration.md` |
| 21 | Multi-tenant architecture | 3,842 | `21. Multi-tenant architecture.md` |
| 22 | Control plane/data plane separation | 3,842 | `22. Control plane／data plane separation.md` |
| 23 | Production architecture patterns | 3,843 | `23. Production architecture patterns.md` |
| 24 | HA architecture | 3,847 | `24. HA architecture.md` |
| 25 | DR architecture | 3,840 | `25. DR architecture.md` |

## Recommended study order

1. Start with dashboard, projects, workbench, notebook controller, and pipelines.
2. Continue with model serving, KServe, ServingRuntime, InferenceService, registry, and TrustyAI.
3. Study storage, ODF, GPU, NFD, monitoring, console, and authentication integrations.
4. Finish with multi-tenancy, control/data planes, production patterns, HA, and DR.

## Validation

- All 25 topic files contain at least 3,600 lines.
- `MANIFEST.csv` contains line count, byte size, and SHA-256 for every file.
- The material is designed as a study and lab workbook; validate commands and CRD fields against the installed product release.
