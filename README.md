# LinkedIn MCP Server

MCP server for LinkedIn MCP Server

## Setup

```bash
# Install dependencies
uv sync

# Copy environment file
cp .env.example .env

# Edit .env with your values
```

## Local Development

```bash
# Run the server
./run.sh

# Or directly
uv run linkedin-mcp-server
```


## Authentication

This server uses OAuth. Set `GITHUB_CLIENT_ID` and `GITHUB_CLIENT_SECRET` in your `.env` file.

For local testing, set `LOCAL_ACCESS_TOKEN` to simulate an authenticated user.

When deployed to Gumstack, users authenticate via the OAuth flow in the Gumstack UI.


## Tools

- `example_tool` - Example tool demonstrating credential usage
