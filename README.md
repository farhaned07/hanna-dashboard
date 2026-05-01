# Hanna Dashboard

Operational dashboard for **Hanna Care Intelligence**.

This repo should be understood as part of the Hanna platform, not a standalone dashboard product.

## Product role

The dashboard exists to help care teams answer one question:

> Who needs attention today?

It supports the post-visit care loop:

```text
Visit → Documentation → Care plan → LINE follow-up → Risk signal → Nurse priority → Outcome report
```

## Current business direction

Hanna is sold as **Care Intelligence**, not as a standalone AI scribe or isolated dashboard.

The dashboard should support:

- nurse priority review
- patient follow-up visibility
- risk signal review
- care plan status
- monthly leadership reporting
- exception-based workflow

## Locked packaging

| Package | Price | Purpose |
|---|---:|---|
| Hanna Pilot | ฿60,000/month for 90 days | Prove the care loop with one clinic or department |
| Hanna Care Intelligence | ฿85,000/month, billed annually | Annual department-level care intelligence system |
| Hanna Enterprise | From ฿250,000/month, annual only | Multi-department, hospital group, or payer rollout |

## Design standard

Medical-grade calm:

- quiet UI
- clear patient priority
- minimal clicking
- no cluttered analytics theater
- action-first nurse workflow
- consistent Hanna identity across landing, scribe, LINE, and dashboard

## Development

```bash
npm install
npm run dev
```

## Product rule

Every screen should reduce nurse workload or improve care visibility. If a feature does not support that, hide it, simplify it, or remove it.
