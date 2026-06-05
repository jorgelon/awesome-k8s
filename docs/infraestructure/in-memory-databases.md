# In-Memory Databases

## With Operator

### Dragonfly

- Official: <https://www.dragonflydb.io/>
- GitHub: <https://github.com/dragonflydb/dragonfly>

Modern, multi-threaded in-memory data store, a drop-in replacement for Redis and Memcached with higher throughput on a single node.

### OT Container Kit Redis Operator

- GitHub: <https://github.com/OT-CONTAINER-KIT/redis-operator>

OpsTree's open source Redis operator for Kubernetes, supporting standalone, replicated, and cluster modes with sentinel and TLS.

### Redis Enterprise Operator

- Official: <https://redis.io/docs/latest/operate/kubernetes/>
- GitHub: <https://github.com/RedisLabs/redis-enterprise-k8s-docs>

Redis Inc.'s official operator to deploy and manage Redis Enterprise Software clusters on Kubernetes (commercial license).

### KubeDB (Redis)

- Official: <https://kubedb.com/docs/latest/guides/redis/>

AppsCode's KubeDB operator includes Redis support, providing provisioning, backups, monitoring, and TLS for Redis on Kubernetes.

### Spotahome Redis Operator (unmaintained)

- GitHub: <https://github.com/spotahome/redis-operator>

Spotahome's Redis operator that manages highly available Redis with Sentinel-based automatic failover. Note: no longer actively maintained.

## Without Operator

### KeyDB

- Official: <https://docs.keydb.dev/>
- GitHub: <https://github.com/Snapchat/KeyDB>

Snapchat-maintained multithreaded fork of Redis, advertised as a faster Redis alternative with multi-master replication.

### Valkey

- Official: <https://valkey.io/>
- GitHub: <https://github.com/valkey-io/valkey>

Linux Foundation open source fork of Redis (BSD-licensed), positioned as a flexible distributed key-value database for caching and real-time workloads.
