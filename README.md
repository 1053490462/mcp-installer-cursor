# MCP Installer for Cursor

This is a modified version of the MCP Installer that supports Cursor's configuration format. It can install MCP servers from npm packages or local directories and configure them for use with Cursor.

## Features

- Supports both Cursor and Claude Desktop configuration formats
- Can install MCP servers from npm packages using `npx`
- Can install MCP servers from Python packages using `uvx`
- Can install MCP servers from local directories

## Installation

```bash
npm install -g @modelcontextprotocol/installer-cursor
```

## Usage

This package provides an MCP server that can be used to install other MCP servers. It will automatically detect whether you're using Cursor or Claude Desktop and update the appropriate configuration file.

### Configuration Files

- Cursor: `~/.cursor/mcp.json`
- Claude Desktop: `~/AppData/Roaming/Claude/claude_desktop_config.json` (Windows) or `~/Library/Application Support/Claude/claude_desktop_config.json` (macOS)

## Development

1. Clone this repository
2. Run `npm install`
3. Run `npm run build`
4. Run `npm start`

## License

MIT