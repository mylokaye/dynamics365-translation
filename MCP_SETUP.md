# MS Learn MCP Setup

This project includes Microsoft Learn MCP (Model Context Protocol) server integration for accessing official Microsoft documentation and terminology.

## What is MCP?

MCP (Model Context Protocol) is a protocol that allows AI assistants to connect to various data sources and services. The MS Learn MCP server provides access to Microsoft Learn documentation, which is particularly useful for:

- Getting accurate Dynamics 365 terminology
- Accessing official Microsoft translations
- Ensuring consistency with Microsoft's documentation
- Finding best practices and examples from official docs

## Configuration

The MCP server is configured in `.claude/mcp.json` and will automatically be available when using Claude Code or other MCP-compatible AI assistants.

## Usage

When working with this project in Claude Code, you can now ask questions like:

- "What is the official Microsoft terminology for [term] in German?"
- "Find the official translation for [Dynamics 365 feature] in Chinese"
- "Look up best practices for [feature] in Microsoft Learn"
- "Check the official documentation for [API/feature]"

The AI assistant will automatically use the MS Learn MCP server to fetch accurate, up-to-date information from Microsoft's official documentation.

## Requirements

- Node.js and npm (for running the MCP server)
- The `@microsoft/mcp-server-mslearn` package (automatically installed via npx)

## Troubleshooting

If the MCP server is not working:

1. Ensure Node.js is installed: `node --version`
2. Check that the `.claude/mcp.json` file exists
3. Restart your Claude Code session to reload MCP configurations
4. Check Claude Code logs for any MCP connection errors

## Benefits for This Project

For the Dynamics 365 translation project, the MS Learn MCP server provides:

- **Accurate terminology**: Access to official Microsoft terminology in multiple languages
- **Consistency**: Ensures translations match Microsoft's official documentation
- **Context**: Provides context about Dynamics 365 features to improve translation quality
- **Up-to-date information**: Always accesses the latest Microsoft Learn content
