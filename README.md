# Hi, I'm Eskstrom

I explore product problems where teams need to make decisions with incomplete information: resolving operational exceptions, choosing AI models, and evaluating whether a workflow is ready to use.

My focus is the reasoning behind the product: who needs help, which decisions deserve automation, where human review matters, and what evidence would justify the next step.

## Financial operations: act on exceptions before deadlines

**The pain point:** An operations team can see a settlement break and still lack a clear owner, an escalation deadline, or evidence that it has been resolved. A dashboard alone does not close that gap.

In an agency securities-lending case study, I mapped the trade lifecycle, framed discovery questions around operational roles, and prioritized five exception families by frequency, impact, and urgency. I translated that scope into requirements, SQL controls, operating protocols, and UAT scenarios.

**The judgment:** Start with configurable rules rather than predictive ranking. Analysts need to understand why a record was flagged, reproduce the result, and review threshold changes. Each exception has one accountable owner. Resolution and closure are separate states so that fixing the issue does not substitute for retaining evidence.

**Where controls belong:** The proposed workflow requires closure evidence and a second reviewer for high-severity manual overrides. Trade execution, credit approvals, and external communications remain outside the automation scope. The static demo uses synthetic records and has no production connections or authentication; it demonstrates the workflow, not production access controls.

**Design takeaway and next test:** Ownership and closure criteria are part of the product. A proposed shadow-mode pilot would test false alerts and missing data before changing operations. The repository’s improvement targets are illustrative, not measured outcomes.

[Explore the case study, decisions, SQL controls, and demo](https://github.com/Eskstrom/agency-lending-operations-case-study)

## Enterprise AI: choose a model for the work it must do

**The pain point:** Teams adopting models independently can lose track of quality, cost, and which models are appropriate for sensitive work. A single leaderboard cannot settle those workload-specific decisions.

In an enterprise model-platform case study, I defined an evaluation approach for grounded Q&A, summarization, extraction, and tool calling, then connected those evaluations to routing policies and launch decision records.

**The judgment:** Choose a model that meets the workload’s quality bar within latency, cost, and governance constraints. Measure cost per successful task alongside quality and P95 latency; a lower token price alone does not establish better value.

**Where controls belong:** The design includes approved-model lists, versioned decisions, review paths, and rollback. It deliberately defers live traffic routing and automatic model approval so the initial scope can focus on the evidence needed to make a selection.

**Design takeaway and next test:** Model choice needs a repeatable decision process. The next validation step is a versioned, representative workload comparison. This repository documents the framework and product design, not measured model performance or a production platform.

[Explore the evaluation framework, scope decisions, and governance design](https://github.com/Eskstrom/enterprise-llm-model-hub)

## Questions I’m exploring next

These are early project briefs, with validation still to do.

| Theme | Problem and proposed approach | Evidence needed next |
| --- | --- | --- |
| AI deployment operations | Help deployment managers identify blocked customer sites using readiness checks and explainable risk rules. | Test whether users can identify a blocked site and its next action in under a minute. [Read the brief](https://github.com/Eskstrom/ai-deployment-command-center). |
| Recruiting search quality | Test whether semantic retrieval improves recruiter-style search against a keyword baseline using synthetic profiles. Evaluate retrieval relevance without turning it into a hiring recommendation. | Document relevance judgments and compare precision@5, recall@5, and failure cases. [Read the brief](https://github.com/Eskstrom/candidate-search-eval-lab). |

## How I approach these problems

- Start with the user’s decision and the cost of getting it wrong.
- Make alternatives and scope boundaries explicit.
- Place controls around specific failures, with a reason for each intervention.
- Separate a proposed benefit from an observed result.
- Define what evidence would change the design before expanding it.

## More problems I am exploring

| Theme | Use case | Repository |
| --- | --- | --- |
| Support operations | Ground support answers in sources and provide escalation paths. | [ClarityDesk RAG](https://github.com/Eskstrom/claritydesk-rag) |
| Research workflows | Turn a question into a concise, cited research brief. | [Research Orchestra](https://github.com/Eskstrom/research-orchestra) |
| Personal productivity | Plan focused work sessions. | [FocusFlow](https://github.com/Eskstrom/focusflow) |
| Learning interfaces | Explain chess-opening ideas and plans interactively. | [Opening Explainer](https://github.com/Eskstrom/opening-explainer) |
| Interactive games | Explore a browser-based number puzzle. | [2048 Game](https://github.com/Eskstrom/2048game) |

## Get in touch

Explore the work above or connect through GitHub.
