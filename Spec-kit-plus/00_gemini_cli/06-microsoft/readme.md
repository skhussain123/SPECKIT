
**Run Terminal**
```bash
npx -y @softeria/ms-365-mcp-server --login
```
* Yeh device code generate karega: Jaise "Go to https://microsoft.com/devicelogin and enter code ABC123".
* Browser kholo, URL pe jaao, code paste karo, apne Microsoft account se login karo (personal ya work).
* Success pe "Login successful" dikhega.
* Token cache ho jayega (next time auto use hoga).

```bash
{
  "ide": {
    "hasSeenNudge": true
  },
  "mcpServers": {
    "ms365": {
      "command": "npx",
      "args": [
        "-y",
        "@softeria/ms-365-mcp-server"
      ]
    }
  },
  "security": {
    "auth": {
      "selectedType": "oauth-personal"
    }
  },
  "ui": {
    "theme": "Default"
  }
}
```

### Gemini Cli
```bash
/gemini
/ mcp list
```
<br>

![alt text](image1.PNG)



