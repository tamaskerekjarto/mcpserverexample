

## Installation Steps

To install the `add_tool` MCP server, run the following command:

```json
{
  "mcpServers": {
     "add_tool": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/tamaskerekjarto/mcpserverexample/",
        "mcp-server"
      ]
    }
  }
}
```