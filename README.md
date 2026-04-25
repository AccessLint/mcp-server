# AccessLint MCP Server

> [!NOTE]
> This repository has moved. Development now happens in the [AccessLint monorepo](https://github.com/AccessLint/accesslint) under [`mcp/`](https://github.com/AccessLint/accesslint/tree/main/mcp).
>
> This repository is archived and read-only. Please open issues and pull requests in the [new location](https://github.com/AccessLint/accesslint/tree/main/mcp).

The MCP (Model Context Protocol) server providing accessibility analysis tools for WCAG conformance is published to npm as [`@accesslint/mcp`](https://www.npmjs.com/package/@accesslint/mcp).

## Installation

```json
{
  "mcpServers": {
    "accesslint": {
      "command": "npx",
      "args": ["-y", "@accesslint/mcp"]
    }
  }
}
```

For full documentation, see the [README in the monorepo](https://github.com/AccessLint/accesslint/blob/main/mcp/README.md).
