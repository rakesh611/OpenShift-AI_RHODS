# Red Hat OpenShift AI — Security and Compliance Corporate L3 Course Pack

- **Generated:** 2026-07-21
- **Baseline:** Red Hat OpenShift AI Self-Managed 3.5 and OpenShift Container Platform 4.20
- **Audience:** 10+ year Corporate/L3 platform, security, SRE, DevSecOps, and MLOps engineers
- **Files:** 30 topic guides
- **Format:** Markdown; each topic includes theory, from-scratch project, commands, policy skeletons, validation, troubleshooting, incident response, compliance evidence, and a detailed control catalog.

## Important usage notes

1. Test all manifests in non-production first.
2. Do not create custom SCCs or cluster-wide identity/audit changes unless supported defaults cannot meet a documented requirement.
3. Replace all placeholders and validate API versions against the installed release.
4. The pack includes reusable control-catalog sections because security controls overlap across AI assets; each guide is tailored to its named topic.
5. Official Red Hat documentation is the source of truth for supported behavior.

## Topic index

| # | Topic | Lines | Words | File |
|---:|---|---:|---:|---|
| 01 | OpenShift AI security model | 3,520 | 96,095 | [01. OpenShift AI security model.md](01.%20OpenShift%20AI%20security%20model.md) |
| 02 | OpenShift RBAC | 3,537 | 93,709 | [02. OpenShift RBAC.md](02.%20OpenShift%20RBAC.md) |
| 03 | SCC for AI workloads | 3,536 | 96,938 | [03. SCC for AI workloads.md](03.%20SCC%20for%20AI%20workloads.md) |
| 04 | Service account security | 3,526 | 94,502 | [04. Service account security.md](04.%20Service%20account%20security.md) |
| 05 | Secret management | 3,530 | 93,685 | [05. Secret management.md](05.%20Secret%20management.md) |
| 06 | S3 credential protection | 3,529 | 94,506 | [06. S3 credential protection.md](06.%20S3%20credential%20protection.md) |
| 07 | TLS for dashboard | 3,524 | 92,882 | [07. TLS for dashboard.md](07.%20TLS%20for%20dashboard.md) |
| 08 | TLS for workbench | 3,524 | 93,671 | [08. TLS for workbench.md](08.%20TLS%20for%20workbench.md) |
| 09 | TLS for model endpoint | 3,528 | 95,310 | [09. TLS for model endpoint.md](09.%20TLS%20for%20model%20endpoint.md) |
| 10 | Route security | 3,525 | 95,276 | [10. Route security.md](10.%20Route%20security.md) |
| 11 | OAuth integration | 3,521 | 93,678 | [11. OAuth integration.md](11.%20OAuth%20integration.md) |
| 12 | LDAP integration | 3,521 | 95,280 | [12. LDAP integration.md](12.%20LDAP%20integration.md) |
| 13 | NetworkPolicy isolation | 3,538 | 96,120 | [13. NetworkPolicy isolation.md](13.%20NetworkPolicy%20isolation.md) |
| 14 | Egress control | 3,527 | 92,080 | [14. Egress control.md](14.%20Egress%20control.md) |
| 15 | Image signing | 3,520 | 92,060 | [15. Image signing.md](15.%20Image%20signing.md) |
| 16 | Image scanning | 3,520 | 94,460 | [16. Image scanning.md](16.%20Image%20scanning.md) |
| 17 | Custom image hardening | 3,523 | 95,311 | [17. Custom image hardening.md](17.%20Custom%20image%20hardening.md) |
| 18 | Vulnerability management | 3,520 | 92,069 | [18. Vulnerability management.md](18.%20Vulnerability%20management.md) |
| 19 | Model artifact security | 3,520 | 93,671 | [19. Model artifact security.md](19.%20Model%20artifact%20security.md) |
| 20 | Model supply chain security | 3,520 | 94,474 | [20. Model supply chain security.md](20.%20Model%20supply%20chain%20security.md) |
| 21 | Dataset security | 3,520 | 93,666 | [21. Dataset security.md](21.%20Dataset%20security.md) |
| 22 | PII handling | 3,520 | 91,268 | [22. PII handling.md](22.%20PII%20handling.md) |
| 23 | Data privacy | 3,520 | 95,277 | [23. Data privacy.md](23.%20Data%20privacy.md) |
| 24 | Audit logging | 3,518 | 92,874 | [24. Audit logging.md](24.%20Audit%20logging.md) |
| 25 | Compliance reporting | 3,520 | 92,881 | [25. Compliance reporting.md](25.%20Compliance%20reporting.md) |
| 26 | Disconnected security | 3,519 | 95,274 | [26. Disconnected security.md](26.%20Disconnected%20security.md) |
| 27 | Least privilege design | 3,521 | 94,494 | [27. Least privilege design.md](27.%20Least%20privilege%20design.md) |
| 28 | Multi-tenant security | 3,522 | 95,279 | [28. Multi-tenant security.md](28.%20Multi-tenant%20security.md) |
| 29 | Secrets rotation | 3,521 | 93,691 | [29. Secrets rotation.md](29.%20Secrets%20rotation.md) |
| 30 | Access review | 3,521 | 94,487 | [30. Access review.md](30.%20Access%20review.md) |

## Suggested study sequence

1. Start with files 01–06 for architecture, authorization, workload admission, machine identity, and secrets.
2. Continue with files 07–14 for TLS, routing, identity integration, tenant network isolation, and egress.
3. Study files 15–20 for image, vulnerability, model artifact, and model supply-chain assurance.
4. Study files 21–25 for data, PII, privacy, audit, and compliance evidence.
5. Finish with files 26–30 for disconnected operations, least privilege, multi-tenancy, rotation, and access certification.

## Official documentation baseline

- [Red Hat OpenShift AI Self-Managed 3.5 documentation](https://docs.redhat.com/en/documentation/red_hat_openshift_ai_self-managed/3.5/)
- [OpenShift AI 3.5 project connections](https://docs.redhat.com/en/documentation/red_hat_openshift_ai_self-managed/3.5/html/working_on_projects/using-connections_projects)
- [OpenShift AI 3.5 administration](https://docs.redhat.com/en/documentation/red_hat_openshift_ai_self-managed/3.5/html/managing_openshift_ai/index)
- [OpenShift AI 3.5 Models-as-a-Service governance](https://docs.redhat.com/en/documentation/red_hat_openshift_ai_self-managed/3.5/html/govern_llm_access_with_models-as-a-service/index)
- [OpenShift Container Platform 4.20 RBAC](https://docs.redhat.com/en/documentation/openshift_container_platform/4.20/html/authentication_and_authorization/using-rbac)
- [OpenShift Container Platform 4.20 security and compliance](https://docs.redhat.com/en/documentation/openshift_container_platform/4.20/html/security_and_compliance/index)
- [OpenShift Container Platform 4.20 container security and SCC concepts](https://docs.redhat.com/en/documentation/openshift_container_platform/4.20/html/security_and_compliance/container-security-1)
- [Red Hat Advanced Cluster Security 4.10 image vulnerability scanning](https://docs.redhat.com/en/documentation/red_hat_advanced_cluster_security_for_kubernetes/4.10/html/operating/examine-images-for-vulnerabilities)
- [Red Hat Trusted Artifact Signer documentation](https://docs.redhat.com/en/documentation/red_hat_trusted_artifact_signer/1/html-single/deployment_guide/index)
