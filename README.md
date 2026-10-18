# Shippp for Cursor

Connects Cursor to your [Shippp](https://shippp.ai) workspaces over MCP. Your agent gets the design as structured data — tokens, components and layout, straight from the canvas — so the result matches the design.

## What you get

- Browse projects, screens and components
- Read design tokens, component schemas and the live selection
- Export deterministic Chakra UI and HTML code
- Apply reviewed, schema-validated change sets (write access only with your explicit consent)

## Setup

1. Install this plugin in Cursor.
2. Cursor connects to the Shippp MCP server at `https://app.shippp.ai/api/mcp/mcp` and opens the Shippp consent page in your browser.
3. Sign in and choose read-only or read-and-write access. The connection covers the workspaces you are a member of.

No API key is needed: authentication is OAuth 2.0 with explicit consent (dynamic client registration). Tool usage is metered according to your Shippp plan.

## Disconnect

Remove the plugin in Cursor, or revoke the connection at any time from your Shippp account page. See the [MCP documentation](https://docs.shippp.ai/mcp) for details.

## Privacy and support

- Privacy policy: https://shippp.ai/legal/privacy
- Documentation: https://docs.shippp.ai/mcp
- Support: hello@shippp.ai

This repository contains only the thin Cursor plugin descriptor for the hosted Shippp MCP server; the Shippp product itself is not part of this repository.
