# Example: Internal Knowledge Search Pilot

## Scenario

A 75-person organization wants to use AI to search internal policies, SOPs, and project documentation to answer employee questions.

## AI role

The AI retrieves and summarizes internal documentation. It must cite source documents. It does not create policy or override managers.

## Baseline

- Employees ask repeated process questions via chat/email
- Documentation exists but is hard to find
- Managers spend time answering repetitive questions

## Pilot design

- Duration: 30 days
- Scope: non-sensitive SOPs and public internal policies
- Human review: weekly sample audit of answers
- Data rule: no HR, legal, medical, compensation, or personnel files

## Metrics

| Metric | Baseline | Target |
|---|---:|---:|
| Repeated manager questions | unknown | reduce by 25% |
| Answer accuracy | unknown | 90%+ sampled accuracy |
| Source citation rate | n/a | 100% |
| Employee satisfaction | unknown | 4/5 average |

## Key risks

| Risk | Control |
|---|---|
| Outdated answers | document version tracking |
| Hallucinated policy | require source citation |
| Unauthorized access | limit indexed documents |
| False authority | disclose AI is assistant, not policy owner |

## Worker feedback focus

- Are answers useful and source-backed?
- Does the system reduce interruption burden?
- Are employees comfortable asking questions?
- Are unclear policies being surfaced for improvement?

## Decision rule

Scale only if answer accuracy and source citation are high, access controls are reliable, and employees understand the AI is not the final authority.
