# Lumen UI for Claude Code

Build, review, and migrate accessible Lumen interfaces across Astro, React, Web Components,
React Native, SwiftUI, and Jetpack Compose.

The plugin includes three skills, an optional reviewer agent, and the read-only Lumen MCP catalog.
Claude Code installs the pinned catalog and its locked dependencies from the public npm registry
when it installs or updates the plugin. The catalog runs locally with Node.js 20.20 or later
and does not send tool inputs to an external service. No Lumen account or API key is required.

Install from the original Lumen marketplace in Claude Code:

```text
/plugin install lumen-ui --marketplace santi020k/lumen
```

Lumen publishes this copy from its stable GitHub releases. Report issues and propose changes in
the [Lumen source repository](https://github.com/santi020k/lumen). See the
[Claude Code guide](https://github.com/santi020k/lumen/blob/main/docs/claude-code-plugin.md) and
[MCP documentation](https://lumen.santi020k.com/docs/mcp).

Released under the MIT license.
