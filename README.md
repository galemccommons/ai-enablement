# AI Enablement

AI-enablement documentation, GitHub issue templates, and reusable Markdown templates for teams piloting AI workflows. Written for a non-engineer audience — no coding experience needed.

A team opens an **Adoption tracking** issue to start a pilot, then posts recurring **Adoption update** issues to report progress. Every Monday, an automated workflow opens a review issue listing open pilots so owners remember to check in. All data lives in GitHub Issues — no external tracker or spreadsheet required.

## What's here

- **`.github/ISSUE_TEMPLATE/`**
  - `adoption-tracking.yml` — Start and track a pilot from exploration through rollout. Labelled `adoption`.
  - `adoption-update.md` — A short (under five minutes) recurring progress update, linked to its pilot. Labelled `adoption-update`.
- **`.github/workflows/weekly-adoption-review.yml`** — Opens a weekly (Monday) issue listing open `adoption`-labelled pilots. Can also be run manually from the Actions tab.
- **`templates/`**
  - `adoption-kpi-template.md` — A table for tracking adoption % and status across pilots in a recurring review meeting.
  - `intake-request-template.md` — Request a new AI capability or workflow.
- **`AGENTS.md`** — Instructions for AI coding agents working in this repository.
- **`CONTRIBUTING.md`** — How to propose changes and submit pull requests.

## Getting started

- To propose an idea or report progress, open a new issue using the template that best fits.
- To make a change, see [`CONTRIBUTING.md`](CONTRIBUTING.md) for the process and expected response times.
