# Agent Skills

Skills for improving human-AI collaboration and agent self-improvement.

## Available Skills

### agent-learnings

Extract agent self-improvement insights from session history. Analyzes interaction patterns to identify mistakes, corrections, and behavioral improvements.

**Use when:**
- Reflecting on agent failures
- Updating agent behaviors
- Building agent self-improvement logs

```bash
npx skills add Bitplanet-L1/agent-skills@agent-learnings
```

### human-agent-collaboration

Extract insights for humans on how to work effectively with AI agents. Produces guides on what works, what doesn't, and how to set agents up for success.

**Use when:**
- Learning to work better with agents
- Documenting collaboration patterns
- Onboarding team members on agent interaction

```bash
npx skills add Bitplanet-L1/agent-skills@human-agent-collaboration
```

## Installation

Install individual skills using the [skills CLI](https://skills.sh):

```bash
npx skills add Bitplanet-L1/agent-skills@<skill-name>
```

Or clone the entire repository:

```bash
git clone https://github.com/Bitplanet-L1/agent-skills.git
```

## About

These skills emerged from real-world experience operating AI agents. They capture patterns about:

- **Agent cognition** — How context windows work, why identity beats instructions
- **Verification discipline** — Why agents fail at "done" and how to fix it
- **Memory patterns** — What persists, what doesn't, and how to work around it
- **Communication** — Platform-specific formatting, link handling, voice patterns

For detailed documentation on these patterns, see:
- [Understanding Agents](https://github.com/Bitplanet-L1/genie-architecture/tree/main/understanding-agents)

## License

Apache 2.0 — See [LICENSE](LICENSE)

## Contributing

PRs welcome! If you've discovered patterns that improve human-AI collaboration, we'd love to include them.

---

Built by [Bitplanet](https://bitplanet.ai) · Powering [Deva](https://deva.me)
