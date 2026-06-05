# Prometheus Metrics

## Prometheus

- Official: <https://prometheus.io/>
- GitHub: <https://github.com/prometheus/prometheus>

CNCF Graduated systems and service monitoring system collecting time-series metrics via pull, with PromQL and a powerful alerting model.

## OpenMetrics

- Official: <https://openmetrics.io/>
- GitHub: <https://github.com/OpenObservability/OpenMetrics>

CNCF Sandbox specification that standardizes the Prometheus exposition format as a vendor-neutral metrics interchange (now an IETF RFC track).

## Prometheus Operator

- Official: <https://prometheus-operator.dev/>
- GitHub: <https://github.com/prometheus-operator/prometheus-operator>

CNCF Incubating operator that provides Kubernetes-native deployment and management of Prometheus, Alertmanager, and related resources via CRDs.

## kube-prometheus-stack

- GitHub: <https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack>

Community Helm chart bundling Prometheus Operator, Alertmanager, Grafana, node-exporter, kube-state-metrics, and curated dashboards/alerts.

## kube-prometheus

- GitHub: <https://github.com/prometheus-operator/kube-prometheus>

End-to-end Kubernetes cluster monitoring stack defined with jsonnet, providing the same components as kube-prometheus-stack via Tanka/jsonnet.

## Grafana Kubernetes Monitoring

- Official: <https://grafana.com/docs/grafana-cloud/monitor-infrastructure/kubernetes-monitoring/>

Grafana Cloud's opinionated Kubernetes monitoring solution that ships metrics, logs, traces, and events via Grafana Agent/Alloy.

## Runbooks (Prometheus Operator runbooks)

- GitHub: <https://github.com/prometheus-operator/runbooks>

Community-maintained runbooks for the alerts shipped by the kube-prometheus / prometheus-operator stacks, linked from Alertmanager notifications.
