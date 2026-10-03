# Muse Small Business Playbook

Real agent workflows for the 30-person company that operates like a 300-person company.

Meta's Muse for Small Business (launched September 2026) connects to the tools a business already runs on: Shopify, Stripe, QuickBooks, Slack, Asana, Notion, and more. This repo documents working patterns for putting an agent workforce to work, with one non-negotiable rule: **nothing publishes, sends, or spends without the owner's approval.**

## The thesis

The smartest model doesn't win. The most accessible model wins.

The frontier labs are fighting over benchmarks. Meta is fighting over distribution, and distribution is winning. Muse is already in the hands of billions. Now it's inside their businesses, doing the books, answering customers, chasing invoices, running the ops that used to take a team.

This playbook is the proof. Every workflow here is a real pattern: the goal, the connectors, the exact prompt to give Muse, and the approval checkpoints that keep the owner in charge.

## Workflows

| # | Workflow | Connectors | Status |
|---|----------|------------|--------|
| 01 | [Books on autopilot](workflows/01-books-on-autopilot.md) | QuickBooks | Documented |
| 02 | [Storefront ops](workflows/02-storefront-ops.md) | Shopify | Documented |
| 03 | [Customer ops triage](workflows/03-customer-ops.md) | Slack | Documented |
| 04 | [Cash flow recovery](workflows/04-cash-flow.md) | Stripe | Documented |
| 05 | [Weekly ops review](workflows/05-weekly-review.md) | Notion, Asana | Documented |

Status key: **Documented** = built from launch materials and connector docs, awaiting field test. **Field tested** = run against a live business.

## The approval rule

Read [guardrails.md](guardrails.md) first. Every workflow in this repo is designed around Muse's approval boundary: the agent prepares, the owner approves. Anything that publishes, sends, or spends stops for a human first. That's not a limitation. That's the feature that makes agents deployable in a real business.

## Contributing

Run one of these workflows in a real business? Open a PR: mark it field tested, note what broke, note what surprised you. The best playbook is the one written by operators.

## Author

Greg Lucas, education futurist and AI evangelist. Muse early access member. Founder of pAIgeBreaker. I write about the agentic small business on LinkedIn: [greg-lucas-28765b416](https://www.linkedin.com/in/greg-lucas-28765b416/).
