# A2A Identity Toll MCP

Make every agent-to-agent call prove who asked, why, and under which scope.

A2A Identity Toll is a paid remote MCP gate for caller identity, target agent scope, task intent, data class, policy verdicts, and audit receipts.

This is a public documentation project for A2A Identity Toll MCP. The structure is modeled after the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and public-safe architecture notes.

## Start Here

- Website: https://a2aidentitytoll.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=a2aidentitytoll_public_docs&utm_content=readme_primary_home
- Pricing: https://a2aidentitytoll.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=a2aidentitytoll_public_docs&utm_content=readme_pricing
- Checkout: https://a2aidentitytoll.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=a2aidentitytoll_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://a2aidentitytoll.clauxel.com/mcp
- Server card: https://a2aidentitytoll.clauxel.com/server-card.json
- Registry name: `com.clauxel.a2aidentitytoll/a2aidentitytoll-mcp`
- Tools: `evaluate_a2a_identity_policy`, `review_agent_scope`, `issue_identity_receipt`, `explain_denied_call`, `export_a2a_audit_log`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Public link reference](reference/links.md)

## Audience

agent platform teams, AI security reviewers, and A2A protocol adopters.

## Capabilities

- caller identity policy
- scope review
- structured verdict JSON
- receipt archive
- audit dashboard

## Public-Safe Boundary

This repository does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
