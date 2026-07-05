# Security Policy

Version: 0.1.0
Status: Draft

## Scope

Security matters because MarketPilot AI may eventually connect to market data providers, notification services, and broker APIs.

## Rules

- Never commit API keys.
- Never commit broker credentials.
- Never commit environment files.
- Use `.env` locally and keep it ignored.
- Use paper trading before any live integration.
- Limit permissions for all external services.

## Future Requirements

Before any broker integration, the project must define:

- Secret storage strategy
- API permission boundaries
- Audit logging
- Failure handling
- Manual override controls

## Reporting

Security concerns should be documented in GitHub Issues until a private reporting workflow is created.
