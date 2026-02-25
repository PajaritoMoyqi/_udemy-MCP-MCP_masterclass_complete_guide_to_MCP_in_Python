Install this MCP server by adding the following JSON code to your JSON config file.

```json
{
  "mcpServers": {
    "Chess.com stat": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/henryhabib/chess-mcp-henry.git",
        "chess"
      ]
    }
  }
}
```

-----

It's just an example, for the lecture. There is no github repository like above, so don't be confused using upper code.