# Tatl → Navvi

**Tatl has been merged into [Navvi](https://github.com/Fellowship-dev/navvi).**

The companion agents (`navvi-browse`, `navvi-login`, `navvi-signup`) now ship with Navvi directly.

## Install

```bash
npx skills add Fellowship-dev/navvi
```

Or add the MCP server:

```json
{
  "mcpServers": {
    "navvi": {
      "command": "uvx",
      "args": ["navvi@latest"]
    }
  }
}
```

See **[Fellowship-dev/navvi](https://github.com/Fellowship-dev/navvi)** for full documentation.
