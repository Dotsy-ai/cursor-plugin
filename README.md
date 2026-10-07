# Dotsy for Cursor and Grok Build

One-click [Dotsy](https://dotsy.ai) MCP for Cursor and [Grok Build](https://x.ai/grok). Your AI builds, edits, and publishes sites; Dotsy hosts them.

MCP endpoint: `https://mcp.dotsy.ai/mcp`

## Install

### Cursor

1. Install this plugin from the Cursor Marketplace (or clone locally for testing).
2. Open **Cursor Settings → Tools & MCP**.
3. Click **Connect** next to `dotsy` and sign in to Dotsy in the browser.

### Grok Build

1. Install this plugin from the [xAI Plugin Marketplace](https://github.com/xai-org/plugin-marketplace).
2. Click **Connect** next to `dotsy` and sign in to Dotsy in the browser via OAuth.

## Local test

```bash
cp -R . ~/.cursor/plugins/local/dotsy
```

Reload Cursor, then connect Dotsy under Tools & MCP.

## Docs

- Site: https://dotsy.ai
- MCP setup on the homepage: paste `https://mcp.dotsy.ai/mcp` into any MCP client
- CLI (separate): `npm i -g @dotsy-ai/cli`

## License

MIT
