# App Language Definition

## Timoni and CUE

- Timoni official: <https://timoni.sh/>
- Timoni GitHub: <https://github.com/stefanprodan/timoni>
- CUE official: <https://cuelang.org/>
- CUE GitHub: <https://github.com/cue-lang/cue>

Timoni is a package manager for Kubernetes built on the CUE language, providing typed, composable, and validated module definitions.

## Helm

- Official: <https://helm.sh/>
- GitHub: <https://github.com/helm/helm>

CNCF Graduated package manager for Kubernetes that templates and releases applications as Charts.

## Kustomize (KRM functions)

- Official: <https://kustomize.io/>
- GitHub: <https://github.com/kubernetes-sigs/kustomize>

Kubernetes-native configuration management that customizes manifests without templates, with support for KRM functions for transformation pipelines.

## PKL

- Official: <https://pkl-lang.org/>
- GitHub: <https://github.com/apple/pkl>

Apple's open source configuration-as-code language with strong typing, validation, and code generation for many targets including Kubernetes.

## Helm OCI

- Docs: <https://helm.sh/docs/topics/registries/>

Helm's support for storing and distributing charts in OCI-compliant registries (such as ECR, GHCR, Harbor) as native artifacts.

## KCL Lang

- Official: <https://www.kcl-lang.io/>
- GitHub: <https://github.com/kcl-lang/kcl>

CNCF Sandbox configuration and policy language for the cloud-native era, with strong typing, validation, and Kubernetes integrations.

## Jsonnet

- Official: <https://jsonnet.org/>
- GitHub: <https://github.com/google/jsonnet>

Google's data templating language often used to generate Kubernetes manifests, with ecosystems like Tanka and kube-libsonnet.

## Holos

- Official: <https://holos.run/>
- GitHub: <https://github.com/holos-run/holos>

Open source platform configuration tool that uses CUE to render Kubernetes manifests and Helm/Kustomize outputs into a unified, validated configuration.

## Helmfile

- GitHub: <https://github.com/helmfile/helmfile>

Declarative spec for deploying Helm charts, allowing you to manage multiple releases, environments, and dependencies as code.

## Argo CD Source Hydrator

- Docs: <https://argo-cd.readthedocs.io/en/latest/operator-manual/rendered-manifests/>
- Proposal: <https://github.com/argoproj/argo-cd/blob/master/docs/proposals/source-hydrator.md>

Argo CD feature that implements the "rendered manifests" GitOps pattern, hydrating dry sources (Helm/Kustomize) into a Git branch of plain YAML for review and sync.

## Carvel ytt

- Official: <https://carvel.dev/ytt/>
- GitHub: <https://github.com/carvel-dev/ytt>

Carvel's YAML templating tool that uses Starlark to express overlays, data values, and reusable templates for Kubernetes manifests.
