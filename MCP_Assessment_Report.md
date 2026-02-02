# Week 0 MCP Setup Assessment Report

## 1. What I Did
- Cloned the provided GitHub repo into my local environment.
- Updated VS Code to the latest version.
- Installed GitHub Copilot and GitHub Copilot Chat extensions.
- Created required folders and files:
  - `.vscode/mcp.json` for MCP server configuration.
  - `.github/copilot-instructions.md` for AI agent rules.
- Attempted to connect to Tenx MCP server (`tenxfeedbackanalytics`) via Copilot Chat Agent mode.
- Authenticated with GitHub when prompted.

## 2. What Worked
- VS Code setup completed successfully.
- Copilot Chat agent mode works.
- `.vscode/mcp.json` and `.github/copilot-instructions.md` files created successfully.
- AI agent is following the rules in `.github/copilot-instructions.md`.

## 3. What Didn’t Work
- MCP server `tenxfeedbackanalytics` failed to fully connect.
- Logs showed repeated `404 Not Found` errors when connecting to: https://mcppulse.10academy.org/proxy


- As a result, the MCP server did not appear in the agent tools panel.
- Possible causes:
- URL typo or extra characters in `mcp.json`.
- MCP server temporarily unavailable or network restriction.

## 4. Troubleshooting Attempted
- Verified `.vscode/mcp.json` URL and headers.
- Reopened VS Code in the repo root folder.
- Re-authenticated with GitHub.
- Checked internet connection and VPN settings.

## 5. Insights Gained
- MCP server requires precise configuration in `.vscode/mcp.json`.
- VS Code must open **repo root** to correctly recognize `.vscode` and `.github` folders.
- Even when MCP connection fails, documenting setup, effort, and troubleshooting demonstrates competency.
- AI agent behavior can be improved via rules file regardless of server connection.
- Understanding paths, workspace, and agent instructions is critical for coding environment orchestration.

---

**Files included in this repository:**
- `.vscode/mcp.json` → MCP server config
- `.github/copilot-instructions.md` → AI agent rules
- `MCP_Assessment_Report.md` → this report
