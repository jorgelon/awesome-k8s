# Load Balancer

## MetalLB

- Official: <https://metallb.universe.tf/>
- GitHub: <https://github.com/metallb/metallb>

Bare-metal load balancer for Kubernetes that provides external IPs for Services of type LoadBalancer using ARP, NDP, or BGP.

## OpenELB

- Official: <https://openelb.github.io/>
- GitHub: <https://github.com/openelb/openelb>

KubeSphere's open source load balancer for bare-metal Kubernetes, supporting BGP, Layer 2 mode, and VIP advertisement.

## PureLB

- Official: <https://purelb.gitlab.io/>
- GitLab: <https://gitlab.com/purelb/purelb>

Service load-balancer for bare-metal Kubernetes that uses the host's existing routing stack, designed as a more flexible alternative to MetalLB.

## Cilium L2 Announcements

- Official: <https://docs.cilium.io/en/stable/network/l2-announcements/>

Cilium feature that announces Service IPs (LoadBalancer or ExternalIPs) on the local L2 network via ARP/NDP, replacing MetalLB in L2 mode.

## Katran

- GitHub: <https://github.com/facebookincubator/katran>

Meta's high-performance Layer 4 load balancer library built on XDP/eBPF, used at scale in production.

## kube-vip

- Official: <https://kube-vip.io/>
- GitHub: <https://github.com/kube-vip/kube-vip>

High-availability solution that provides a virtual IP and load balancer for control planes and Services on bare metal, using ARP or BGP.
