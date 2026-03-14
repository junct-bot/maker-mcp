# Maker MCP Server

MCP server for Maker. Agent-ready API for Maker.

Hosted at [maker.mcp.junct.dev/mcp](https://maker.mcp.junct.dev/mcp). Free to use. No auth. No API key required.

Part of [Junct](https://junct.dev) — the agent-readiness layer for the crypto stack.

## Quick Start

Add to your MCP client config (Claude Desktop, Cursor, Windsurf):

```json
{
  "mcpServers": {
    "maker": {
      "url": "https://maker.mcp.junct.dev/mcp",
      "transport": "streamable-http"
    }
  }
}
```

## About

This MCP server is **deterministically generated** from the Maker API specification. Every tool maps 1:1 to a real API endpoint — no hallucinated endpoints, no phantom tools.

- **Protocol:** Maker
- **Endpoint:** `https://maker.mcp.junct.dev/mcp`
- **Transport:** Streamable HTTP
- **Auth:** None required
- **Documentation:** [maker.mcp.junct.dev/llms.txt](https://maker.mcp.junct.dev/llms.txt)
- **Server card:** [maker.mcp.junct.dev/.well-known/mcp/server.json](https://maker.mcp.junct.dev/.well-known/mcp/server.json)

## Links

- [Junct Dashboard](https://junct.dev/servers/maker)
- [llms.txt](https://maker.mcp.junct.dev/llms.txt)
- [agents.md](https://maker.mcp.junct.dev/agents.md)
- [OpenAPI spec](https://maker.mcp.junct.dev/openapi.json)

## Keywords

Maker, MCP server, DeFi, AI agent, agent-ready API, crypto tools, Model Context Protocol, hosted MCP
