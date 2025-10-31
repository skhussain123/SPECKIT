

# Gemini Connect With (Goggle shee , Google Drive)

#### Goto Google Cloud Console and Working
* Create Service Account and download (service account key .json file)
* Enabled Google Drive Api
* Enabled Google Sheet

#### Goto Google Drive / Create Folder and copy folder id 
**.gemini/settings.json**
```bash
 {
  "ide": {
    "hasSeenNudge": true
  },
  "mcpServers": {
     "google-sheets": {
      "command": "uvx",
      "args": [
        "mcp-google-sheets@latest"
      ],
      "env": {
        "SERVICE_ACCOUNT_PATH": "C:\\Users\\user\\Downloads\\service-account.json",
        "DRIVE_FOLDER_ID": "1ntFUISe0-9lXIjZqSMmOjMd7IcXMs87s"
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
  }
}
```