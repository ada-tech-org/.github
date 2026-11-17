# .github

Organization-wide GitHub defaults and the public profile shown at github.com/ada-tech-org.

## Shared templates

The [issue templates](.github/ISSUE_TEMPLATE/) (Task, Bug report, Epic and Spike)
apply in repositories that have no issue templates or issue-template configuration
of their own. The [PR template](.github/pull_request_template.md) applies,
independently, in repositories that have no PR template of their own. In GitHub's
web editor, each issue template sets the matching organization issue type. Changes
take effect after merging into this repository's default branch.

Issues and pull requests created through the API, or through the `gh` CLI with the
body supplied, get no template, and an issue gets a type only when one is passed
(`--type` in the CLI). Read the template, write the body under its headings without
the guidance comments, and set the issue type and any parent or blocking
relationships explicitly.

These templates are public; keep their guidance generic and free of internal or
customer information.
