# .github

Organization-wide GitHub defaults and the public profile shown at github.com/ada-tech-org.

## Issue templates

The shared [issue templates](.github/ISSUE_TEMPLATE/) cover tasks, bugs, epics and
spikes. They help preserve the context needed to understand, carry out and review
work without relying on the original conversation.

| Template | Use for |
| --- | --- |
| [Task](.github/ISSUE_TEMPLATE/task.md) | A defined change with verifiable results. |
| [Bug report](.github/ISSUE_TEMPLATE/bug.md) | Incorrect behavior to investigate and fix. |
| [Epic](.github/ISSUE_TEMPLATE/epic.md) | A larger outcome delivered through related issues. |
| [Spike](.github/ISSUE_TEMPLATE/spike.md) | A bounded investigation that informs a decision or subsequent work. |

### Writing a useful issue

- Summarise essential context and link supporting detail. Explain why a reference
  matters rather than relying on a link to the original discussion alone.
- Separate agreed requirements and constraints from suggested approaches. State
  confirmed findings, hypotheses and unknowns accurately; do not invent missing details.
- Include concrete examples, inputs, outputs or screenshots when they clarify the work.
- Describe observable acceptance criteria and how to verify them. Shared review,
  testing and completion rules remain in the team's workflow and repository instructions.
- Keep detail proportional to the work. Use the sections to expose useful context,
  not to fill space. Combine overlapping sections and remove irrelevant ones and
  unused prompts; do not omit a material dependency or uncertainty to make an issue shorter.

Before handing off an issue, check whether someone unfamiliar with the original
conversation can explain the intended result, identify the boundaries, find the
necessary context and determine whether the work succeeded.

An idea can be captured before all answers exist. Identify what must be resolved
before implementation and what can be investigated during the work. A completed
template alone does not establish that the issue is ready to start. Keep the
description current as scope or decisions change, with comments preserving the
reason for significant changes.

### GitHub defaults

GitHub offers these defaults in repositories that have no issue templates or
issue-template configuration of their own. A repository's own configuration
replaces the inherited set. Changes take effect after merging into this
repository's default branch.

Task, Bug report and Epic templates set the matching issue type. The Spike
template leaves the type unset until an organization owner creates the Spike
issue type; then add `type: Spike` to its frontmatter.

Maintain the issue structures here so people and tools can use the same files.
These templates are public; keep their guidance generic and free of internal or
customer information.
