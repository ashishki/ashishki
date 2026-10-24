# Georgia Community Navigator

A Telegram guide and AI assistant prototype for people navigating administrative
tasks in Georgia.

**Stage — 24 October 2026:** private development project. The active branch
contains implemented guide, navigation, and opt-in AI work. Its 24 October
checkpoint records S1 semantic acceptance: 12/12 cards and 5/5 dialogues are
acceptable under the versioned rubric, including minor-only partial results.
Live testing and release are recorded as unperformed. This is a bounded
recording-transport result, not a public launch or proof of user outcomes.

## The workflow

A person needs an understandable route through a practical task: what applies,
what information is missing, and where the explanation came from. Searching
scattered pages is different from understanding the next step.

The delivery order is:

1. Useful topic guides, onboarding, and clear navigation.
2. The paid assistance layer.
3. The specialist foundation.

Commercial terms and later-stage implementation remain separate decisions.

## Representative journey

This is an illustrative journey, not a recorded user outcome.

A user opens a topic guide, chooses a section, and reads a source-backed card.
Back, Home, and Resume keep navigation predictable without calling a model.
If the user explicitly enables assistance, they can ask a question about their
task. The assistant uses the available material, identifies missing conditions,
and can seek a source for a specific unresolved point. A displayed instruction
does not mean the user has completed the task.

The implementation includes source/version handling, persistent task context,
and controlled delivery. Existing document-explanation experiments and generated
PDFs have their own version-specific limits; they do not establish complete
support for every incoming document.

## Engineering and checks

The project combines a Python Telegram interface, PostgreSQL and Redis state,
source-backed retrieval, and model-assisted answers. Guide navigation is
deterministic; language models enter the explicitly activated assistance flow.

Recorded checks cover navigation and state, source conditions, answer coverage,
context retention, delivery, and recovery. Historical dialogue evaluations belong
to their dated builds. Passing code checks does not establish that an
administrative explanation is complete or that a user can successfully finish
the real-world task.

The next evidence needed is a separately authorized live journey and observed
user usefulness. No adoption, time-saving, legal-accuracy, or
revenue metric is claimed.

## Publication boundary

This summary is based on the private project's active task ledger and status
records inspected on 24 October 2026. Private source documents, user messages,
account data, and operational records are excluded.

[Back to the portfolio](../README.md)
