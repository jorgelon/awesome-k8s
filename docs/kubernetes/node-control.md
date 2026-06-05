# Node Control

## Kubermatic Machine Controller

- Official: <https://docs.kubermatic.com/kubermatic/main/architecture/concept/kkp-concepts/machine-controller/>
- GitHub: <https://github.com/kubermatic/machine-controller>

Kubermatic controller that manages worker node lifecycle (create, scale, delete) across cloud providers via Machine and MachineDeployment CRDs.

## Kured (Kubernetes Reboot Daemon)

- Official: <https://kured.dev/>
- GitHub: <https://github.com/kubereboot/kured>

CNCF Sandbox daemon that performs safe automatic node reboots after OS package updates, draining workloads and reboot-coordinating across the cluster.

## Flatcar Linux Update Operator

- GitHub: <https://github.com/flatcar/flatcar-linux-update-operator>

Operator that coordinates Flatcar Container Linux OS updates across a Kubernetes cluster by safely draining and rebooting nodes.

## Cluster Autoscaler

- Official: <https://kubernetes.io/docs/concepts/cluster-administration/cluster-autoscaling/>
- GitHub: <https://github.com/kubernetes/autoscaler>

Kubernetes SIG project that automatically adjusts the size of a cluster's node pools based on pending pods and node utilization, across many cloud providers.

## VMware VM Operator

- GitHub: <https://github.com/vmware-tanzu/vm-operator>

Kubernetes operator that manages vSphere virtual machines as Kubernetes resources, used by vSphere with Tanzu and related platforms.

## Karpenter

- Official: <https://karpenter.sh/>
- GitHub: <https://github.com/kubernetes-sigs/karpenter>

Open source, just-in-time node provisioner originally built by AWS that launches right-sized nodes in response to pending pods, faster than Cluster Autoscaler.

## Karpenter Azure

- GitHub: <https://github.com/Azure/karpenter-provider-azure>

Azure provider implementation of Karpenter for AKS, providing node autoprovisioning using Azure VM Scale Sets and standalone VMs.

## system-upgrade-controller (Rancher)

- GitHub: <https://github.com/rancher/system-upgrade-controller>

Rancher controller that applies upgrade Plans to nodes (OS, kubelet, K3s/RKE2, etc.) via Jobs, driving cluster-wide rolling upgrades.

## Amazon EKS Auto Mode

- Official: <https://docs.aws.amazon.com/eks/latest/userguide/automode.html>

Managed EKS mode where AWS automatically provisions and manages compute, networking, and storage (via integrated Karpenter), removing data-plane operational overhead.

## GKE Autopilot

- Official: <https://cloud.google.com/kubernetes-engine/docs/concepts/autopilot-overview>

Google Kubernetes Engine operating mode where Google manages the entire node lifecycle and you pay per pod, with hardened defaults and SLA-backed availability.
