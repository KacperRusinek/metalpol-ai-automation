# Trade-offs and Design Decisions

## Why Event-Driven Architecture?

Advantages:
- scalable,
- resilient,
- asynchronous processing,
- better handling of seasonal peaks.

## Why Human-in-the-loop?

Complaint handling impacts:
- customer relationships,
- operational costs,
- quality assurance.

Because of this, final approval should remain manual.

## Why ASP.NET Core?

Advantages:
- strong API ecosystem,
- easy enterprise integrations,
- good Azure compatibility,
- suitable for webhook processing.

## Why Azure OpenAI?

Advantages:
- multilingual processing,
- enterprise security,
- Microsoft ecosystem integration.

## Why Not Fully Autonomous AI?

Full automation introduces risk:
- incorrect complaint decisions,
- customer dissatisfaction,
- operational errors.

The proposed solution focuses on AI-assisted automation.