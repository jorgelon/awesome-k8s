# Admission Controllers

## Kyverno

- Official: <https://kyverno.io/>
- GitHub: <https://github.com/kyverno/kyverno>

CNCF Graduated Kubernetes-native policy engine that validates, mutates, generates, and verifies images using YAML policies.

## Open Policy Agent (OPA) Gatekeeper

- Official: <https://open-policy-agent.github.io/gatekeeper/>
- GitHub: <https://github.com/open-policy-agent/gatekeeper>

CNCF policy controller for Kubernetes built on OPA Rego, enforcing constraints via ConstraintTemplates and admission webhooks.

## Kubewarden

- Official: <https://www.kubewarden.io/>
- GitHub: <https://github.com/kubewarden>

CNCF Sandbox policy engine for Kubernetes that runs policies as WebAssembly modules, supporting multiple languages and OPA Rego.

## Cloud Custodian

- Official: <https://cloudcustodian.io/>
- GitHub: <https://github.com/cloud-custodian/cloud-custodian>

CNCF Incubating rules engine for cloud security, cost, and governance — Kubernetes provider enforces policies on cluster resources.

## Pod Security Admission

- Official: <https://kubernetes.io/docs/concepts/security/pod-security-admission/>

Built-in Kubernetes admission controller that enforces the Pod Security Standards (privileged/baseline/restricted) at the namespace level.

## Validating Admission Policy (CEL)

- Official: <https://kubernetes.io/docs/reference/access-authn-authz/validating-admission-policy/>

Native Kubernetes admission policies expressed in CEL, allowing in-process validation without webhook overhead (GA in Kubernetes 1.30).

## Polaris

- Official: <https://polaris.docs.fairwinds.com/>
- GitHub: <https://github.com/FairwindsOps/polaris>

Fairwinds' open source tool that audits Kubernetes workloads against best practices and can act as a validating admission controller.

## Datree

- Official: <https://www.datree.io/>
- GitHub: <https://github.com/datreeio/datree>

Policy enforcement engine with 100+ built-in rules covering security, HA, NSA hardening, and Argo CD best practices. Note: project is no longer actively maintained.

## Paralus

- Official: <https://www.paralus.io/>
- GitHub: <https://github.com/paralus/paralus>

CNCF Sandbox project for centralized, zero-trust access management to Kubernetes clusters with audit logging and RBAC.
