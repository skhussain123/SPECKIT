



#### Use this model 
https://huggingface.co/spaces/black-forest-labs/FLUX.1-schnell


```bash
{
  "ide": {
    "hasSeenNudge": true
  },
  "mcpServers": {
    "mcp-hfspace": {
      "command": "npx",
      "args": [
        "-y",
        "@llmindset/mcp-hfspace",
        "--work-dir=/Users/mcp-files", // Apna folder path daalo, jaise images/audio save ke liye
        "black-forest-labs/FLUX.1-schnell", // Default image gen space
        "Qwen/Qwen2.5-72B-Instruct", // Chat space add karo
        "hf-audio/whisper-large-v3-turbo" // Audio transcribe ke liye
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

![alt text](image1.PNG)

<br>

#### This model is Paid




