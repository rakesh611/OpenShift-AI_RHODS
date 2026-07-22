# Production Design and Architecture for Red Hat OpenShift AI

Corporate L3 / senior architect learning pack for professionals with approximately 10+ years of infrastructure, OpenShift, DevOps, SRE, security, storage, and networking experience.

## Baseline

- Red Hat OpenShift AI Self-Managed 3.5
- OpenShift Container Platform 4.22
- Red Hat Advanced Cluster Management 2.15 where multicluster management is discussed
- Always verify the exact supported configuration for the installed release before production implementation.

## Guide inventory

| # | Topic | Lines | File |
|---:|---|---:|---|
| 01 | Enterprise AI platform design | 5,606 | [01. Enterprise AI platform design.md](01.%20Enterprise%20AI%20platform%20design.md) |
| 02 | Single-cluster design | 5,606 | [02. Single-cluster design.md](02.%20Single-cluster%20design.md) |
| 03 | Multi-cluster design | 5,606 | [03. Multi-cluster design.md](03.%20Multi-cluster%20design.md) |
| 04 | Hub-spoke architecture | 5,606 | [04. Hub-spoke architecture.md](04.%20Hub-spoke%20architecture.md) |
| 05 | Dev-test-prod architecture | 5,606 | [05. Dev-test-prod architecture.md](05.%20Dev-test-prod%20architecture.md) |
| 06 | GPU node pool design | 5,606 | [06. GPU node pool design.md](06.%20GPU%20node%20pool%20design.md) |
| 07 | Storage architecture | 5,606 | [07. Storage architecture.md](07.%20Storage%20architecture.md) |
| 08 | Object storage architecture | 5,606 | [08. Object storage architecture.md](08.%20Object%20storage%20architecture.md) |
| 09 | Network architecture | 5,606 | [09. Network architecture.md](09.%20Network%20architecture.md) |
| 10 | Identity architecture | 5,606 | [10. Identity architecture.md](10.%20Identity%20architecture.md) |
| 11 | Security architecture | 5,606 | [11. Security architecture.md](11.%20Security%20architecture.md) |
| 12 | Monitoring architecture | 5,606 | [12. Monitoring architecture.md](12.%20Monitoring%20architecture.md) |
| 13 | Backup architecture | 5,606 | [13. Backup architecture.md](13.%20Backup%20architecture.md) |
| 14 | DR architecture | 5,606 | [14. DR architecture.md](14.%20DR%20architecture.md) |
| 15 | Cost model | 5,606 | [15. Cost model.md](15.%20Cost%20model.md) |
| 16 | Capacity model | 5,606 | [16. Capacity model.md](16.%20Capacity%20model.md) |
| 17 | Sizing model | 5,606 | [17. Sizing model.md](17.%20Sizing%20model.md) |
| 18 | Tenant model | 5,606 | [18. Tenant model.md](18.%20Tenant%20model.md) |
| 19 | Chargeback-showback | 5,606 | [19. Chargeback-showback.md](19.%20Chargeback-showback.md) |
| 20 | Platform ownership model | 5,606 | [20. Platform ownership model.md](20.%20Platform%20ownership%20model.md) |
| 21 | Data science onboarding model | 5,606 | [21. Data science onboarding model.md](21.%20Data%20science%20onboarding%20model.md) |
| 22 | Shared service model | 5,606 | [22. Shared service model.md](22.%20Shared%20service%20model.md) |
| 23 | Regulated environment design | 5,606 | [23. Regulated environment design.md](23.%20Regulated%20environment%20design.md) |
| 24 | Disconnected environment design | 5,606 | [24. Disconnected environment design.md](24.%20Disconnected%20environment%20design.md) |
| 25 | High availability design | 5,606 | [25. High availability design.md](25.%20High%20availability%20design.md) |

Total topic files: 25
Total topic lines: 140,150

## Usage

1. Read the enterprise design first, then single-cluster or multi-cluster patterns.
2. Complete the requirements and ADR sections using your organization’s actual evidence.
3. Run labs only in a non-production environment.
4. Convert accepted decisions into GitOps repositories, policies, dashboards, alerts, backup schedules, and runbooks.
5. Revalidate after every significant OpenShift AI or OpenShift Container Platform upgrade.
