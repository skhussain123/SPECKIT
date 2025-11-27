

### Installations:
```bash
pip install specifyplus
specifyplus --version
specifyplus init my_project
```

---


### Commands

| Command | Description                                                                                                                            |
| ------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| `init`  | Initialize a new Specify project from the latest template                                                                              |
| `check` | Check for installed tools (`git`, `claude`, `gemini`, `code`/`code-insiders`, `cursor-agent`, `windsurf`, `qwen`, `opencode`, `codex`) |


### `specifyplus init` Arguments & Options

| Argument/Option        | Type     | Description                                                                |
|------------------------|----------|------------------------------------------------------------------------------|
| `<project-name>`       | Argument | Name for your new project directory (optional if using `--here`, or use `.` for current directory) |
| `--ai`                 | Option   | AI assistant to use: `claude`, `gemini`, `copilot`, `cursor-agent`, `qwen`, `opencode`, `codex`, `windsurf`, `kilocode`, `auggie`, `roo`, `codebuddy`, `amp`, or `q` |
| `--script`             | Option   | Script variant to use: `sh` (bash/zsh) or `ps` (PowerShell)                 |
| `--ignore-agent-tools` | Flag     | Skip checks for AI agent tools like Claude Code                             |
| `--no-git`             | Flag     | Skip git repository initialization                                          |
| `--here`               | Flag     | Initialize project in the current directory instead of creating a new one   |
| `--force`              | Flag     | Force merge/overwrite when initializing in current directory (skip confirmation) |
| `--skip-tls`           | Flag     | Skip SSL/TLS verification (not recommended)                                 |
| `--debug`              | Flag     | Enable detailed debug output for troubleshooting                            |
| `--github-token`       | Option   | GitHub token for API requests (or set GH_TOKEN/GITHUB_TOKEN env variable)  |



### Examples

```bash
# Basic project initialization
specifyplus init my-project

# Initialize with specific AI assistant
specifyplus init my-project --ai claude

# Initialize with Cursor support
specifyplus init my-project --ai cursor

# Initialize with Windsurf support
specifyplus init my-project --ai windsurf

# Initialize with Amp support
specify init my-project --ai amp

# Initialize with PowerShell scripts (Windows/cross-platform)
specifyplus init my-project --ai copilot --script ps

# Initialize in current directory
specifyplus init . --ai copilot
# or use the --here flag
specifyplus init --here --ai copilot

# Force merge into current (non-empty) directory without confirmation
specifyplus init . --force --ai copilot
# or
specifyplus init --here --force --ai copilot

# Skip git initialization
specifyplus init my-project --ai gemini --no-git

# Enable debug output for troubleshooting
specifyplus init my-project --ai claude --debug

# Use GitHub token for API requests (helpful for corporate environments)
specifyplus init my-project --ai claude --github-token ghp_your_token_here

# Check system requirements
specifyplus check
```

