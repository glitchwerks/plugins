# glitchwerks plugins marketplace

Claude Code plugins published by [@glitchwerks](https://github.com/glitchwerks).

## Status

**Bootstrap** — the marketplace exists and registers cleanly, but the `plugins[]` array is currently empty. Entries will be added as the plugins reach their first releasable state.

## Install

Register this marketplace once:

```bash
claude plugin marketplace add github:glitchwerks/plugins
```

Then install any plugin from it by name:

```bash
claude plugin install <plugin-name>@glitchwerks
```

(Nothing to install yet — see "Upcoming" below.)

## Upcoming

| Plugin | Source | Status |
| --- | --- | --- |
| `claude-prospector` | [glitchwerks/claude-prospector](https://github.com/glitchwerks/claude-prospector) | Pending Phase 1 of the v0.4.0 plan — entry will be added once `.claude-plugin/plugin.json` lands in the plugin repo |
| `claude-wayfinder` | [glitchwerks/claude-wayfinder](https://github.com/glitchwerks/claude-wayfinder) | Currently self-hosting its own marketplace; migration into this one is tracked as a separate concurrent task |

`claude-prospector` is the rebranded successor to `claude-usage` — a token-usage / billing-window dashboard for Claude Code, packaged as a plugin with a skill, slash command, and opt-in Stop-hook auto-regen.

`claude-wayfinder` is a typed, auditable dispatch matcher for Claude Code — post-cognitive routing with a deterministic-first scoring kernel.

## Schema

Entries follow the [Claude Code marketplace schema](https://anthropic.com/claude-code/marketplace.schema.json). Each plugin entry pins a specific commit SHA from the plugin's source repo so installs are reproducible.

## License

MIT. See [LICENSE](LICENSE).
