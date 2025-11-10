

1. Browser mein jaao: https://nanana.app
2. Dashboard mein jaao → Account ya Settings
3. "API Access" section mein jaao
4. Generate API Token button click karo

---

#### Sesstings.json
```bash
{
  "mcpServers": {
    "nanana": {
      "command": "npx",
      "args": [
        "-y",
        "@nanana-ai/mcp-server-nano-banana"
      ],
      "env": {
        "NANANA_API_TOKEN": ""
      }
    }
  },
  "security": {
    "auth": {
      "selectedType": "oauth-personal"
    }
  },
  "ui": {
    "theme": "Default"
  },
  "hasSeenIdeIntegrationNudge": true
}
```