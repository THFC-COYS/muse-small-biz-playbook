# 04, Cash flow recovery

**Goal:** Failed payments recover themselves instead of quietly churning.
**Connectors:** Stripe

## The prompt

> "Watch Stripe for failed payments. For each one, draft a dunning message in our brand voice and queue it for my approval. Retry logic: first retry after 24 hours, second after 72 hours, then escalate to me with the customer's history. Show me a weekly recovered-revenue number. Never issue a refund without my explicit approval."

## Approval checkpoints

- Dunning messages: approve the templates once, then approve-by-category.
- Refunds: always explicit approval.
- Anything that looks like friendly fraud: escalate, don't engage.

## What good looks like

Involuntary churn drops because someone, something, is always watching the failed charges. The owner sees a weekly number: revenue the agent saved.
