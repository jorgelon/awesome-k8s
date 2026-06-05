# Alternatives

## Pixie

- Official: <https://px.dev/>
- GitHub: <https://github.com/pixie-io/pixie>

CNCF Sandbox eBPF-based observability platform that auto-instruments Kubernetes applications for metrics, traces, logs, and protocols without code changes.

## Sentry

- Official: <https://sentry.io/>
- GitHub: <https://github.com/getsentry/sentry>

Application monitoring and error tracking platform, with Kubernetes-friendly self-hosted Helm charts and tight CI/CD integration.

## Goldpinger

- GitHub: <https://github.com/bloomberg/goldpinger>

Bloomberg's lightweight DaemonSet that pings other pods to expose intra-cluster connectivity health and latency as Prometheus metrics.

## Botkube

- Official: <https://botkube.io/>
- GitHub: <https://github.com/kubeshop/botkube>

Open source ChatOps tool that monitors Kubernetes events and runs commands via Slack, Microsoft Teams, Discord, and Mattermost.

## Node Problem Detector

- GitHub: <https://github.com/kubernetes/node-problem-detector>

Kubernetes SIG DaemonSet that detects node-level problems (kernel deadlocks, disk issues, runtime issues) and reports them to the API server.

## SSL Exporter

- GitHub: <https://github.com/ribbybibby/ssl_exporter>

Prometheus exporter that probes endpoints and certificates to expose TLS certificate expiry, issuer, and validity metrics.

## Ingress Monitor Controller

- GitHub: <https://github.com/stakater/IngressMonitorController>

Stakater controller that auto-registers Ingress hosts in external uptime monitors (UptimeRobot, StatusCake, Pingdom, etc.).

## List of Grafana Kubernetes Dashboards

- kubernetes-mixin: <https://github.com/kubernetes-monitoring/kubernetes-mixin>
- dotdc/grafana-dashboards-kubernetes: <https://github.com/dotdc/grafana-dashboards-kubernetes>

Reusable jsonnet libraries and curated Grafana dashboards/alerts for monitoring Kubernetes clusters, widely adopted as the baseline for kube-prometheus stacks.
