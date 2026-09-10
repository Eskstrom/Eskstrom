# Documenting project judgment

Use this outline inside a project repository when there is enough evidence to explain a decision. For a concept, describe the proposed approach and the next validation step. For an implementation, link to the relevant code, test, or observation.

## Problem and context

Who is this for? Describe a concrete situation, what the person wants to do, and where the current approach creates friction. For a game, the aim can be enjoyment, exploration, or learning rather than a business problem.

## Alternatives and choice

Describe the chosen approach and at least one plausible alternative. Explain the constraint that influenced the choice, the benefit expected, and the cost accepted. Distinguish a rationale documented at the time from a later interpretation of the implementation.

## Controls and boundaries

Identify the specific failure a control prevents. Explain when review, validation, undo, or abstention is appropriate. Where a control is omitted, record the scope or consequence that makes the omission reasonable. Do not add a checklist that is unrelated to the actual workflow.

## Evidence and learning

Record what was tested, the conditions, the observed result, and its limits. Link evidence where available. Keep targets, simulation outputs, and measured outcomes separate. If no test has been run, state the question still open rather than inventing a learning.

## Next decision

Name the smallest test that could change the approach. Specify what outcome would lead to keeping, revising, or dropping it.

## Short decision record

| Field | What to capture |
| --- | --- |
| Status and date | Proposed, implemented, evaluated, or superseded; date of the record. |
| Trigger | The user situation or observed failure. |
| Choice | The decision and plausible alternative. |
| Tradeoff | Expected benefit and accepted cost. |
| Evidence | Code, test, notes, or an explicit evidence gap. |
| Next test | What could change the decision. |
