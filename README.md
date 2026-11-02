# Custom MCP Server for LLM Tool Integration

A custom Python server built with the **Model Context Protocol (MCP)** to expose a calculator tool to an LLM client. The project demonstrates how an AI application can discover and invoke external tools through a structured client-server interface.

## Features

- Exposes a custom calculator tool through MCP.
- Defines tool inputs using a structured schema.
- Supports tool discovery and execution by an MCP-compatible client.
- Demonstrates natural-language requests being routed to a tool.
- Uses JSON-RPC-based communication through the MCP protocol.

## Tech Stack

- Python
- Model Context Protocol (MCP)
- JSON-RPC
- `uv`

## How It Works

1. The MCP server registers the calculator tool and its input schema.
2. An MCP-compatible client discovers the available tool.
3. The client sends a tool invocation based on the user's request.
4. The server executes the calculator logic and returns the result.

## Setup

Clone the repository:

```bash
git clone https://github.com/utkrashtsrepo/custom-mcp-calculator-server.git
cd your-repo
