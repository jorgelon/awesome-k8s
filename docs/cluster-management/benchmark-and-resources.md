# Benchmark and Resources

## kube-bench

- GitHub: <https://github.com/aquasecurity/kube-bench>

Aqua Security tool that checks whether Kubernetes is deployed securely by running the CIS Kubernetes Benchmark.

## Goldilocks

- Official: <https://goldilocks.docs.fairwinds.com/>
- GitHub: <https://github.com/FairwindsOps/goldilocks>

Fairwinds tool that uses the Vertical Pod Autoscaler in recommendation mode to identify appropriate CPU and memory requests/limits.

## Robusta

- Official: <https://home.robusta.dev/>
- GitHub: <https://github.com/robusta-dev/robusta>

Open source Kubernetes observability and automation platform that enriches Prometheus alerts and runs playbooks against the cluster.

## Robusta KRR

- GitHub: <https://github.com/robusta-dev/krr>

Kubernetes Resource Recommender from Robusta: scans your cluster and Prometheus to recommend right-sized CPU/memory requests and limits.

## k8s-pod-cpu-stressor

- GitHub: <https://github.com/krzko/k8s-pod-cpu-stressor>

Small utility/Helm chart for stressing CPU on Kubernetes pods, useful for testing autoscaling and resource limits.

## Kube Capacity

- GitHub: <https://github.com/robscott/kube-capacity>

CLI that provides an overview of resource requests, limits, and utilization in a Kubernetes cluster, similar to `kubectl top` but with capacity context.

## Kruize Autotune

- GitHub: <https://github.com/kruize/autotune>

Open source autotuning framework that recommends and applies right-sized resource requests, limits, and runtime configurations for Kubernetes workloads.

## StormForge

- Official: <https://www.stormforge.io/>
- GitHub: <https://github.com/thestormforge>

StormForge's machine-learning-based platform for optimizing Kubernetes resource requests/limits and HPA settings to reduce cost and improve reliability.

## Parca

- Official: <https://www.parca.dev/>
- GitHub: <https://github.com/parca-dev/parca>

Open source continuous profiling for Kubernetes and Linux, using eBPF to collect CPU profiles with minimal overhead.

## Polar Signals Profiler (Prodfiler)

- Official: <https://www.polarsignals.com/>
- Elastic Universal Profiling (ex-Prodfiler): <https://www.elastic.co/observability/universal-profiling>

Continuous, whole-system profiler originally built as Prodfiler (now Elastic Universal Profiling) and offered as a managed service by Polar Signals.

## Kor

- GitHub: <https://github.com/yonahd/kor>

Kubernetes Orphaned Resources finder — scans the cluster for unused ConfigMaps, Secrets, Services, ServiceAccounts, Deployments, HPAs, PVCs, etc.

## Right Size Guide (RSG)

- Official: <https://mhausenblas.info/right-size-guide/>
- GitHub: <https://github.com/mhausenblas/right-size-guide>

Michael Hausenblas' simple, standalone tool that observes a containerized workload and produces baseline CPU/memory request and limit recommendations.
