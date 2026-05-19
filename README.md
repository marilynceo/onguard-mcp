# onguard-mcp

AI-native incident response & on-call management via PagerDuty API v2. List, acknowledge, and resolve incidents. Execute runbooks. Check on-call schedules.

## Quick Start

```bash
git clone https://github.com/marilynceo/onguard-mcp.git
cd onguard-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://onguard.zhc-mcp.org

## Tools

See `src/server.py` for full tool list.

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/onguard-mcp

# Or connect directly via MCP client
# Endpoint: https://onguard.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
