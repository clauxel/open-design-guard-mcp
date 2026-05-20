# Open Design Guard MCP

agent design system guard MCP with structured receipts.

Paid remote MCP for agent design system guard MCP, structured receipts, audit logs, and reviewer-ready evidence.

## Public Endpoints

- Website: https://opendesignguard.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://opendesignguard.clauxel.com/mcp
- Server card: https://opendesignguard.clauxel.com/server-card.json
- Registry name: `com.clauxel.opendesignguard/opendesignguard-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `check_design_guard`
- `explain_design_gap`
- `issue_design_receipt`
- `suggest_agent_fix`
- `export_design_audit`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://opendesignguard.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://opendesignguard.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://opendesignguard.clauxel.com/server-card.json
- MCP endpoint: https://opendesignguard.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
