# AI Enablement

This repository contains AI-enablement documentation, GitHub issue templates, and reusable Markdown templates for teams piloting AI workflows. It is written for a non-engineer audience — no coding experience is needed to use or contribute to it.

## Overview

Teams across the organization are exploring, piloting, and rolling out AI capabilities (tools, workflows, and integrations). This repository is the shared home for that work: a lightweight, low-friction way to propose an idea, track a pilot's progress, and report on adoption over time — all using standard GitHub issues, so no separate tracker or spreadsheet is required.

## Purpose

- **Reduce friction for non-engineers.** Anyone can propose or report on an AI pilot using a short, guided issue form — no special tools or technical background needed.
- **Standardize how adoption is tracked.** A consistent set of fields (workflow, owner, launch date, adoption percentage, blockers, next step) makes it easy to compare pilots and spot ones that need support.
- **Keep reporting lightweight.** Templates are designed to take under five minutes to complete, so regular check-ins don't become a burden.
- **Automate the reminder, not the decision-making.** A scheduled workflow surfaces open pilots needing an update each week; humans still decide what to report.

## What's here

- **`.github/ISSUE_TEMPLATE/`** — Issue forms and templates for reporting on AI pilots:
  - `adoption-tracking.yml` — Track a team's adoption of an AI capability from exploration through rollout.
  - `adoption-update.md` — A short (under five minutes) recurring progress update for an active pilot.
- **`.github/workflows/weekly-adoption-review.yml`** — A scheduled GitHub Actions workflow that opens a weekly review issue listing every open pilot (issues labelled `adoption`) so owners remember to post an update. Runs every Monday and can also be triggered manually from the Actions tab.
- **`templates/`** — Markdown templates for direct reuse in issues or recurring reviews:
  - `adoption-kpi-template.md` — A table for tracking adoption percentage and status across pilots during a recurring review meeting.
  - `intake-request-template.md` — A template for requesting a new AI capability or workflow.
- **`AGENTS.md`** — Instructions for AI coding agents making changes in this repository.
- **`CONTRIBUTING.md`** — How to propose changes, submit pull requests, and what response times to expect.

## How adoption tracking works

1. A team opens an **Adoption tracking** issue (`adoption-tracking.yml`) when it starts piloting an AI capability. This is automatically labelled `adoption`.
2. The team posts recurring **Adoption update** issues (`adoption-update.md`) or comments to report progress, blockers, and next steps.
3. Every Monday, the **Weekly adoption review** workflow opens a new issue listing all open `adoption`-labelled issues, prompting owners to check in.
4. Data lives entirely in GitHub Issues — there is no external database or spreadsheet to maintain.

## Getting started

- To propose an idea or report an issue, open a new issue using the template that best fits.
- To make a change, see [`CONTRIBUTING.md`](CONTRIBUTING.md) for the process and expected response times.
