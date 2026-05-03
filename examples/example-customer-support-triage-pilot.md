# Example: Customer Support Triage Pilot

## Scenario

A 45-person company wants to use AI to categorize inbound support emails, summarize customer issues, suggest priority level, and draft internal routing notes.

## AI role

The AI classifies and summarizes. It does not send customer replies, close tickets, promise refunds, or make account decisions.

## Baseline

- Daily support emails: 120
- Average first triage time: 3.5 hours/day
- Misrouting rate: estimated 8–10%
- Escalation delays: common during peak periods

## Pilot design

- Duration: 30 days
- Scope: one support inbox
- Human review: 100% of AI-prioritized urgent tickets; 25% random sample of routine tickets
- Sensitive data: exclude billing disputes and legal threats from AI processing

## Metrics

| Metric | Baseline | Target |
|---|---:|---:|
| First triage time | 3.5 hr/day | 2.0 hr/day |
| Misrouting rate | 8–10% | below 5% |
| Urgent issue detection | unknown | measured during pilot |
| Review burden | unknown | below 45 min/day |

## Key risks

| Risk | Control |
|---|---|
| Misclassification of urgent issue | Human review and escalation keywords |
| Privacy exposure | Exclude sensitive categories; approved tool only |
| Overreliance | AI priority is recommendation, not decision |
| Customer trust | No external AI-generated response without human review |

## Worker feedback focus

- Does AI reduce repetitive sorting work?
- Does it create extra correction burden?
- Are priority suggestions trustworthy?
- Does it change stress or workload intensity?

## Decision rule

Scale only if triage time drops, misrouting improves, urgent issues are not missed, and support staff report neutral or positive workload impact.
