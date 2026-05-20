# Open Design Guard

Open Design Guard is a hosted remote MCP for agent design system guard MCP.

This repository is a public documentation project for Open Design Guard. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://opendesignguard.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=opendesignguard_public_docs&utm_content=readme_home
- Pricing: https://opendesignguard.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=opendesignguard_public_docs&utm_content=readme_pricing
- Checkout: https://opendesignguard.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=opendesignguard_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://opendesignguard.clauxel.com/mcp
- Server card: https://opendesignguard.clauxel.com/server-card.json
- Registry name: `com.clauxel.opendesignguard/opendesignguard-mcp`
- Tools: `check_design_guard`, `explain_design_gap`, `issue_design_receipt`, `suggest_agent_fix`, `export_design_audit`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: check_design_guard
- MCP tool: explain_design_gap
- MCP tool: issue_design_receipt
- MCP tool: suggest_agent_fix
- MCP tool: export_design_audit

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
