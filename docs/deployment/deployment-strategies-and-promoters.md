# Deployment Strategies and Promoters

## Deployment Strategies

### Argo Rollouts

- Official: <https://argo-rollouts.readthedocs.io/>
- GitHub: <https://github.com/argoproj/argo-rollouts>

Argo project providing advanced Kubernetes deployment strategies (canary, blue-green, progressive delivery) with analysis and traffic shaping.

### Flagger

- Official: <https://flagger.app/>
- GitHub: <https://github.com/fluxcd/flagger>

Flux project for progressive delivery on Kubernetes, automating canary, A/B testing, and blue-green releases with metric analysis.

### OpenKruise Rollouts

- Official: <https://openkruise.io/rollouts/introduction>
- GitHub: <https://github.com/openkruise/rollouts>

CNCF Incubating OpenKruise component providing bypass progressive delivery without modifying native Deployment/StatefulSet workloads.

## Promoters

### Kargo

- Official: <https://kargo.io/>
- GitHub: <https://github.com/akuity/kargo>

Akuity's open source multi-stage application promotion engine for GitOps, orchestrating progressive promotion across environments with Argo CD.

### GitOps Promoter

- GitHub: <https://github.com/argoproj-labs/gitops-promoter>

Argo Labs project that automates promoting changes across environments in GitOps repositories using pull requests and policies.

### Stakater Reloader

- GitHub: <https://github.com/stakater/Reloader>

Stakater's Kubernetes controller that watches ConfigMaps and Secrets and performs rolling upgrades of Deployments, StatefulSets, and DaemonSets when their contents change.
