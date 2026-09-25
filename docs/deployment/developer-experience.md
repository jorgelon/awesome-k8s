# Developer Experience

## Score

- Official: <https://score.dev/>
- GitHub: <https://github.com/score-spec/spec>

CNCF Sandbox developer-centric and platform-agnostic workload specification. Developers declare the workload once in a `score.yaml` file, and a platform converts it to the target environment.

## Telepresence

- Official: <https://www.telepresence.io/>
- GitHub: <https://github.com/telepresenceio/telepresence>

CNCF project that connects a workstation to a Kubernetes cluster. A local process receives real cluster traffic, so the developer skips the build, push, and deploy cycle.

## mirrord

- Official: <https://metalbear.com/mirrord/>
- GitHub: <https://github.com/metalbear-co/mirrord>

MIT licensed tool from MetalBear that runs a local process in the context of a live Kubernetes cluster. It routes traffic, files, and environment variables through a target pod, and ships as a CLI, a VS Code extension, and an IntelliJ plugin.

## Gefyra

- Official: <https://gefyra.dev/>
- GitHub: <https://github.com/gefyrahq/gefyra>

Apache 2.0 licensed tool that bridges a local container into an existing Kubernetes cluster. The local container keeps the network identity of the pod that it replaces.

## Skaffold

- Official: <https://skaffold.dev/>
- GitHub: <https://github.com/GoogleContainerTools/skaffold>

Apache 2.0 licensed command line tool from Google for continuous development on Kubernetes. It watches the source code and repeats the build, push, and deploy steps on every change.

## Tilt

- Official: <https://tilt.dev/>
- GitHub: <https://github.com/tilt-dev/tilt>

Apache 2.0 licensed development tool for microservices on Kubernetes, now owned by Docker. It watches files, rebuilds images, updates the cluster, and shows the state of every service in one UI.

## DevSpace

- Official: <https://www.devspace.sh/>
- GitHub: <https://github.com/devspace-sh/devspace>

CNCF Sandbox command line tool from Loft Labs to develop, deploy, and debug applications in Kubernetes. It syncs local files into a running container and gives hot reload without a new image build.

## Okteto

- Official: <https://okteto.com/>
- GitHub: <https://github.com/okteto/okteto>

Apache 2.0 licensed CLI that swaps a deployment for a development container and syncs local code into it. The company also sells a commercial platform that builds on the CLI.

## Microcks

- Official: <https://microcks.io/>
- GitHub: <https://github.com/microcks/microcks>

CNCF Incubating tool that turns API definitions into running mocks and reuses them as tests. It reads OpenAPI, AsyncAPI, gRPC, GraphQL, Postman, and SoapUI assets, and ships Helm charts plus Testcontainers modules for local test loops.

## Garden

- Official: <https://garden.io/>
- GitHub: <https://github.com/garden-io/garden>

MPL-2.0 licensed automation tool that creates production-like environments on demand for development, testing, and CI. One configuration set covers every stage of the delivery pipeline.
