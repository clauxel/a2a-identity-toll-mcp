# A2A Identity Toll MCP

Make every agent-to-agent call prove who asked, why, and under which scope.

Paid remote MCP for A2A caller identity policy, scope review, structured allow/review/deny receipts, and audit history.

## Public Endpoints

- Website: https://a2aidentitytoll.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://a2aidentitytoll.clauxel.com/mcp
- Server card: https://a2aidentitytoll.clauxel.com/server-card.json
- Registry name: `com.clauxel.a2aidentitytoll/a2aidentitytoll-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `evaluate_a2a_identity_policy`
- `review_agent_scope`
- `issue_identity_receipt`
- `explain_denied_call`
- `export_a2a_audit_log`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://a2aidentitytoll.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://a2aidentitytoll.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://a2aidentitytoll.clauxel.com/server-card.json
- MCP endpoint: https://a2aidentitytoll.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
