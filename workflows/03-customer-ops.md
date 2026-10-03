# 03, Customer ops triage

**Goal:** Every customer message answered in minutes, with the owner only touching the ones that matter.
**Connectors:** Slack (or wherever customer messages land)

## The prompt

> "Monitor our customer channel. Draft a reply to every incoming message within 5 minutes, in our brand voice, using our FAQ and order data. If the message involves a refund over $50, an angry customer, or anything you can't answer confidently, escalate to me immediately with your draft attached. Never send a reply without my approval until I tell you otherwise."

## Approval checkpoints

- Every outbound reply: approve until the drafts are consistently right, then approve-by-category (routine questions auto-send, everything else escalates).
- Refunds, cancellations, complaints: always escalate.
- Tone: review weekly. The agent should sound like your best employee, not a bot.

## What good looks like

Response time drops from hours to minutes. The owner spends their customer time on the 10% of conversations that actually need a human, instead of drowning in the 90% that don't.
