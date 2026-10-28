# Super Mario World Reverse Engineering — Knowledge Base

[![GitMCP](https://img.shields.io/endpoint?url=https://gitmcp.io/badge/ethanhunt1981/smw-reverse-engineering-kb)](https://gitmcp.io/ethanhunt1981/smw-reverse-engineering-kb) [![Glama MCP](https://glama.ai/mcp/connectors/io.github.ethanhunt1981/smw-reverse-engineering-kb/badges/score.svg)](https://glama.ai/mcp/connectors/io.github.ethanhunt1981/smw-reverse-engineering-kb) [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

GitMCP-ready knowledge base for Super Mario World (SNES) reverse engineering: WLA disassembly, Ghidra C-decompilation, Python port, graphics, audio, levels, sprites.

## GitMCP

This repository is designed to be used with https://gitmcp.io/ethanhunt1981/smw-reverse-engineering-kb.

It is also listed in the official MCP Registry as `io.github.ethanhunt1981/smw-reverse-engineering-kb` (streamable HTTP via GitMCP; metadata in `server.json`).

OpenCode / typical agent setup:

```json
{
  "$schema": "https://opencode.ai/config.json",
  "mcp": {
    "servers": {
      "smw-re-kb": {
        "type": "remote",
        "url": "https://gitmcp.io/ethanhunt1981/smw-reverse-engineering-kb"
      }
    }
  }
}
```

OpenCode CLI command:

```
opencode mcp add smw-re-kb --global --url https://gitmcp.io/ethanhunt1981/smw-reverse-engineering-kb
opencode mcp list
```

## Source project

https://github.com/ethanhunt1981/reverse-engineer-anything_supermarioworld

## License

MIT
