# Quickstart

Open Design Guard is a hosted remote MCP for agent design system guard MCP.

## Fast Path

1. Open Open Design Guard and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://opendesignguard.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call check_design_guard with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://opendesignguard.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=opendesignguard_public_docs&utm_content=quickstart_home
- https://opendesignguard.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=opendesignguard_public_docs&utm_content=quickstart_pricing
- https://opendesignguard.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=opendesignguard_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://opendesignguard.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
