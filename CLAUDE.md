# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository purpose

`awesome-k8s` is a curated, public link collection about Kubernetes and Cloud Native technologies. There is no code, no build, and no tests — content lives entirely in Markdown under `docs/`.

Because this repo is public, do not add internal information (AWS ARNs, internal project names, cluster names, IPs, hostnames, kubeconfig contents, employee names, etc.).

## Content structure

`docs/` is partitioned by topic area; each topic directory contains one Markdown file per sub-theme:

- `kubernetes/` — distributions, installers, node control, operating systems, baremetal, deployment
- `cluster-management/` — scalers, chaos engineering, finops, benchmarks, tests
- `deployment/` — gitops, ci-cd, image build, IDPs, app definition, deployment strategies
- `observability/` — metrics (prometheus), logging, tracing, UIs, long-term storage
- `infraestructure/` — storage, databases, serverless, eventing, ML, edge/IoT (note: directory is spelled "infraestructure", keep that spelling for existing links)
- `networking-services/`, `security-and-policies/`, `applications/`

Files named `98-tools.md` are "miscellaneous tools" catch-alls within a category. Preserve this convention when adding new entries that don't fit a more specific page.

## Entry format

Each tool/project is an H2 section following this pattern (see `docs/observability/observability.md` for canonical examples):

```markdown
## Project Name

- Official: <https://...>
- GitHub: <https://github.com/...>

One- to two-sentence neutral description. Note CNCF status (Graduated/Incubating/Sandbox) or Linux Foundation affiliation when applicable.
```

Keep descriptions vendor-neutral and factual. URLs are wrapped in `<...>` angle brackets.

## Working in this repo

- When adding a new project, place it in the most specific topical file; only fall back to `98-tools.md` if nothing fits.
- Maintain alphabetical or logical grouping consistent with the surrounding file — read the file before inserting.
- The `misc-document-manager` skill enforces a 150-line cap and English-by-default for markdown; split a topic page when it grows past that limit rather than letting it sprawl.
- The `misc-response-validator` skill (triggered by "verify it") checks CNCF/AWS claims against official docs via context7/awsdoc MCP — useful before committing descriptions of projects you're not certain about.
