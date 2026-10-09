# Software Eng — AI prompts

Copy any prompt below into ChatGPT, Gemini, Claude, Copilot, Perplexity or Grok. Replace the `{{ }}` parts and “(paste here)” with your own details.

## Code review

```
Review the change below.
Order: possible bugs, edge cases, readability, missing tests. Label each finding high/medium/low and separate real problems from matters of taste.

Diff or code:
(paste here)
```

## Debug an error

```
Help me find the cause of this error.
List the three most likely causes, with how to verify each and how to fix it. Ask me for anything you need to know.

Error and context:
(paste here)
```

## Write a function

```
Write a {{Language}} function for this spec: {{Spec}}
Validate inputs and handle errors, note the complexity if it matters, and include a usage example and a few tests.
```

## Refactor without changing behavior

```
Suggest a refactor of the code below that keeps behavior identical.
Bullet what you'd change and why, show the new code, and list any change that carries risk separately.

Code:
(paste here)
```

## Pull request description

```
Write a pull request description from the diff below.
Sections: summary, why, what changed, how to test, risks and rollout notes. Don't mention anything that isn't in the diff.

Diff or notes:
(paste here)
```

## Test case brainstorm

```
List test cases for the feature below.
Cover happy path, boundaries, failure modes, permissions, concurrency. Table: setup / action / expected result. Highest priority first.

Feature spec:
(paste here)
```

## Explain it to a non-engineer

```
Explain the technical concept below to a non-engineer colleague.
A three-sentence explanation with an analogy, one concrete example, and a common misconception with how to avoid it.

Concept:
(paste here)
```

## Design options

```
Compare design options for the problem below.
Give three approaches with pros, cons, and when each fits; then three questions that would settle the choice.
I'll decide; just lay out the trade-offs.

Problem and constraints:
(paste here)
```

## Postmortem draft

```
Draft a blameless postmortem from the notes below.
Summary, impact, timeline, root cause, what went well, what didn't, follow-up actions.
Focus on systems, not people; mark unknowns "needs confirmation".

Incident notes:
(paste here)
```

## SQL / regex / shell helper

```
Write the {{Kind:SQL|Regex|Shell command}} for this requirement: {{Requirement}}
Explain what each part does, and point out inputs that could break it.
```

## README draft

```
Draft a README for the code below.
Overview, setup, usage with examples, configuration, FAQ. Only describe what the code shows; mark guesses "verify".

Code or spec:
(paste here)
```

## Commit message

```
Write a commit message for this change.
Imperative subject under 50 characters, then a body explaining why. Don't include anything not in the change.

Change:
(paste here)
```
