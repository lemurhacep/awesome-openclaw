# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of OpenClaw resources, ecosystem projects, and practical references.

OpenClaw is one of the fastest-growing open-source AI assistant/framework projects and was previously known as **Moltbot** and originally **Clawdbot**.

## Canonical Project + Aliases

- [openclaw/openclaw](https://github.com/openclaw/openclaw) - Official OpenClaw repository.
- [moltbot/moltbot](https://github.com/moltbot/moltbot) - Legacy alias URL; redirects to `openclaw/openclaw`.
- [clawdbot/clawdbot](https://github.com/clawdbot/clawdbot) - Legacy alias URL; redirects to `openclaw/openclaw`.

## Official Resources

- [OpenClaw Website](https://openclaw.ai)
- [OpenClaw Docs](https://docs.openclaw.ai)
- [Getting Started](https://docs.openclaw.ai/start/getting-started)
- [Onboarding Wizard](https://docs.openclaw.ai/start/wizard)
- [Skills Docs](https://docs.openclaw.ai/tools/skills)
- [Gateway Security](https://docs.openclaw.ai/gateway/security)
- [Channels](https://docs.openclaw.ai/channels)
- [Docker Install](https://docs.openclaw.ai/install/docker)
- [Nix Setup](https://github.com/openclaw/nix-openclaw)
- [Showcase](https://docs.openclaw.ai/start/showcase)
- [FAQ](https://docs.openclaw.ai/start/faq)
- [Discord](https://discord.gg/clawd)

## Must-Include Awesome Lists

- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - Large, category-organized skills index (OpenClaw/Moltbot/Clawdbot lineage explicitly documented).
- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) - Community collection of real-world use cases.
- [SamurAIGPT/awesome-openclaw](https://github.com/SamurAIGPT/awesome-openclaw) - Broader curated resources/tools/tutorials list.

## Topic Hubs (Primary Discovery)

- [Topic: `openclaw`](https://github.com/topics/openclaw)
- [Topic: `moltbot`](https://github.com/topics/moltbot)
- [Topic: `clawdbot`](https://github.com/topics/clawdbot)

## Topic Scan Snapshot (Most stars sort, checked Feb 9, 2026)

- `openclaw` topic: 505 public repositories.
- `moltbot` topic: 164 public repositories.
- `clawdbot` topic: 251 public repositories.

## Core Ecosystem Repositories

- [openclaw/openclaw](https://github.com/openclaw/openclaw) - Core framework/personal AI assistant.
- [openclaw/skills](https://github.com/openclaw/skills) - Archived versions of ClawHub skills.
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - Massive skills catalog.
- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) - Practical usage patterns.
- [SamurAIGPT/awesome-openclaw](https://github.com/SamurAIGPT/awesome-openclaw) - Additional ecosystem curation.

## Skills, MCP, and Agent Tooling

- [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) - Manus-style planning skill workflow.
- [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) - Skill collection for Obsidian workflows.
- [refly-ai/refly](https://github.com/refly-ai/refly) - Open-source skills builder and workflow tooling.
- [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) - Token usage tracking across agent/coding tools including OpenClaw.
- [luccast/crabwalk](https://github.com/luccast/crabwalk) - Real-time companion monitor for OpenClaw agents.

## Memory and Long-Context Systems

- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) - Memory OS positioned for OpenClaw/Moltbot/Clawdbot ecosystems.
- [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) - Memory system for proactive/always-on agents.
- [oceanbase/powermem](https://github.com/oceanbase/powermem) - Long-term memory infrastructure with Moltbot/Clawdbot plugin support.

## Routing, Model Access, and Integrations

- [badrisnarayanan/antigravity-claude-proxy](https://github.com/badrisnarayanan/antigravity-claude-proxy) - Proxy layer for Claude/Gemini access in OpenClaw workflows.
- [BlockRunAI/ClawRouter](https://github.com/BlockRunAI/ClawRouter) - LLM routing/cost optimization project tagged for OpenClaw usage.
- [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) - Agent/coding desktop with OpenClaw-tagged ecosystem links.
- [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) - Local cowork/agent surface with OpenClaw ecosystem tags.

## Deployment, Ops, and Setup Helpers

- [miaoxworld/OpenClawInstaller](https://github.com/miaoxworld/OpenClawInstaller) - One-click installer/deployment helper.
- [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) - Linux server management UI with OpenClaw-tagged deployment usage.

## Localization and Regional Forks

- [jiulingyun/openclaw-cn](https://github.com/jiulingyun/openclaw-cn) - Chinese-focused OpenClaw distribution/adaptation.
- [1186258278/OpenClawChineseTranslation](https://github.com/1186258278/OpenClawChineseTranslation) - Chinese translation + setup-oriented distribution.

## Practical Use-Case Indexes

- [awesome-openclaw-usecases: Social Media](https://github.com/hesamsheikh/awesome-openclaw-usecases#social-media)
- [awesome-openclaw-usecases: Creative & Building](https://github.com/hesamsheikh/awesome-openclaw-usecases#creative--building)
- [awesome-openclaw-usecases: Productivity](https://github.com/hesamsheikh/awesome-openclaw-usecases#productivity)
- [awesome-openclaw-usecases: Research & Learning](https://github.com/hesamsheikh/awesome-openclaw-usecases#research--learning)

## Security-First Notes

- Treat third-party skills as untrusted code.
- Review skill source before enabling it.
- Prefer sandboxed runs for risky skills and untrusted inputs.
- Keep secrets out of prompts/logs and configure env injection carefully.
- Start with official docs: [Skills Security Notes](https://docs.openclaw.ai/tools/skills) and [Gateway Security](https://docs.openclaw.ai/gateway/security).

## Curator Notes

This list intentionally includes projects tagged across `openclaw`, `moltbot`, and `clawdbot` to preserve discoverability through the rename timeline.

## Contributing

PRs are welcome for:

- New high-signal repositories in the OpenClaw ecosystem.
- Better categorization of existing links.
- Removal of stale or low-quality entries.

When adding links, prefer repositories with:

- Clear OpenClaw/Moltbot/Clawdbot relevance.
- Active maintenance.
- Real usage evidence (stars, issues, docs, or community adoption).

## License

MIT. See [`LICENSE`](LICENSE).
