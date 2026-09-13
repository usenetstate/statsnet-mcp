# Statsnet MCP

Remote [Model Context Protocol](https://modelcontextprotocol.io) server for **Statsnet** company data across Kazakhstan (KZ), Uzbekistan (UZ), and Kyrgyzstan (KG).

- **Endpoint:** `https://statsnet.co/mcp`
- **Transport:** Streamable HTTP
- **Official Registry name:** `io.github.usenetstate/statsnet`
- **Website:** https://statsnet.co

## Tools

- `search_companies` — search by name, BIN/IIN, or executive
- `get_company` — public Markdown company card (status, registration, leadership, contracts, courts, finances)

Free tools return the public card. Contacts, full contracts, relations, and exports need a Statsnet subscription via the [REST API](https://statsnet.co/api.md) ([pricing](https://statsnet.co/pricing.md)).

## Cursor / Claude config

```json
{
  "mcpServers": {
    "statsnet": {
      "url": "https://statsnet.co/mcp"
    }
  }
}
```

## Privacy

https://statsnet.co/privacy

## License

MIT
