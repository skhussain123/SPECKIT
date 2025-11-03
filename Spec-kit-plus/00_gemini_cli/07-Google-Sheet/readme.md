

# Gemini Connect With (Goggle shee , Google Drive)

#### Goto Google Cloud Console and Working
* Create Service Account and download (service account key .json file)
* Enabled Google Drive Api
* Enabled Google Sheet


![alt text](image1.PNG)

<br>


![alt text](image2.PNG)

<br>

##### Email ko copy kro or Google Drive me access do
* Click "Share" button (top right)
* apny Service account ki Email daalo or Editor Access ko Spreadsheet ko

---

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
        "SERVICE_ACCOUNT_PATH": "C:\\Users\\user\\Downloads\\auth.json"
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

---

### Try this Command
#### Creat sheet in perticular Spreadsheet 
```bash
create a new sheet student-aptech in spreadsheet 1jK9je7IBAzKMr3SGSvPwsCyA8QJmeQ6WeHd3C31H0k4
```

#### Create Spreadsheet
```bash
create a new spreadsheet named "Aptech Students Data"
```
