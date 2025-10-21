# STRATINT MCP

Strategic intelligence platform that transforms real-time signals from global markets, geopolitics, and conflicts into AI-powered forecasts and actionable strategies. Track events, predict outcomes, and develop informed strategies.

## Connecting

### For Claude Code

Run this command in your terminal:

```bash
claude mcp add --transport http stratint-mcp https://mcp.stratint.ai/mcp
```

### For Cursor

Add this to your `.cursor/mcp.json` (project-specific) or `~/.cursor/mcp.json` (global):

```json
{
  "mcpServers": {
    "stratint-mcp": {
      "command": "npx",
      "args": [
        "mcp-remote",
        "https://mcp.stratint.ai"
      ]
    }
  }
}
```

### For other MCP clients

Connect to: **https://mcp.stratint.ai**

## Learn More

Visit [https://stratint.ai](https://stratint.ai) for detailed documentation and examples.

## License

MIT
