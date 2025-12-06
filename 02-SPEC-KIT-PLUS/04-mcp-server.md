
## Github MCP Server Connect With Claude 

#### Create specifyplus project
```bash
specifyplus init hakhthon-app
calude
power shell
```

#### Goto Home directory Cmd open in Vs code
* open .calude.json file
* goto your project name path and set your credentials
```bash
"C:\\Users\\user\\Music\\hackathon-app": {
      "allowedTools": [],
      "mcpContextUris": [],
      "mcpServers": {
        "github": {
          "type": "http",
          "url": "https://api.githubcopilot.com/mcp/",
          "headers": {
            "Authorization": "Bearer github_pat_11A2KNPXA0c27dUB7Wn0Rk_lWc7IY78mg3brjVJ2Z5bp2sWTyLcqxZTvyLS4ANIYPazuPgyvz"
          }
        }
      },
```

#### With Commands 
* Goto your project and open in cmd 
```bash
# 1) Playwright MCP (browse the web)
claude mcp add --transport stdio playwright npx @playwright/mcp@latest

# 2) Context7 MCP (get up-to-date docs)
claude mcp add --transport stdio context7 npx @upstash/context7-mcp
```
* Automatically add mcp in your .claude.json file

---

## Context 7 Connection
```bash
claude mcp add --transport stdio context7 npx @upstash/context7-mcp
npm install -g @playwright/mcp @upstash/context7-mcp (Run on power shell administrator)
```

```bash
 "C:\\Users\\user\\Music\\hackathon-app": {
      "allowedTools": [],
      "mcpContextUris": [],
      "mcpServers": {
        "context7": {
          "type": "stdio",
          "command": "npx",
          "args": [
            "@upstash/context7-mcp"
          ]
        }
      },
      "enabledMcpjsonServers": [],
      "disabledMcpjsonServers": [],
      "hasTrustDialogAccepted": true,
      "projectOnboardingSeenCount": 0,
      "hasClaudeMdExternalIncludesApproved": false,
      "hasClaudeMdExternalIncludesWarningShown": false,
      "exampleFiles": [],
      "hasCompletedProjectOnboarding": true
    }
  ```

