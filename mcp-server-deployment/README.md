# Installation Steps

To install the `add_tool` MCP server, run the following command:

```json
{
  "mcpServers": {
    "add_tool": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/henryhabib/mcpserverexample.git",
        "mcp-server"
      ]
    }
  }
}
```

This will fetch and set up the `mcp-server` from the specified GitHub repository.

---

It's just an example. Do not paste it to install this MCP server to your AI tools, because in Henry Habib's repo, who is the author of this lecture, there is no public repo named 'mcpserverexample' anymore.