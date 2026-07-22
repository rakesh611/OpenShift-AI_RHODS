# KServe Deep Dive for Red Hat OpenShift AI - Corporate/L3

Generated: 2026-07-21

## Baseline

- Product baseline: Red Hat OpenShift AI 3.5.
- Upstream reference: KServe 0.18.
- Audience: senior OpenShift/Kubernetes/AI platform engineers with approximately 10+ years of infrastructure experience.
- Format: one standalone Markdown file per requested topic.

## Important support note

Upstream KServe documentation is used to deepen architecture and troubleshooting understanding. Production configuration must be validated against the Red Hat documentation and support policy for the exact installed OpenShift AI release.

## Files

- [01. KServe architecture](01.%20KServe%20architecture.md) — 3,777 lines, 54,996 words
- [02. InferenceService CRD](02.%20InferenceService%20CRD.md) — 3,765 lines, 53,973 words
- [03. Predictor](03.%20Predictor.md) — 3,752 lines, 54,056 words
- [04. Transformer](04.%20Transformer.md) — 3,758 lines, 54,094 words
- [05. Explainer](05.%20Explainer.md) — 3,752 lines, 54,061 words
- [06. ServingRuntime](06.%20ServingRuntime.md) — 3,752 lines, 53,676 words
- [07. ClusterServingRuntime](07.%20ClusterServingRuntime.md) — 3,752 lines, 54,089 words
- [08. RawDeployment mode](08.%20RawDeployment%20mode.md) — 3,752 lines, 54,190 words
- [09. KServe networking](09.%20KServe%20networking.md) — 3,771 lines, 54,634 words
- [10. KServe storage access](10.%20KServe%20storage%20access.md) — 3,761 lines, 55,080 words
- [11. KServe autoscaling](11.%20KServe%20autoscaling.md) — 3,755 lines, 53,950 words
- [12. KServe readiness](12.%20KServe%20readiness.md) — 3,752 lines, 54,387 words
- [13. KServe status conditions](13.%20KServe%20status%20conditions.md) — 3,749 lines, 54,249 words
- [14. KServe logs](14.%20KServe%20logs.md) — 3,755 lines, 54,576 words
- [15. KServe events](15.%20KServe%20events.md) — 3,761 lines, 54,260 words
- [16. KServe route creation](16.%20KServe%20route%20creation.md) — 3,752 lines, 55,055 words
- [17. KServe TLS](17.%20KServe%20TLS.md) — 3,761 lines, 54,510 words
- [18. KServe authorization](18.%20KServe%20authorization.md) — 3,761 lines, 54,725 words
- [19. KServe GPU runtime](19.%20KServe%20GPU%20runtime.md) — 3,765 lines, 55,647 words
- [20. KServe troubleshooting](20.%20KServe%20troubleshooting.md) — 3,786 lines, 54,543 words

## How to use the pack

1. Read files 01-08 for architecture, API, components, runtimes, and deployment mode.
2. Read files 09-18 for networking, storage, scaling, health, observability, exposure, TLS, and authorization.
3. Read files 19-20 for accelerator operations and integrated troubleshooting.
4. Run all labs in a disposable non-production namespace.
5. Replace placeholder images, credentials, endpoints, storage paths, and model formats with approved environment values.
6. Keep all manifests in Git and record observed conditions, events, logs, metrics, and inference evidence.

## Total size

- Topic files: 20
- Total lines: 75,189
- Total words: 1,088,751
