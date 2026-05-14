# AML / 6AMLD AI Compliance MCP

[![PyPI](https://img.shields.io/pypi/v/aml-ai-mcp)](https://pypi.org/project/aml-ai-mcp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![MEOK AI Labs](https://img.shields.io/badge/MEOK_AI_Labs-governance--mcp-purple)](https://meok.ai)

6AMLD + UK MLR 2017 + FinCEN BSA AML/CFT compliance for AI-enabled transaction monitoring, sanctions screening, PEP screening.

## Install

```bash
pip install aml-ai-mcp
```

## Tools

| Tool | Purpose |
|------|---------|
| `classify_obliged_entity` | Determine if entity falls within 6AMLD scope |
| `kyc_cdd_audit` | Customer Due Diligence + Enhanced Due Diligence audit |
| `sanctions_screening` | OFAC + EU + UK + UN sanctions list screening check |
| `transaction_monitoring` | AI-based transaction monitoring rule effectiveness audit |
| `sar_filing_check` | Suspicious Activity Report filing trigger conditions |

## Pairs with

- `meok-attestation-api` — POST results to https://meok-attestation-api.vercel.app/sign for cryptographically signed compliance certs
- `meok-attestation-verify` — public verification of any MEOK-signed cert
- Other MEOK governance MCPs via SOV3 `mcp_bridge_call`

## Pricing

- **Free**: 10 calls/day. No API key required.
- **Pro** £79/mo: unlimited + signed attestations. [Subscribe](https://buy.stripe.com/14A4gB3K4eUWgYR56o8k836)
- **Enterprise** £1,499/mo: white-label + on-premise + SLA. hello@meok.ai

## Status

Scaffold v1.0.0 ships the MCP framework + 5 tool stubs. v1.1.0 will add real regulation data ingestion.

If your team needs this MCP fully-loaded faster, ping hello@meok.ai for sponsored development.

## License

MIT © MEOK AI Labs
