# Retrovee draft workflow

This edition builds on [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo). Original copyright and licensing are in [LICENSE](LICENSE).

Upstream main branch ZIP SHA-256: `b3f4e575771164ae00982aa84554bfb13dfffc2dfea03d2d83b9ac8990e1dfc6`.

Use the [`retail-technical-seo` skill](codex-skills/retail-technical-seo/SKILL.md) for the Codex draft workflow. Copy the entire skill directory into your Codex skills directory. This skill has no runtime dependencies. The upstream tools retain their separate setup instructions in the original README.

Keep credentials, customer data and performance exports out of Git. Review proposed external changes and get approval before making them live.

## GitHub Actions

The original workflows are retained in `.github/upstream-workflows/` for review. Enable selected workflows only after checking their triggers, tokens and publish targets.
