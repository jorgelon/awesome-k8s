# Git Platforms

Platforms that host Git repositories and the collaboration around them. The first
section covers the traditional forges. The second section covers newer platforms
built around coding agents, where an agent session is a first class object.

## Traditional Platforms

### GitHub

- Official: <https://github.com/>
- Self hosted: Yes, with GitHub Enterprise Server

Microsoft owned Git hosting platform with pull requests, issues, GitHub Actions
for CI/CD, and a container and package registry.

### GitLab

- Official: <https://about.gitlab.com/>
- GitHub: <https://gitlab.com/gitlab-org/gitlab>
- Self hosted: Yes

Git platform with merge requests, an integrated CI/CD engine, a container
registry, and a self hosted Community Edition under an open source license.

### Gitea

- Official: <https://about.gitea.com/>
- GitHub: <https://github.com/go-gitea/gitea>
- Self hosted: Yes

Lightweight self hosted Git service written in Go, with pull requests, issues,
packages, and Gitea Actions, which is compatible with GitHub Actions workflows.

### Forgejo

- Official: <https://forgejo.org/>
- GitHub: <https://codeberg.org/forgejo/forgejo>
- Self hosted: Yes

Community driven fork of Gitea, hosted by Codeberg e.V. and published under a
copyleft license. It adds federation work based on the ActivityPub protocol.

### Bitbucket

- Official: <https://bitbucket.org/>
- Self hosted: Yes, with the Data Center edition

Atlassian Git platform with pull requests, Bitbucket Pipelines for CI/CD, and
native links to Jira issues. A self hosted Data Center edition is available.

### Azure DevOps Repos

- Official: <https://azure.microsoft.com/products/devops/repos/>
- Self hosted: Yes, with Azure DevOps Server

Microsoft hosted Git repositories inside Azure DevOps, with pull request
policies and a link to Azure Pipelines and Azure Boards.

### Codeberg

- Official: <https://codeberg.org/>
- Self hosted: No, it is a hosted service. You can self host the Forgejo software it runs

Non profit Git hosting service operated by Codeberg e.V. in Germany, running
Forgejo and accepting only projects under a free software license.

### SourceHut

- Official: <https://sourcehut.org/>
- Self hosted: Yes

Minimal hosting suite with no JavaScript in the web interface. It works through
mailing lists, patch email, ticket trackers, and a CI service.

### OneDev

- GitHub: <https://github.com/theonedev/onedev>
- Self hosted: Yes

Self hosted Git server with a built in CI/CD engine, code search, issue
tracking, and Kanban boards, packaged as a single container image.

### Radicle

- Official: <https://radicle.xyz/>
- Self hosted: Yes, every user runs a node

Peer to peer code collaboration stack. Repositories, issues, and patches
replicate between nodes over a gossip network, without a central server.

## Agentic Era Platforms

### Delta

- Official: <https://delta.dev/>
- Self hosted: No, hosted only

Zed Industries platform where the unit of work is a thread, which holds the
conversation with the agent together with the checkout it edits. It stores fine
grained operations in DeltaDB, its own version control layer, and interoperates
with Git so that other people still see a normal repository.

### Cursor Origin

- Official: <https://cursor.com/changelog/origin-code-hosting>
- Self hosted: No, hosted only

Git hosting built into the Cursor editor, with repositories, pull requests, code
browsing, and two way synchronization with GitHub. Cursor agents run against the
hosted repositories, either on the workstation or in a cloud sandbox.

### Entire

- Official: <https://entire.io/>
- GitHub: <https://github.com/entireio>
- Self hosted: No, hosted only. The command line tool is open source

Git platform from Thomas Dohmke, a former GitHub chief executive officer. It
records every agent session next to the commits, so each line links back to the
prompt and the reasoning that produced it. It also mirrors repositories in
several regions. The command line tool is open source under the MIT license.

### GitLab Project Switch

- News: <https://www.publickey1.jp/blog/26/gitlabaigitproject_switch50.html>
- Self hosted: No, hosted only

Git compatible source code management service that GitLab announced in June 2026
for agent driven workloads. It separates compute from storage and adds a routing
and caching layer above both. GitLab claims large gains in speed and a lower
token cost. No official English page is available yet.

### Graphite

- Official: <https://graphite.dev/>
- Self hosted: No, hosted only

Code review platform for stacked pull requests, small changes that depend on
each other and merge in order. It adds automated review on top of GitHub.
Cursor acquired the company in December 2025.
