# Coinmarketcap MCP Server

MCP server for Coinmarketcap. Agent-ready API for Coinmarketcap.

Hosted at [coinmarketcap.mcp.junct.dev/mcp](https://coinmarketcap.mcp.junct.dev/mcp). Free to use. No auth. No API key required.

Part of [Junct](https://junct.dev) — the agent-readiness layer for web3.

## Quick Start

Add to your MCP client config (Claude Desktop, Cursor, Windsurf):

```json
{
  "mcpServers": {
    "coinmarketcap": {
      "url": "https://coinmarketcap.mcp.junct.dev/mcp",
      "transport": "streamable-http"
    }
  }
}
```

## About

This MCP server is **deterministically generated** from the Coinmarketcap API specification. Every tool maps 1:1 to a real API endpoint — no hallucinated endpoints.

- **Protocol:** Coinmarketcap
- **Endpoint:** `https://coinmarketcap.mcp.junct.dev/mcp`
- **Transport:** Streamable HTTP
- **Auth:** None required
- **Documentation:** [coinmarketcap.mcp.junct.dev/llms.txt](https://coinmarketcap.mcp.junct.dev/llms.txt)

## Links

- [Junct Dashboard](https://junct.dev/servers/coinmarketcap)
- [llms.txt](https://coinmarketcap.mcp.junct.dev/llms.txt)
- [agents.md](https://coinmarketcap.mcp.junct.dev/agents.md)
- [OpenAPI spec](https://coinmarketcap.mcp.junct.dev/openapi.json)

Keywords: Coinmarketcap, MCP server, DeFi, AI agent, agent-ready API, crypto tools, Model Context Protocol
