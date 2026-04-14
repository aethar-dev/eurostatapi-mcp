# EurostatAPI MCP Server

[![MCP Compatible](https://img.shields.io/badge/MCP-Compatible-blue)](https://modelcontextprotocol.io)

EU economic statistics via MCP. GDP, inflation (HICP), unemployment, population, trade, earnings for 27 EU member states. Clean JSON — no SDMX codes. Data sourced from Eurostat, updated daily.

## Installation

### Claude Desktop / Claude Code

```json
{
  "mcpServers": {
    "aethar-eurostat": {
      "url": "https://eurostat.wageapi.com/api/mcp",
      "headers": { "X-API-Key": "your_api_key_here" }
    }
  }
}
```

## Authentication

Get a free API key at [console.aethar.dev](https://console.aethar.dev).

## Links

- [API Docs](https://eurostat.wageapi.com/docs) | [Dashboard](https://eurostat.wageapi.com) | [Smithery](https://smithery.ai/servers/aethar/eurostatapi) | [Aethar](https://aethar.dev)

## License

Source code is proprietary. MCP endpoint provided as part of EurostatAPI.
