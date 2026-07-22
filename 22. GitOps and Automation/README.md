# Red Hat OpenShift AI - GitOps and Automation Corporate L3 Study Pack

This folder contains 25 deep-dive Markdown guides. Each guide includes architecture, project creation from scratch, manifests, commands, security, observability, troubleshooting, production readiness, labs, enterprise drills, and official references.

## Version scope

Prepared on 2026-07-21. The examples are aligned to current official documentation found for OpenShift AI 3.4/3.5-era releases, OpenShift GitOps 1.20, and OpenShift Pipelines 1.14-era documentation. Product APIs and support status can change; always compare manifests with the CRDs installed on the target cluster.

## File inventory

| No. | Topic | Filename | Lines | Words |
|---:|---|---|---:|---:|
| 01 | GitOps for OpenShift AI | `01. GitOps for OpenShift AI.md` | 3,600 | 45,301 |
| 02 | OpenShift GitOps | `02. OpenShift GitOps.md` | 3,650 | 45,003 |
| 03 | Argo CD | `03. Argo CD.md` | 3,700 | 45,803 |
| 04 | OpenShift Pipelines | `04. OpenShift Pipelines.md` | 3,750 | 46,051 |
| 05 | Tekton | `05. Tekton.md` | 3,800 | 46,480 |
| 06 | Helm | `06. Helm.md` | 3,550 | 43,086 |
| 07 | Kustomize | `07. Kustomize.md` | 3,600 | 44,018 |
| 08 | Ansible automation | `08. Ansible automation.md` | 3,650 | 45,008 |
| 09 | Operator installation automation | `09. Operator installation automation.md` | 3,700 | 45,707 |
| 10 | DataScienceCluster automation | `10. DataScienceCluster automation.md` | 3,750 | 46,253 |
| 11 | Workbench image automation | `11. Workbench image automation.md` | 3,800 | 47,674 |
| 12 | Pipeline deployment automation | `12. Pipeline deployment automation.md` | 3,550 | 44,194 |
| 13 | Model deployment automation | `13. Model deployment automation.md` | 3,600 | 44,287 |
| 14 | ServingRuntime automation | `14. ServingRuntime automation.md` | 3,650 | 45,321 |
| 15 | InferenceService automation | `15. InferenceService automation.md` | 3,700 | 45,547 |
| 16 | Secrets automation | `16. Secrets automation.md` | 3,750 | 46,168 |
| 17 | RBAC automation | `17. RBAC automation.md` | 3,800 | 47,239 |
| 18 | NetworkPolicy automation | `18. NetworkPolicy automation.md` | 3,550 | 43,512 |
| 19 | ResourceQuota automation | `19. ResourceQuota automation.md` | 3,600 | 44,635 |
| 20 | Environment promotion | `20. Environment promotion.md` | 3,650 | 45,263 |
| 21 | Dev/test/prod deployment | `21. Dev-test-prod deployment.md` | 3,700 | 46,115 |
| 22 | Model promotion workflow | `22. Model promotion workflow.md` | 3,750 | 46,645 |
| 23 | Rollback automation | `23. Rollback automation.md` | 3,800 | 47,685 |
| 24 | CI/CD for model serving | `24. CI-CD for model serving.md` | 3,550 | 44,497 |
| 25 | CI/CD for custom images | `25. CI-CD for custom images.md` | 3,600 | 45,021 |

## Recommended learning order

1. Start with files 01-08 for architecture and core automation tools.
2. Continue with files 09-19 for platform resources and policy automation.
3. Complete files 20-25 for promotion, rollback, and end-to-end CI/CD.
4. Implement every lab in a disposable OpenShift project before adapting it to production.

## Quality and safety notes

- Placeholder values such as `<supported-channel>` and `sha256:REPLACE_ME` must be replaced with values approved for the target environment.
- Technology Preview or version-sensitive features must be checked against current Red Hat support documentation.
- Do not store plaintext secrets in Git.
- Prefer GitOps reconciliation for production deployment and restrict direct CI credentials.
- Validate every manifest with server-side dry run and the installed CRD schema.

## Official source families

- [Red Hat OpenShift AI Self-Managed 3.4 - Installing and uninstalling](https://docs.redhat.com/en/documentation/red_hat_openshift_ai_self-managed/3.4/html/installing_and_uninstalling_openshift_ai_self-managed/)
- [Red Hat OpenShift AI Self-Managed 3.4 - Configuring model serving](https://docs.redhat.com/en/documentation/red_hat_openshift_ai_self-managed/3.4/html-single/configuring_your_model-serving_platform/)
- [Red Hat OpenShift AI Self-Managed 3.4 - Working on projects](https://docs.redhat.com/en/documentation/red_hat_openshift_ai_self-managed/3.4/html-single/working_on_projects/)
- [Red Hat OpenShift AI Self-Managed 3.4 - AI pipelines](https://docs.redhat.com/en/documentation/red_hat_openshift_ai_self-managed/3.4/html-single/working_with_ai_pipelines/)
- [Red Hat OpenShift AI Self-Managed 3.4 - Creating a workbench](https://docs.redhat.com/en/documentation/red_hat_openshift_ai_self-managed/3.4/html-single/creating_a_workbench/)
- [Red Hat OpenShift GitOps 1.20 documentation](https://docs.redhat.com/en/documentation/red_hat_openshift_gitops/1.20/)
- [Red Hat OpenShift Pipelines documentation](https://docs.redhat.com/en/documentation/red_hat_openshift_pipelines/)
- [Argo CD documentation](https://argo-cd.readthedocs.io/en/stable/)
- [Tekton documentation](https://tekton.dev/docs/)
- [Helm documentation](https://helm.sh/docs/)
- [Kubernetes Kustomize documentation](https://kubernetes.io/docs/tasks/manage-kubernetes-objects/kustomization/)
- [Kubernetes RBAC documentation](https://kubernetes.io/docs/reference/access-authn-authz/rbac/)
- [Kubernetes NetworkPolicy documentation](https://kubernetes.io/docs/concepts/services-networking/network-policies/)
- [Kubernetes ResourceQuota documentation](https://kubernetes.io/docs/concepts/policy/resource-quotas/)
- [Ansible kubernetes.core collection](https://docs.ansible.com/projects/ansible/latest/collections/kubernetes/core/)
