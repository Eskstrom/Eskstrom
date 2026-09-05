# Sumukh Gadavilli [Linkedin](https://www.linkedin.com/in/sumukh-gadavilli/)

I build tools that help people understand, decide, and act: from AI and operational workflows to everyday productivity, learning, and games.

I'm interested in the judgment behind a product: why this problem matters, which approach fits, what should stay simple, and what evidence would change the design. Some repositories contain implementations; others document case studies or ideas still to validate.

## Start here

| Explore | Why it matters | Status |
| --- | --- | --- |
| [Opening Explainer](https://github.com/Eskstrom/opening-explainer) | Understand the purpose of a chess move while stepping through the position. | Implementation |
| [FocusFlow](https://github.com/Eskstrom/focusflow) | Start focused work and track sessions from the terminal. | Implementation |
| [2048 Game](https://github.com/Eskstrom/2048game) | Explore interaction design through a familiar, playable puzzle. | Implementation |
| [Agency Lending Operations](https://github.com/Eskstrom/agency-lending-operations-case-study) | Turn operational exceptions into accountable action with closure evidence. | Case study + synthetic demo |
| [Enterprise LLM Model Hub](https://github.com/Eskstrom/enterprise-llm-model-hub) | Choose models against workload quality, latency, cost, and governance needs. | Case study |
| [Marketplace Discovery Diagnostic](https://github.com/Eskstrom/marketplace-discovery-diagnostic) | Investigate how catalog structure prevents shoppers from finding products. | Concept brief |

## Making AI useful and trustworthy

Support, research, recruiting, and AI platform decisions: the shared question is what evidence makes an automated output useful enough to act on.

| Project | Problem and direction | Decision to investigate | Status |
| --- | --- | --- | --- |
| [ClarityDesk RAG](https://github.com/Eskstrom/claritydesk-rag) | Help support teams answer from sources and escalate unsupported questions with useful context. | When should the assistant answer, clarify, or abstain? | Concept brief |
| [Research Orchestra](https://github.com/Eskstrom/research-orchestra) | Make research conclusions traceable to collected evidence. | Do multiple agents improve citation quality enough to justify added complexity? | Concept brief |
| [Candidate Search Evaluation Lab](https://github.com/Eskstrom/candidate-search-eval-lab) | Find relevant experience that keyword searches can miss. | Compare semantic and keyword retrieval on labeled synthetic examples, including misleading matches. | Concept + scope and measurement plan |
| [Enterprise LLM Model Hub](https://github.com/Eskstrom/enterprise-llm-model-hub) | Select a model for the workload it must perform. | Balance task success, latency, cost per successful task, and governance constraints. | Case study |
| [Agent Use-Case Prioritizer](https://github.com/Eskstrom/agent-use-case-prioritizer) | Decide whether a workflow merits automation, assistance, investigation, or no intervention. | When should error cost and data limitations outweigh expected efficiency? | Concept brief |
| [Governance Guardrails Toolkit](https://github.com/Eskstrom/governance-guardrails-toolkit) | Translate launch concerns into specific controls and evidence requirements. | Why does one scenario require a control while another does not? | Concept brief |
| [Human Approval Workspace](https://github.com/Eskstrom/human-approval-workspace) | Help reviewers assess recommendations without rubber-stamping them. | Does the evidence display help people detect incorrect recommendations? | Concept brief |

## Helping operations teams act

Healthcare implementation, record reconciliation, financial operations, and data quality: make blockers visible, ownership explicit, and the next action understandable.

| Project | Problem and direction | Decision to investigate | Status |
| --- | --- | --- | --- |
| [AI Deployment Command Center](https://github.com/Eskstrom/ai-deployment-command-center) | Move customer deployments from installed to operationally usable. | Separate technical readiness from training, adoption, and unresolved launch blockers. | Concept + scope and measurement plan |
| [Clinical Feedback Insight Hub](https://github.com/Eskstrom/clinical-feedback-insight-hub) | Distinguish product defects, training gaps, and workflow mismatches in implementation feedback. | Let people correct classifications and explain why similar complaints need different responses. | Concept brief |
| [Referral Loop Simulator](https://github.com/Eskstrom/referral-loop-simulator) | Find where follow-up workflows lose people and explore operational interventions. | Does faster outreach solve the bottleneck or move it to appointment capacity? | Concept brief |
| [Eligibility Reconciliation Workbench](https://github.com/Eskstrom/eligibility-reconciliation-workbench) | Reconcile inconsistent records without silently joining the wrong people. | Set auto-match, review, and reject thresholds against synthetic ground truth and error costs. | Concept brief |
| [Agency Lending Operations](https://github.com/Eskstrom/agency-lending-operations-case-study) | Turn time-sensitive exceptions into accountable action. | Use explainable rules, one owner, and evidence-backed closure; retain review for high-severity overrides. | Case study + synthetic demo |
| [Workflow Exception Navigator](https://github.com/Eskstrom/workflow-exception-navigator) | Route operational cases to the right owner with enough context to act. | Explore reusable routing and handoff patterns across workflows. | Concept brief |
| [AI Data Quality Sentinel](https://github.com/Eskstrom/ai-data-quality-sentinel) | Catch broken inputs before they undermine downstream workflows. | Distinguish actionable changes from harmless variation and connect alerts to reproducible checks. | Concept brief |

Operational concepts use synthetic or fictional examples. The lending demo is static; proposed benefits and targets are not measured production outcomes.

## Making commerce easier to navigate

Help shoppers find relevant products and understand what they are buying. These concepts focus on the quality of product information and the decisions it enables.

| Project | Problem and direction | Decision to investigate | Status |
| --- | --- | --- | --- |
| [Marketplace Discovery Diagnostic](https://github.com/Eskstrom/marketplace-discovery-diagnostic) | Find products hidden by poor categories, missing attributes, and weak filter coverage. | Show the same shopping task before and after a catalog fix; weigh navigability against taxonomy complexity. | Concept brief |
| [Return-Risk Explainer](https://github.com/Eskstrom/return-risk-explainer) | Surface listing ambiguities that can cause preventable purchase misunderstandings. | Link each flag to missing or conflicting information without claiming proven reductions in returns. | Concept brief |

## Everyday tools, learning, and play

Small products are a place to explore clarity, interaction, and enjoyment. Games belong here as deliberate creative work: familiar rules make the quality of feedback and control especially visible.

| Project | Problem and direction | Design choice or next question | Status |
| --- | --- | --- | --- |
| [FocusFlow](https://github.com/Eskstrom/focusflow) | Help terminal users start focused work without switching to another planning app. | A CLI and local SQLite storage keep the workflow close to the work. Do tracking and analytics help focus or add overhead? | Implementation |
| [FocusFlow AI Planner](https://github.com/Eskstrom/focusflow-ai-planner) | Turn an ambitious task list into a schedule that fits available time. | Respect scheduling constraints and user overrides; complement FocusFlow's execution workflow. | Concept brief |
| [Case Study Evidence Studio](https://github.com/Eskstrom/case-study-evidence-studio) | Explain work clearly without overstating what happened. | Keep facts, assumptions, and unverified outcomes distinguishable through editing and export. | Concept brief |
| [Opening Explainer](https://github.com/Eskstrom/opening-explainer) | Understand why a chess move is played at the moment it appears. | Curated explanations sit beside the board in a static app. Next question: can learners transfer the ideas to unfamiliar positions? | Implementation |
| [2048 Game](https://github.com/Eskstrom/2048game) | Make a familiar puzzle approachable through responsive controls and clear feedback. | Keyboard and touch input, undo, synthesized sound, and saved preferences create tradeoffs around challenge, recovery, and distraction. | Implementation |

For future game experiments, the direction is a small playable experience around one original mechanic, with a design log connecting playtest observations to revisions.

## How I approach the work

Start with a person, a situation, and a reason to care. Compare approaches and explain the scope. Add controls around specific failures; keep interactions lightweight when the consequences are small. Separate what has been built or observed from what is proposed, and identify the next test that could change the design.

Implementation means source code is present, not a claim of production readiness or validated user outcomes. Concept entries describe intended directions, not completed features. The linked repositories contain the available detail.

## Get in touch

Explore the repositories above or connect through GitHub.
