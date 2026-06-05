# Service Mesh

## Linkerd

- Official: <https://linkerd.io/>
- GitHub: <https://github.com/linkerd/linkerd2>

CNCF Graduated ultralight service mesh for Kubernetes, with a Rust-based proxy (linkerd2-proxy) focused on simplicity, security, and performance.

## Istio

- Official: <https://istio.io/>
- GitHub: <https://github.com/istio/istio>

CNCF Graduated service mesh providing traffic management, security (mTLS), and observability via Envoy sidecars or the new ambient (sidecarless) mode.

## Consul

- Official: <https://www.consul.io/>
- GitHub: <https://github.com/hashicorp/consul>

HashiCorp's service networking platform with service discovery, mesh (mTLS via Envoy), and Kubernetes integration through Consul on Kubernetes.

## Traefik Mesh

- Official: <https://traefik.io/traefik-mesh/>
- GitHub: <https://github.com/traefik/mesh>

Traefik Labs' simple, non-invasive service mesh ("smi") that runs as a DaemonSet without sidecars, using SMI-compliant traffic policies.

## Kuma

- Official: <https://kuma.io/>
- GitHub: <https://github.com/kumahq/kuma>

CNCF Sandbox universal service mesh built on Envoy from Kong, supporting Kubernetes and VMs with multi-zone, multi-mesh deployments.

## Merbridge (eBPF)

- GitHub: <https://github.com/merbridge/merbridge>

CNCF Sandbox project that accelerates Istio/Linkerd service meshes by replacing iptables redirects with eBPF socket-level redirection.

## Istio Ambient Mesh

- Official: <https://istio.io/latest/docs/ambient/overview/>

Istio's sidecar-less data plane mode using per-node ztunnel and optional Layer 7 waypoint proxies, lowering resource cost and operational complexity.

## Cilium Service Mesh

- Official: <https://cilium.io/use-cases/service-mesh/>
- GitHub: <https://github.com/cilium/cilium>

Cilium's eBPF-native service mesh providing mTLS, traffic policies, and observability without sidecars by leveraging in-kernel programs.

## Meshery

- Official: <https://meshery.io/>
- GitHub: <https://github.com/meshery/meshery>

CNCF Sandbox cloud-native manager for service meshes, providing multi-mesh management, performance benchmarking, and design as code.
