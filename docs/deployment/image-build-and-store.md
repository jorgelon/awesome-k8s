# Image Build and Store

## Shipwright

- Official: <https://shipwright.io/>
- GitHub: <https://github.com/shipwright-io/build>

CNCF Sandbox framework for building container images on Kubernetes, with strategies for Buildpacks, Buildah, Kaniko, ko, and more.

## Kaniko

- GitHub: <https://github.com/GoogleContainerTools/kaniko>

Google Container Tools project that builds container images from a Dockerfile inside a container or Kubernetes cluster without privileged access.

## Harbor

- Official: <https://goharbor.io/>
- GitHub: <https://github.com/goharbor/harbor>

CNCF Graduated open source registry that stores, signs, and scans container images and OCI artifacts, with replication and RBAC.

## Distroless and slim images

- Distroless GitHub: <https://github.com/GoogleContainerTools/distroless>

"Distroless" images contain only the application and its runtime dependencies, with no shell or package manager — minimizing attack surface and size.

## Slimtoolkit

- Official: <https://slimtoolkit.org/>
- GitHub: <https://github.com/slimtoolkit/slim>

Open source tool (formerly DockerSlim) that minifies and hardens container images automatically, often reducing size by 30x.

## Bif (Fairwinds)

- GitHub: <https://github.com/FairwindsOps/bif>

Fairwinds' tool for working with container image build information and metadata as part of their cloud-native image tooling. (Confirm exact scope upstream.)

## Sigstore

- Official: <https://www.sigstore.dev/>
- GitHub: <https://github.com/sigstore>

OpenSSF project for signing, verifying, and providing transparency for software artifacts and container images (Cosign, Fulcio, Rekor).

## Saffire (Fairwinds)

- GitHub: <https://github.com/FairwindsOps/saffire>

Fairwinds' open source tool in the container image build and store space, part of their cloud-native image tooling alongside Bif. (Confirm exact scope upstream.)

## Buildah

- Official: <https://buildah.io/>
- GitHub: <https://github.com/containers/buildah>

CNCF/Containers project for building OCI container images without requiring a daemon, scriptable from shell.

## BuildKit

- GitHub: <https://github.com/moby/buildkit>

Moby project providing an efficient, cacheable, concurrent image build engine — the backend used by modern Docker builds.

## Podman

- Official: <https://podman.io/>
- GitHub: <https://github.com/containers/podman>

Daemonless, rootless container engine from the Containers project for running and building OCI containers and pods.

## Dragonfly

- Official: <https://d7y.io/>
- GitHub: <https://github.com/dragonflyoss/dragonfly>

CNCF Graduated peer-to-peer (P2P) image and file distribution system that accelerates large-scale container image pulls.
