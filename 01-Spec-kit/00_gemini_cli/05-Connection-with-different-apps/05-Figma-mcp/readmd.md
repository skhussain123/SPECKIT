

### Create Figma Api key
1. Go to figma website
2. click profile icon and Settings
3. Click to Security menu
4. Create Personal access tokens


#### Settings.json
```bash
{
  "ide": { "hasSeenNudge": true },
  "mcpServers": {
    "Framelink MCP for Figma": {
      "command": "cmd",
      "args": ["/c", "npx", "-y", "figma-developer-mcp", "--figma-api-key=FIGMA_API_KEY", "--stdio"]
    }
  },
  "security": { "auth": { "selectedType": "oauth-personal" } },
  "ui": { "theme": "Default" }
}
```