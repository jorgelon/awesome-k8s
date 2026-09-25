# Storage and Backup

## etcd

- Official: <https://etcd.io/>
- GitHub: <https://github.com/etcd-io/etcd>

CNCF Graduated distributed key-value store used as the primary datastore for Kubernetes cluster state.

## Rook

- Official: <https://rook.io/>
- GitHub: <https://github.com/rook/rook>

CNCF Graduated storage orchestrator for Kubernetes that deploys and manages Ceph storage clusters as Kubernetes-native services.

## Longhorn

- Official: <https://longhorn.io/>
- GitHub: <https://github.com/longhorn/longhorn>

CNCF Incubating distributed block storage system for Kubernetes from SUSE/Rancher. It gives replicated persistent volumes with snapshots and backups.

## CubeFS

- Official: <https://cubefs.io/>
- GitHub: <https://github.com/cubefs/cubefs>

CNCF Incubating cloud-native distributed file and object storage system designed for large-scale containerized workloads.

## MinIO

- Official: <https://min.io/>
- GitHub (original, archived): <https://github.com/minio/minio>
- GitHub (maintained fork): <https://github.com/chainguard-forks/minio>

High-performance S3-compatible object storage, deployable on Kubernetes for AI/ML and data lake workloads. The upstream project stopped publishing free community container images in October 2025 and later went read-only. Chainguard maintains a fork under its EmeritOSS program, with a companion fork of the console at <https://github.com/chainguard-forks/minio-console>.

## RustFS

- Official: <https://rustfs.com/>
- GitHub: <https://github.com/rustfs/rustfs>

Apache 2.0 licensed distributed object storage system written in Rust, with S3-compatible APIs, aimed at data lakes, AI, and analytics workloads.

## Velero

- Official: <https://velero.io/>
- GitHub: <https://github.com/vmware-tanzu/velero>

Open source tool to back up, restore, and migrate Kubernetes cluster resources and persistent volumes.

## OpenEBS / Mayastor

- Official: <https://openebs.io/>
- GitHub: <https://github.com/openebs/openebs>
- Mayastor GitHub: <https://github.com/openebs/mayastor>

CNCF Sandbox container-attached storage platform. Mayastor is its NVMe-based, high-performance storage engine for low-latency workloads.

## Volume Snapshotter (external-snapshotter)

- GitHub: <https://github.com/kubernetes-csi/external-snapshotter>

Kubernetes CSI sidecar and controller that implement the VolumeSnapshot API. They let CSI drivers expose snapshot functionality.

## Gemini

- GitHub: <https://github.com/FairwindsOps/gemini>

Fairwinds' Kubernetes operator that schedules and manages CSI VolumeSnapshots declaratively, with retention policies.
