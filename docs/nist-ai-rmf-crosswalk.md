# NIST AI Risk Management Framework Crosswalk

## Purpose

This crosswalk maps the Responsible AI Adoption Toolkit for SMEs to the NIST AI Risk Management Framework (AI RMF) functions: **Govern, Map, Measure, and Manage**.

The goal is not to turn small organizations into compliance departments. The goal is to translate responsible AI risk management into practical workflow-level questions and documents that SMEs can actually use.

## Toolkit-to-NIST summary

| NIST AI RMF Function | SME Toolkit Component | Practical purpose |
|---|---|---|
| Govern | AI Governance Policy | Defines principles, ownership, prohibited uses, review cadence, and incident response. |
| Govern | Human Oversight Plan | Assigns human accountability, override rights, review requirements, and stop conditions. |
| Govern | Pilot Review Scorecard | Creates accountable scale/stop/revise decisions. |
| Map | AI Use Case Intake | Defines context, purpose, users, data, affected people, and AI role. |
| Map | Stakeholder and Impact Map | Identifies affected groups, likely benefits, harms, and engagement needs. |
| Map | Workforce Impact Checklist | Maps job-quality, autonomy, surveillance, skill, and role-change implications. |
| Measure | Productivity and ROI Measurement Plan | Establishes baseline, metrics, target outcomes, and evidence quality. |
| Measure | Risk Register | Measures likelihood, impact, controls, ownership, and status. |
| Measure | Pilot Review Scorecard | Compares results against baseline, including risk and worker experience. |
| Manage | Risk Register | Tracks mitigations, owners, dates, and open/closed status. |
| Manage | Human Oversight Plan | Defines operational controls, escalation, review, and appeal paths. |
| Manage | Implementation Guide | Provides staged pilot workflow and review process. |

## Govern

NIST emphasis: establish policies, processes, accountability, organizational roles, and risk culture.

Toolkit support:

- `07-ai-governance-policy.md`
- `06-human-oversight-plan.md`
- `08-pilot-review-scorecard.md`

SME questions:

1. Who owns this AI use case?
2. Who is accountable when the AI is wrong?
3. What uses are prohibited without special review?
4. What decisions must remain human-owned?
5. Who can pause or stop the pilot?
6. How often is the AI workflow reviewed?
7. How are incidents logged and escalated?

Minimum evidence:

- Named sponsor and process owner
- Human review requirements
- Stop conditions
- Incident response path
- Pilot review date

## Map

NIST emphasis: understand context, intended purpose, affected groups, assumptions, benefits, and risks.

Toolkit support:

- `01-ai-use-case-intake.md`
- `02-stakeholder-and-impact-map.md`
- `04-workforce-impact-checklist.md`

SME questions:

1. What exact workflow is changing?
2. What AI capability is being used?
3. What data goes in and what output comes out?
4. Who directly uses the system?
5. Who is affected indirectly?
6. Could this change job quality, autonomy, pay, scheduling, monitoring, or advancement?
7. Could this affect customers, applicants, vendors, or public access?

Minimum evidence:

- Use-case description
- Data/input/output description
- Stakeholder list
- Workforce impact notes
- Initial risk screen

## Measure

NIST emphasis: analyze, evaluate, benchmark, and monitor AI risks and performance.

Toolkit support:

- `03-productivity-roi-measurement-plan.md`
- `05-risk-register.md`
- `08-pilot-review-scorecard.md`

SME questions:

1. What is the current baseline?
2. What productivity gain is expected?
3. How will quality be measured?
4. How will errors/rework be tracked?
5. How will worker experience be measured?
6. What risks are high-impact even if unlikely?
7. What evidence would prove the pilot failed?

Minimum evidence:

- Baseline metrics
- Success thresholds
- Risk likelihood/impact ratings
- Incident log
- Worker/user feedback

## Manage

NIST emphasis: prioritize, respond to, treat, monitor, and communicate AI risks.

Toolkit support:

- `05-risk-register.md`
- `06-human-oversight-plan.md`
- `docs/implementation-guide.md`
- `08-pilot-review-scorecard.md`

SME questions:

1. Which risks must be mitigated before pilot?
2. Which risks can be monitored during pilot?
3. Who owns each mitigation?
4. What triggers pause/stop/escalation?
5. What must change before scale-up?
6. What should be communicated to workers or affected people?

Minimum evidence:

- Risk owners
- Mitigation actions
- Review dates
- Stop/revise/scale decision
- Conditions for expansion

## Lightweight scoring model

Use a 1–5 score for each dimension:

| Dimension | 1 = weak/high risk | 5 = strong/low risk |
|---|---|---|
| Purpose clarity | Vague or speculative | Narrow, useful, measurable |
| Data sensitivity | Sensitive/uncontrolled | Minimal/approved data |
| Human accountability | Unclear | Named owner and review path |
| Workforce impact | Unknown/possibly harmful | Reviewed with affected workers |
| Measurement quality | No baseline | Baseline and success metrics defined |
| Risk controls | No mitigations | Controls, owners, stop rules defined |
| Reversibility | Hard to undo | Limited pilot, easy rollback |

Suggested decision rule:

- **28–35:** Pilot likely appropriate with normal controls.
- **20–27:** Revise before pilot; address weak dimensions.
- **Below 20:** Do not pilot until governance and risk gaps are fixed.
- Any high-impact use case involving employment, pay, safety, legal, financial, health, housing, education, or access rights requires special review regardless of score.

## Grant positioning note

This crosswalk strengthens funding applications by showing that the toolkit is not merely a checklist collection. It is structured around a recognized AI risk-management framework while remaining usable for SMEs.
