This is a repository for studying a lecture 'MCP Masterclass: Complete Guide to MCP in Python 2025' by Henry Habib and The Intellegent Worker. The videos are in [udemy](https://www.udemy.com/). If you want to see original videos, [Click here](https://www.udemy.com/course/learn-mcp-model-context-protocol-complete-guide/).

------

## Notes

### Sometimes installation path of Claude Desktop differs

So, you need to find your own path which also has it's own `claude_desktop_config.json` file. Candidates below.

```
%LOCALAPPDATA%\Packages\Claude_pzs8sxrjxfjjc
%LOCALAPPDATA%\Microsoft\WindowsApps\Claude_pzs8sxrjxfjjc
```

In the folder goes to `LocalCache\Roaming\Claude`, then you can find log folders(`logs`) and config json file. But still Claude Desktop app tries to find config file and log files in `%APPDATA%\Claude`, and also `mcp install ________` command updates same path. So, be carefui.

It's known that this happens when recent version of Claude Desktop app is installed using MSIX package or because of certain conflicts, but I'm not sure why.