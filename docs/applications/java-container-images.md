# Java Container Images

## Microsoft Build of OpenJDK (containers)

- Official: <https://learn.microsoft.com/en-us/java/openjdk/containers>
- GitHub: <https://github.com/microsoft/openjdk>

Microsoft's free, supported distribution of OpenJDK with official container images for Linux and Windows base images.

## Distroless (GCR)

- GitHub: <https://github.com/GoogleContainerTools/distroless>
- Images: <https://gcr.io/distroless>

Google Container Tools' "distroless" Java images contain only the JRE and your app — no shell, package manager, or extra OS surface.

## Chainguard

- Official: <https://www.chainguard.dev/>
- GitHub: <https://github.com/chainguard-images/images>

Chainguard provides minimal, zero-CVE container images (including JDK/JRE flavors) built on Wolfi, with signed SBOMs and rebuilds.

## Amazon Corretto

- Official: <https://aws.amazon.com/corretto/>
- GitHub: <https://github.com/corretto/corretto-21> (per-version repos)

AWS's no-cost, multiplatform, production-ready distribution of OpenJDK, with official container images for multiple LTS versions.

## RapidFort

- Official: <https://www.rapidfort.com/>

RapidFort provides hardened, near-zero-CVE container images (RapidFort Curated Images) for popular runtimes including Java/JDK.

## Bellsoft Liberica Alpaquita

- Official: <https://bell-sw.com/pages/alpaquita-containers/>
- Alpaquita Linux: <https://bell-sw.com/alpaquita-linux/>

BellSoft's small, musl/glibc-based Linux distribution paired with Liberica JDK, producing very small, optimized Java container images.

## Red Hat UBI

- Official: <https://www.redhat.com/en/products/universal-base-image>
- OpenJDK UBI images: <https://catalog.redhat.com/software/containers/search?q=openjdk>

Red Hat Universal Base Image with OpenJDK runtime images — freely redistributable, supported on OpenShift and other Kubernetes distros.
