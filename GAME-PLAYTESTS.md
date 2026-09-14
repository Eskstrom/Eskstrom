# Learning from small games

This is a proposed playtest plan, not a report of completed user testing. It gives the game and learning projects concrete questions to investigate before adding more features.

## 2048: control, recovery, and feedback

Ask a player to start a game, make several moves, undo a mistake, toggle sound, and restart. Repeat with keyboard and touch input where devices are available.

Observe whether the player discovers the controls, whether swipes move in the intended direction, and whether undo restores the state they expected. Ask whether sound clarifies the result of a move or becomes distracting. Record the device and input method alongside observations.

The design question is how recovery affects challenge. If undo makes experimentation more enjoyable, keep it easy to reach; if players want a stricter challenge, investigate an optional mode rather than removing recovery for everyone.

Technical checks to accompany playtesting: a tile merges at most once per move; an unchanged board does not spawn a tile; undo restores score and board; restart clears move history. These are checks to perform, not claims of passing tests.

## Opening Explainer: understanding beyond memorization

Ask a learner to step through one opening and describe the purpose of a selected move in their own words. Then show a related unfamiliar position and ask which idea might still apply.

Observe navigation errors separately from conceptual misunderstandings. If the explanation can be repeated but not applied, test a concrete example or a short question before expanding the opening catalog. Have chess explanations reviewed for accuracy before treating learner outcomes as evidence about the teaching design.

## A future original game: one mechanic first

Write down the intended experience, one core rule, and what makes a player choice interesting. Build the smallest playable loop and observe whether players understand the consequences of an action without coaching. Add content after the core choice is understandable and worth repeating.

## Record each session

Capture the build version, device, task, observed behavior, optional player comment, and proposed change. Avoid collecting unnecessary personal information. Report how many sessions informed a conclusion and distinguish an individual preference from a repeated pattern.

For each revision, record the observation that prompted it and what the next playtest should resolve. A small number of sessions can reveal usability issues; it does not establish broad engagement or learning gains.
