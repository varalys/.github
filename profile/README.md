# Varalys

Privacy-first tools for developers and AI
---
## Projects

### [Redactyl](https://github.com/varalys/redactyl)

Secret detection for cloud-native artifacts. Finds sensitive data hidden in container images, Helm charts, Kubernetes manifests, and nested archives—places traditional scanners can't reach.

- Streams complex archives without disk extraction
- Tracks secrets through nested paths (`chart.tgz::templates/secret.yaml::line-123`)
- Built on proven Gitleaks detection patterns
- Zero telemetry, privacy-first design

### [Lore](https://github.com/varalys/lore)

Captures AI coding sessions and links them to git commits. Preserves the reasoning and decisions behind code changes and context that git alone doesn't keep.

- Supports 10+ AI tools (Claude Code, Aider, Continue.dev, Cline, and more)
- Bidirectional linking: commit → sessions, session → commits
- Full-text search across all conversations
- 100% local storage, no cloud sync

---

<sub>All projects are built with privacy in mind.</sub>
