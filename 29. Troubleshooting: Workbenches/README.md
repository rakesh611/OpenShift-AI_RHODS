# Red Hat OpenShift AI — Troubleshooting: Workbenches

Corporate L3 / senior platform-engineering training package.

## Baseline

- Primary stable documentation baseline: Red Hat OpenShift AI Self-Managed 3.4.
- OpenShift AI 3.5 material is treated as version-dependent or early-access unless supported in the target environment.
- Every guide contains a from-scratch lab, controlled fault injection, evidence bundle, root-cause matrix, detailed runbooks, decision drills, production cases, automation, observability, incident handling, validation, references, and competency checks.

## Files

| # | File | Physical lines | SHA-256 |
|---:|---|---:|---|
| 01 | 01. Workbench not starting.md | 4,315 | `d14cb2f589848e92f1a8bb71939d01da8eec01fdeaf078603ab77d50756c94d1` |
| 02 | 02. Workbench stuck Starting.md | 4,315 | `fed3ac0cc081745bb654853a160ecb98756903730231ab74617b61e6788ef9c3` |
| 03 | 03. Workbench pod Pending.md | 4,315 | `76e46a826b8f5b08f616dffbc0041b93cf5d279ccb8fcf3f2d2c744360734887` |
| 04 | 04. Workbench CrashLoopBackOff.md | 4,315 | `31f7d9a980f6af6a86c2fc268d82665b44c7d6df73b014043f04de3e01e91244` |
| 05 | 05. Workbench ImagePullBackOff.md | 4,315 | `90470ea56cb5e1391586308894b78f860051297c56cbc6f682c03506217f783e` |
| 06 | 06. PVC not mounted.md | 4,315 | `18d71bcb5ec0f429d9279de6eefa3c4f079041a97599ad31cb82dc24c2616d95` |
| 07 | 07. Notebook kernel not starting.md | 4,315 | `ed18267b178eb69d67d63de2f0ba3647f568afdc2c89e9153b4fcb0dd6b77b17` |
| 08 | 08. User cannot access workbench.md | 4,315 | `dbb9ddd3c35deb96a42647d221ea7d5c813a45740843df6f01a02db4ca0eff12` |
| 09 | 09. Workbench route unavailable.md | 4,315 | `8a93fb344d08ab8d7e3ba4d1d03b67299625653afed2ee4a3dd79e1c30fa1ff8` |
| 10 | 10. Custom image not visible.md | 4,315 | `ec0c2f9bd7147ea3af1afefff923406dc1106d34f059a20623484976207842db` |
| 11 | 11. Custom image broken.md | 4,315 | `49f58562de106499a79704cfa6d28ba6e91d72509fc9063e1f829646ccb3e92f` |
| 12 | 12. Python package missing.md | 4,315 | `e68118f7128a07d038bc8204a78511f2591f956b6391092dc1013f5db6cb9223` |
| 13 | 13. GPU not available.md | 4,315 | `63a4933f4956601205574821cdf6df7d6b292849c6d4fc2ba0ee8daebc456c76` |
| 14 | 14. Workbench memory exceeded.md | 4,315 | `6e405abece28d64d7b8584e80fb1fd68bf8af73737c9d872e68b2452b2b6fb34` |
| 15 | 15. Workbench CPU throttling.md | 4,315 | `4b1a830449f162881c7b569e13172c2f9bb1f6c57fa0aa08fcb498f16f3da272` |
| 16 | 16. Permission denied inside notebook.md | 4,315 | `8a6351c02a4c0b04d1ebbae291d2948f22d5b3bda12dc423ae21efcc002294b5` |
| 17 | 17. Data connection not visible.md | 4,315 | `f587d9f8810aaf65c3b5b8a1590b1f3b3b25ce0763f91d8bcd49405e8e2fffca` |
| 18 | 18. Secret not mounted.md | 4,315 | `dd0e49f71328883b807a141866223a9ee3c253776f021494d4d113df8db0a49e` |
| 19 | 19. Idle timeout issue.md | 4,315 | `be7154ed2ed17ff3d22838546bab1d31f530bcaeb8b121be61efc35b943213e2` |
| 20 | 20. Workbench cleanup issue.md | 4,315 | `44223ab14ee2c545c884f83c4c0178e2599fe65df3d614ba3c413a377c640662` |

## Use

1. Match the guide to the observed symptom.
2. Build the lab in a non-production namespace.
3. Collect evidence before restarting or deleting resources.
4. Repair the declarative source of the failure.
5. Validate platform health and user-level notebook behavior.
6. Add preventive monitoring, policy, and capacity controls.

