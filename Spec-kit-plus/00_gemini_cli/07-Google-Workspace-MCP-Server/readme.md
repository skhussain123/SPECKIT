
# Gemini Connect With (Goggle shee , Google Drive)


#### Goto google cloud console and working
* Create Service Account and download (service account key .json file)
* Enabled Google Drive Api
* Enabled Google Sheet


```bash
 "google-sheets": {
      "command": "uvx",
      "args": [
        "mcp-google-sheets@latest"
      ],
      "env": {
        "SERVICE_ACCOUNT_PATH": "~/.gemini/service-account.json",
        "DRIVE_FOLDER_ID": "1ntFUISe0-9lXIjZqSMmOjMd7IcXMs87s"
      }
    }
  },
  ```