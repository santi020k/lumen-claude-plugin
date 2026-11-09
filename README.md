# Lumen UI for Claude Code

Build, review, and migrate accessible Lumen interfaces across Astro, React, Web Components,
React Native, SwiftUI, and Jetpack Compose.

The plugin includes three skills, an optional reviewer agent, and the read-only Lumen MCP catalog.
Claude connects to the public Lumen MCP over HTTPS and sends catalog queries and tool arguments
to `https://mcp.lumen.santi020k.com/mcp`. The service returns public documentation and does not
persist tool arguments or responses. Do not include credentials, personal data, or private source
in catalog queries. No Lumen account or API key is required. See the
[Lumen privacy policy](https://lumen.santi020k.com/privacy).

For a local catalog, install from the original Lumen marketplace in Claude Code:

```text
/plugin install lumen-ui --marketplace santi020k/lumen
```

Lumen publishes this copy from its stable GitHub releases. Report issues and propose changes in
the [Lumen source repository](https://github.com/santi020k/lumen). See the
[Claude Code guide](https://github.com/santi020k/lumen/blob/main/docs/claude-code-plugin.md) and
[MCP documentation](https://lumen.santi020k.com/docs/mcp).

Released under the MIT license.
