# ADR-0001: Project Architecture Direction

Version: 0.1.0
Status: Accepted
Date: 2026-07-04

## Context

MarketPilot AI needs a structure that can grow from documentation and analysis into a working software platform.

The project must support:

- Market intelligence
- Opportunity scoring
- Risk rules
- Portfolio tracking
- Notifications
- Future integrations

## Decision

MarketPilot AI will be organized as a modular system.

Primary modules:

- Atlas AI Core
- Market Engine
- Opportunity Engine
- Risk Engine
- Portfolio Manager
- Notification Engine
- Data Connectors
- Journal Engine

Each module should have clear inputs, outputs, and responsibilities.

## Consequences

Benefits:

- Easier to test individual modules
- Easier to replace data providers
- Easier to add broker integrations later
- Better explainability

Tradeoffs:

- More upfront documentation
- More discipline required before implementation

## Notes

Atlas is the internal reasoning layer.
MarketPilot AI is the product layer.
