# DNS

## ExternalDNS

- GitHub: <https://github.com/kubernetes-sigs/external-dns>

Kubernetes SIG controller that synchronizes Services and Ingresses with external DNS providers (Route53, Cloud DNS, Cloudflare, etc.).

## CoreDNS

- Official: <https://coredns.io/>
- GitHub: <https://github.com/coredns/coredns>

CNCF Graduated flexible, extensible DNS server written in Go, used as the default cluster DNS in modern Kubernetes distributions.

## NodeLocal DNSCache

- Official: <https://kubernetes.io/docs/tasks/administer-cluster/nodelocaldns/>
- GitHub: <https://github.com/kubernetes/dns/tree/master/cmd/node-cache>

Kubernetes feature that runs a DNS caching agent on each node, reducing latency, conntrack pressure, and load on CoreDNS.
