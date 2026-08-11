# Repository Instructions

## Repository purpose

This repository contains AI-enablement documentation, GitHub issue templates, and reusable Markdown templates. Preserve the plain-language, non-engineer-friendly tone used in `CONTRIBUTING.md`.

## Layout

- `.github/ISSUE_TEMPLATE/`: GitHub Issue Forms and issue templates.
- `templates/`: Markdown templates intended for direct reuse in issues or recurring reviews.
- `CONTRIBUTING.md`: Contributor process and response-time expectations.

## Making changes

- Keep changes small and limited to the requested documentation or template.
- Reuse existing terminology and formatting where applicable.
- Use Markdown headings, brief instructions, and placeholders that make templates quick to complete.
- For GitHub Issue Forms, use valid YAML and include clear labels, descriptions, and required-field validation when appropriate.
- Do not add credentials, sensitive data, or organization-specific examples.

## Validation

- Review the rendered Markdown for readable headings, tables, and task lists.
- Check YAML syntax after changing Issue Forms.
- Run `git diff --check` before submitting changes.
- In pull requests, state the user-facing purpose of the change and list any validation performed.
