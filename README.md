# MCP Server Deployment

## MCP Installation

To configure a local MCP server, you can add the following to your `claude_desktop_config.json` file. This allows you to run the `mcp-server` directly from the git repository using `uvx`.

```json
{
  "mcpServers": {
    "gitserver": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/uttpesh-vyas/mcp-sever-deepdive-deployment.git",
        "mcp-server"
      ]
    }
  }
}
```