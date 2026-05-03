# Example: SME Administrative Assistant Pilot

## Use case

A small organization wants to use a generative AI assistant to summarize inbound emails, draft internal task lists, and prepare first-draft customer replies for human review.

## Intended outcome

Reduce administrative cycle time while maintaining quality, privacy, and human accountability.

## Baseline

- Average daily admin emails: 80
- Average time spent triaging: 2.5 hours/day
- Rework/errors: not formally tracked
- Customer response target: same business day

## AI workflow

1. Human exports or routes non-sensitive emails into approved AI workflow.
2. AI summarizes thread, identifies requested action, drafts reply.
3. Human reviews, edits, and sends.
4. Errors and time saved are logged.

## Human-owned decisions

- Sending external replies
- Commitments to customers/vendors
- Pricing, legal, HR, or financial decisions
- Any message involving conflict, complaint, or sensitive information

## Key risks

| Risk | Mitigation |
|---|---|
| Hallucinated facts in draft reply | Require source email citation and human review |
| Confidential data exposure | Exclude sensitive emails; use approved tool only |
| Overreliance | Human sender remains accountable |
| Worker deskilling | Use as drafting aid; train worker in review and prompt skills |
| Hidden productivity pressure | Track workload and review burden, not only output volume |

## Pilot metrics

- Time spent triaging email
- Draft acceptance/edit rate
- Customer response time
- Error/rework incidents
- Worker satisfaction
- Review burden

## Decision rule

Scale only if time savings are meaningful, error rate does not rise, worker feedback is neutral/positive, and no sensitive-data incidents occur.
