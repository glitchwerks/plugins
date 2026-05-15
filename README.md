# glitchwerks plugins marketplace

Claude Code plugins published by [@glitchwerks](https://github.com/glitchwerks).

## Install

Register this marketplace once:

```bash
claude plugin marketplace add glitchwerks/plugins
```

Then install any plugin from it by name:

```bash
claude plugin install <plugin-name>@glitchwerks
```

## Plugins

| Plugin | Source | Description |
| --- | --- | --- |
| `claude-wayfinder` | [glitchwerks/claude-wayfinder](https://github.com/glitchwerks/claude-wayfinder) | Helps Claude make deterministic, auditable choices about which agent and skills to use for a given task — replacing prose-scanning agent/skill selection with a typed scoring kernel. |

## Upcoming

| Plugin | Source | Status |
| --- | --- | --- |
| `claude-prospector` | [glitchwerks/claude-prospector](https://github.com/glitchwerks/claude-prospector) | Pending Phase 1 of the v0.4.0 plan — entry will be added once `.claude-plugin/plugin.json` lands in the plugin repo |

`claude-prospector` is the rebranded successor to `claude-usage` — a token-usage / billing-window dashboard for Claude Code, packaged as a plugin with a skill, slash command, and opt-in Stop-hook auto-regen.

## Schema

Entries follow the [Claude Code marketplace schema](https://anthropic.com/claude-code/marketplace.schema.json). Each plugin entry pins a specific commit SHA from the plugin's source repo so installs are reproducible.

## License

MIT. See [LICENSE](LICENSE).
