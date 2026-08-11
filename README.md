# AI Enablement

This is where we keep track of AI pilots happening across the org — the templates, the docs, all of it. You don't need to be an engineer to use anything here; if you can fill out a form, you're set.

Here's how it works in practice: your team opens an **Adoption tracking** issue when you kick off a pilot, then checks back in with **Adoption update** issues as things progress. Every Monday, a little automation opens a review issue rounding up what's still open, just so nothing falls through the cracks. Everything lives in GitHub Issues — no extra spreadsheet or tracker to remember to update.

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
