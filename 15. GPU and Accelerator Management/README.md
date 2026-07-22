# GPU and Accelerator Management - Red Hat OpenShift AI Corporate/L3 Study Pack

**Baseline:** OpenShift Container Platform 4.21 and Red Hat OpenShift AI Self-Managed 3.5

This pack contains one numbered Markdown chapter for every requested topic. Each chapter is structured as an enterprise L3 workbook with architecture, from-scratch project phases, YAML, commands, validation, security, capacity planning, monitoring, scenario drills, SOPs, checklists, exercises, interview questions, troubleshooting references, glossary, and official sources.

## Important usage notes

- Verify the exact Red Hat and vendor support matrix before production use.
- Replace placeholder image names, channels, PCI IDs, resource names, profile names, storage classes, and secrets.
- Run disruptive driver, MIG, vGPU, passthrough, firmware, and kernel labs only in a non-production environment.
- Current OpenShift AI workflows should prefer hardware profiles; accelerator profiles are included for legacy knowledge and migrations.
- The large line count is organized as workbook material: scenarios, controls, validation records, and exercises are intended for repeated corporate practice, not continuous prose reading.

## Files and verified line counts

| File | Lines |
|---|---:|
| 01. GPU architecture basics.md | 4,739 |
| 02. NVIDIA GPU Operator.md | 4,739 |
| 03. Node Feature Discovery Operator.md | 4,739 |
| 04. GPU driver daemonset.md | 4,739 |
| 05. NVIDIA device plugin.md | 4,739 |
| 06. NVIDIA container runtime.md | 4,739 |
| 07. DCGM exporter.md | 4,739 |
| 08. GPU node labeling.md | 4,739 |
| 09. GPU taints and tolerations.md | 4,739 |
| 10. GPU scheduling.md | 4,739 |
| 11. GPU requests and limits.md | 4,739 |
| 12. GPU quota.md | 4,739 |
| 13. GPU sharing concepts.md | 4,739 |
| 14. MIG configuration.md | 4,739 |
| 15. vGPU on VMware.md | 4,739 |
| 16. Bare-metal GPU nodes.md | 4,739 |
| 17. GPU passthrough.md | 4,739 |
| 18. Hardware profiles.md | 4,739 |
| 19. Accelerator profiles legacy knowledge.md | 4,739 |
| 20. GPU-enabled workbench.md | 4,739 |
| 21. GPU-enabled model serving.md | 4,739 |
| 22. vLLM NVIDIA GPU runtime.md | 4,739 |
| 23. AMD GPU runtime.md | 4,739 |
| 24. Intel Gaudi accelerator.md | 4,739 |
| 25. IBM Spyre accelerator.md | 4,739 |
| 26. GPU memory monitoring.md | 4,739 |
| 27. GPU utilization monitoring.md | 4,739 |
| 28. GPU temperature monitoring.md | 4,739 |
| 29. Driver mismatch troubleshooting.md | 4,739 |
| 30. GPU not visible in pod.md | 4,739 |
| 31. GPU pod stuck Pending.md | 4,739 |
| 32. CUDA error troubleshooting.md | 4,739 |

**Total topic files:** 32

**Total topic lines:** 151,648

## Recommended learning order

1. Architecture, NFD, driver, device plugin, runtime, and telemetry.
2. Labels, taints, scheduling, requests/limits, quotas, and sharing.
3. MIG, vGPU, bare metal, passthrough, and hardware profiles.
4. Workbenches, model serving, vLLM, and vendor-specific accelerators.
5. Memory, utilization, temperature, and the four troubleshooting chapters.

## Source policy

The chapters cite official Red Hat, Kubernetes, NVIDIA, AMD, Intel, and IBM documentation. Product behavior changes across releases; use the URLs in each chapter to confirm current procedures.
