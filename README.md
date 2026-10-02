# Hermes Knowledge Skill (Claude-Compatible)

A portable knowledge base for **Hermes Agent** (Nous Research) packaged for skill systems that support agent definitions and reference directories.

## Structure

```
claude-compatible-skill/
├── manifest.json              # Skill manifest (this format)
├── SKILL.md                   # Human-readable skill description
├── LICENSE.txt                # MIT License
├── agents/                    # Specialized agent definitions
│   ├── hermes-expert.md           # General Q&A
│   ├── hermes-mission-planner.md  # Mission brief generation
│   ├── hermes-troubleshooter.md   # Error diagnosis
│   ├── hermes-cost-optimizer.md   # Cost optimization
│   └── hermes-security-auditor.md # Security auditing
└── references/                # 21 reference files (380 KB)
    ├── 00-index-and-routing.md
    ├── 01-foundations-architecture.md
    ├── 02-install-vps-config-basics.md
    ├── 03-providers-and-models.md
    ├── 04-cli-command-reference-a.md
    ├── 04-cli-command-reference-b.md
    ├── 05-slash-commands-sessions-interactive.md
    ├── 06-config-keys-and-env-vars.md
    ├── 07-tools-and-toolsets.md
    ├── 08-terminal-backends.md
    ├── 09-messaging-gateway.md
    ├── 10-mcp-plugins-api.md
    ├── 11-skills-system.md
    ├── 12-memory-and-context.md
    ├── 13-scheduling-and-automation.md
    ├── 14-subagents-and-delegation.md
    ├── 15-learning-loop-and-advanced.md
    ├── 16-security-and-hardening.md
    ├── 17-vps-operations.md
    ├── 18-troubleshooting.md
    ├── 19-cost-and-optimization.md
    ├── 20-use-case-catalog.md
    ├── 21-glossary.md
    ├── 22-unverified-and-gaps.md
    └── 23-sources.md
```

## Installation

### For Skill Systems with Agent Support
```bash
cp -r claude-compatible-skill /path/to/your/skills/hermes-knowledge
# Load agents from agents/ directory
```

### For Reference-Only Use
```bash
cp -r claude-compatible-skill/references /path/to/knowledge/hermes-docs
```

### For Manual Use
```bash
# Browse references directly
cat claude-compatible-skill/references/04-cli-command-reference-a.md
```

## Agents

| Agent | Purpose | Best For |
|-------|---------|----------|
| `hermes-expert` | General Q&A on any Hermes topic | "How do I configure X?" "What's the command for Y?" |
| `hermes-mission-planner` | Generates complete mission briefs | "Plan a Hermes task: monitor my site..." |
| `hermes-troubleshooter` | Diagnoses errors and issues | "Hermes doctor shows X error..." |
| `hermes-cost-optimizer` | Cost reduction strategies | "Reduce my Hermes API costs..." |
| `hermes-security-auditor` | Security hardening review | "Audit my Hermes config..." |

## Reference Files Summary

| File | Topic | Size |
|------|-------|------|
| 00-index-and-routing.md | Routing index | 11 KB |
| 01-foundations-architecture.md | Architecture | 18 KB |
| 02-install-vps-config-basics.md | Installation | 19 KB |
| 03-providers-and-models.md | Providers/Models | 11 KB |
| 04-cli-command-reference-a.md | CLI Core | 28 KB |
| 04-cli-command-reference-b.md | CLI Extended | 14 KB |
| 05-slash-commands-sessions-interactive.md | Slash Commands | 18 KB |
| 06-config-keys-and-env-vars.md | Config/Env | 32 KB |
| 07-tools-and-toolsets.md | Tools/Toolsets | 30 KB |
| 08-terminal-backends.md | Terminal Backends | 13 KB |
| 09-messaging-gateway.md | Gateway | 25 KB |
| 10-mcp-plugins-api.md | MCP/Plugins | 17 KB |
| 11-skills-system.md | Skills System | 28 KB |
| 12-memory-and-context.md | Memory/Context | 17 KB |
| 13-scheduling-and-automation.md | Scheduling | 17 KB |
| 14-subagents-and-delegation.md | Subagents | 11 KB |
| 15-learning-loop-and-advanced.md | Advanced | 11 KB |
| 16-security-and-hardening.md | Security | 37 KB |
| 17-vps-operations.md | VPS Ops | 19 KB |
| 18-troubleshooting.md | Troubleshooting | 24 KB |
| 19-cost-and-optimization.md | Cost | 16 KB |
| 20-use-case-catalog.md | Use Cases | 19 KB |
| 21-glossary.md | Glossary | 44 KB |
| 22-unverified-and-gaps.md | Gaps | 19 KB |
| 23-sources.md | Sources | 19 KB |

## Version Compatibility

- **Hermes Agent**: v0.21.5 (tag `v2026.9.24`, Sep 24 2026)
- **Research Date**: Friday, October 2, 2026
- **Note**: Phase 3/4/5 research was not version-pinned; all files carry this caveat

## Known Gaps

See `references/22-unverified-and-gaps.md` for complete list of 30 unverified items.

## License

MIT — Same as Hermes Agent (Nous Research)