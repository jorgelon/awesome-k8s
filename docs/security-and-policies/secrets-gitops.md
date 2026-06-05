# Secrets GitOps

## External Secrets Operator

- Official: <https://external-secrets.io/>
- GitHub: <https://github.com/external-secrets/external-secrets>

CNCF Sandbox operator that syncs secrets from external providers (Vault, AWS/GCP/Azure secret managers, 1Password, etc.) into Kubernetes Secrets.

## Mozilla SOPS

- GitHub: <https://github.com/getsops/sops>

Encrypted file editor supporting YAML, JSON, ENV, INI, and binary with KMS/Vault/age/PGP backends — widely used with Flux for GitOps secrets.

## Argo CD Vault Plugin

- GitHub: <https://github.com/argoproj-labs/argocd-vault-plugin>

Argo Labs plugin that retrieves secrets from Vault and other secret managers and injects them into Kubernetes manifests at sync time.

## Secrets Store CSI Driver

- Official: <https://secrets-store-csi-driver.sigs.k8s.io/>
- GitHub: <https://github.com/kubernetes-sigs/secrets-store-csi-driver>

Kubernetes SIG driver that mounts secrets from external providers as volumes into pods, with optional sync to Kubernetes Secrets.

## Helm Secrets

- GitHub: <https://github.com/jkroepke/helm-secrets>

Helm plugin that integrates with SOPS (and Vault) to manage and decrypt encrypted values files transparently during install/upgrade.

## Vault and Kubernetes (Vault Agent Injector)

- Official: <https://developer.hashicorp.com/vault/docs/platform/k8s/injector>
- GitHub: <https://github.com/hashicorp/vault-k8s>

HashiCorp's mutating webhook that injects a Vault Agent sidecar into pods to fetch and renew secrets from Vault at runtime.

## vault-secrets-operator

- Official: <https://developer.hashicorp.com/vault/docs/platform/k8s/vso>
- GitHub: <https://github.com/hashicorp/vault-secrets-operator>

HashiCorp's official operator that syncs Vault secrets into native Kubernetes Secrets via CRDs, with rotation and templating.

## Kamus

- GitHub: <https://github.com/Soluto/kamus>

Soluto's open source GitOps-friendly secrets encryption tool for Kubernetes, decrypting secrets only for authorized service accounts.

## Sync Secrets Tools

- Reflector: <https://github.com/emberstack/kubernetes-reflector>
- kubed: <https://github.com/kubeops/config-syncer>
- kubernetes-replicator: <https://github.com/mittwald/kubernetes-replicator>

Tools that mirror or replicate Secrets (and ConfigMaps) across namespaces or clusters — useful for distributing TLS certs, registry creds, etc.
