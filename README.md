# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of high-signal resources for **OpenClaw** (formerly **Moltbot**, originally **Clawdbot**): frameworks, skills, tooling, deployments, and real-world use cases.

## Navigation

- [Canonical Project and Aliases](#canonical-project-and-aliases)
- [Contributing](#contributing)
- [Curated Collections](#curated-collections)
- [Developer Tooling and Observability](#developer-tooling-and-observability)
- [Deployment and Operations](#deployment-and-operations)
- [License](#license)
- [Localization and Regional Forks](#localization-and-regional-forks)
- [MCP and Tool Servers](#mcp-and-tool-servers)
- [Memory and Context Systems](#memory-and-context-systems)
- [Official Resources](#official-resources)
- [Security Notes](#security-notes)
- [Skills and Skill Indexes](#skills-and-skill-indexes)
- [Tag Legend](#tag-legend)
- [Use-Case Libraries](#use-case-libraries)

## Tag Legend

- `[Alias]` - legacy naming (Moltbot/Clawdbot) continuity.
- `[Archived]` - historical archive or legacy storage.
- `[Catalog]` - index/list of many resources.
- `[Community]` - community-maintained project.
- `[Infra]` - deployment, packaging, or infrastructure.
- `[MCP]` - Model Context Protocol related.
- `[Official]` - maintained by OpenClaw org or official docs/site.
- `[OSS]` - open-source code.
- `[Skills]` - focused on OpenClaw skill discovery or implementation.

## Canonical Project and Aliases

- [clawdbot/clawdbot](https://github.com/clawdbot/clawdbot) `[Alias]`
  - Legacy alias URL redirecting to the canonical repository.
- [moltbot/moltbot](https://github.com/moltbot/moltbot) `[Alias]`
  - Legacy alias URL redirecting to the canonical repository.
- [openclaw/openclaw](https://github.com/openclaw/openclaw) `[Official] [OSS]`
  - Core project.

## Official Resources

- [Channels](https://docs.openclaw.ai/channels) `[Official]`
- [Discord](https://discord.gg/clawd) `[Official]`
- [Docker Install](https://docs.openclaw.ai/install/docker) `[Official] [Infra]`
- [FAQ](https://docs.openclaw.ai/start/faq) `[Official]`
- [Gateway Security](https://docs.openclaw.ai/gateway/security) `[Official]`
- [Getting Started](https://docs.openclaw.ai/start/getting-started) `[Official]`
- [Onboarding Wizard](https://docs.openclaw.ai/start/wizard) `[Official]`
- [OpenClaw Docs](https://docs.openclaw.ai) `[Official]`
- [OpenClaw Website](https://openclaw.ai) `[Official]`
- [openclaw/nix-openclaw](https://github.com/openclaw/nix-openclaw) `[Official] [OSS] [Infra]`
- [Showcase](https://docs.openclaw.ai/start/showcase) `[Official]`
- [Skills Docs](https://docs.openclaw.ai/tools/skills) `[Official] [Skills]`

## Curated Collections

- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) `[Community] [Catalog]`
  - Real-world usage patterns and domain examples.
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) `[Community] [Catalog] [Skills]`
  - Major community index of OpenClaw skills (with Moltbot/Clawdbot lineage context).

## Skills and Skill Indexes

- [BankrBot/openclaw-skills](https://github.com/BankrBot/openclaw-skills) `[Community] [OSS] [Skills]`
  - Community skill library with automation and finance-oriented integrations.
- [clawdbot/skills](https://github.com/clawdbot/skills) `[Alias] [Skills] [Archived]`
  - Legacy alias path to historical skill archive content.
- [lekt9/unbrowse-openclaw](https://github.com/lekt9/unbrowse-openclaw) `[Community] [OSS] [Skills]`
  - API-skill generation workflow from captured web/API traffic.
- [openclaw/skills](https://github.com/openclaw/skills) `[Official] [OSS] [Skills] [Archived]`
  - Archived versions of skills published on ClawHub.

## MCP and Tool Servers

- [Enderfga/openclaw-claude-code-skill](https://github.com/Enderfga/openclaw-claude-code-skill) `[Community] [OSS] [Skills] [MCP]`
  - OpenClaw skill integration for Claude Code workflows via MCP.
- [Helms-AI/openclaw-mcp-server](https://github.com/Helms-AI/openclaw-mcp-server) `[Community] [OSS] [MCP]`
  - MCP server exposing OpenClaw Gateway tools.
- [openclaw/openclaw#4834](https://github.com/openclaw/openclaw/issues/4834) `[Official] [MCP]`
  - Native MCP support discussion/history.
- [openclaw/openclaw#5121](https://github.com/openclaw/openclaw/pull/5121) `[Official] [MCP]`
  - MCP server support implementation PR.

## Memory and Context Systems

- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) `[Community] [OSS]`
  - Memory operating system with OpenClaw ecosystem adoption.
- [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) `[Community] [OSS]`
  - Agent memory layer for long-lived assistants.
- [oceanbase/powermem](https://github.com/oceanbase/powermem) `[Community] [OSS]`
  - Long-term memory infrastructure referenced in Moltbot/Clawdbot plugin contexts.

## Developer Tooling and Observability

- [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) `[Community] [OSS]`
  - Token/cost tracking across coding assistants including OpenClaw workflows.
- [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) `[Community] [OSS] [Skills]`
  - Transferable skill-pack patterns useful for OpenClaw skill design.
- [luccast/crabwalk](https://github.com/luccast/crabwalk) `[Community] [OSS]`
  - Monitoring companion for OpenClaw agent sessions.
- [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) `[Community] [OSS] [Skills]`
  - Planning workflow skill pattern used in agentic repos.
- [refly-ai/refly](https://github.com/refly-ai/refly) `[Community] [OSS] [Skills]`
  - Skills and workflow builder ecosystem with overlap for agent tooling.

## Deployment and Operations

- [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) `[Community] [OSS] [Infra]`
  - Self-hosted server panel often used for OpenClaw deployments.
- [badrisnarayanan/antigravity-claude-proxy](https://github.com/badrisnarayanan/antigravity-claude-proxy) `[Community] [OSS] [Infra]`
  - Proxy/routing support for model access in assistant workflows.
- [BlockRunAI/ClawRouter](https://github.com/BlockRunAI/ClawRouter) `[Community] [OSS] [Infra]`
  - Routing and cost optimization layer for OpenClaw-style agent setups.
- [miaoxworld/OpenClawInstaller](https://github.com/miaoxworld/OpenClawInstaller) `[Community] [OSS] [Infra]`
  - Installer and setup automation helper.

## Localization and Regional Forks

- [1186258278/OpenClawChineseTranslation](https://github.com/1186258278/OpenClawChineseTranslation) `[Community] [OSS]`
  - Translation-focused setup repository.
- [jiulingyun/openclaw-cn](https://github.com/jiulingyun/openclaw-cn) `[Community] [OSS]`
  - Chinese-oriented OpenClaw adaptation.

## Use-Case Libraries

- [Creative and Building](https://github.com/hesamsheikh/awesome-openclaw-usecases#creative--building) `[Community] [Catalog]`
- [Productivity](https://github.com/hesamsheikh/awesome-openclaw-usecases#productivity) `[Community] [Catalog]`
- [Research and Learning](https://github.com/hesamsheikh/awesome-openclaw-usecases#research--learning) `[Community] [Catalog]`
- [Social Media Use Cases](https://github.com/hesamsheikh/awesome-openclaw-usecases#social-media) `[Community] [Catalog]`

## Security Notes

- Treat third-party skills as untrusted code.
- Review repository source and maintainer profile before install.
- Start with least privilege and allow-listed tools.
- Keep API keys out of prompts, logs, and skill templates.
- Prefer sandboxed execution for untrusted integrations.
- Use official references first: [Skills Docs](https://docs.openclaw.ai/tools/skills) and [Gateway Security](https://docs.openclaw.ai/gateway/security).

## Contributing

PRs are welcome for:

- New high-signal OpenClaw ecosystem links.
- Better categorization and metadata tags.
- Dead-link cleanup and stale project removal.

Please include a short relevance note when submitting a new entry.

## License

MIT. See [`LICENSE`](LICENSE).
