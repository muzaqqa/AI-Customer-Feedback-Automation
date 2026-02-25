# Escalation Logic

## Routing Overview

Positive:
- Auto-send response
- Update status in Google Sheets

Neutral:
- Generate draft
- Human review required before sending

Negative:
- Generate controlled draft
- Flag row as URGENT
- Send internal alert
- Require human approval before responding

---

## Escalation Triggers

The following keywords trigger elevated handling:
- chargeback
- lawsuit
- fraud
- scam
- report
- BBB
- legal action

If detected:
- Mark as CRITICAL
- Notify manager
- Prioritize response

---

## Risk Controls

- No automatic refunds or compensation promises
- No timeline guarantees
- Strict single-word classifier output
- Human-in-the-loop safeguard for high-risk sentiment

---

## Rationale

Negative customer feedback carries reputational, financial, and legal risk.
Automation is limited to drafting only.
Final response requires human validation.
