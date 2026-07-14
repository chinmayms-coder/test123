# test123
Just a test repository

## Exotel MCP server

This repo defines a `.mcp.json` entry for the [Exotel MCP server](https://mcp.exotel.com/mcp),
which lets Claude send SMS/place calls through Exotel's APIs.

To use it:

1. Copy `.env.example` to `.env`.
2. Fill in your Exotel credentials (API key/token, account ID, caller ID, etc.) in `.env`.
   `.env` is gitignored — never commit real credentials.
3. Restart Claude Code so it picks up `.mcp.json` and loads the `exotel` server.
