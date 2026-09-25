# AI Project Delivery Assistant

An AI-assisted project management portfolio demo that turns raw project updates into an executive-ready status summary, RAID analysis, action items, and go-live readiness view.

## Why I built it

After years of managing enterprise technology projects, customer implementations, production operations, and cross-functional escalations, I wanted to explore how AI could reduce project-management administration while improving visibility into risks, dependencies, decisions, and customer impact.

This is a portfolio project using **fictional data**. It does not contain confidential customer, employer, or production information.

## What it demonstrates

- Executive project status summarization
- Risk, assumption, issue, and dependency identification
- Action-item extraction and ownership
- Customer-impact analysis
- Escalation recommendations
- Go-live readiness assessment
- Human review and validation of AI output

## Demo

Open `index.html` locally in a browser, or publish the repository with GitHub Pages.

## AI workflow

```text
Raw project updates → Normalize → Identify risks/issues/dependencies → Assess impact → Generate executive summary → Extract actions → Assess go-live readiness → Human review
```

## Example AI prompt

> You are an enterprise project delivery assistant. Review the project updates below and produce an executive status summary, RAID analysis, customer impact, actions with owners and timing, escalations requiring leadership attention, and go-live readiness. Do not invent facts. Clearly distinguish known facts from recommendations and flag missing information.

## Important design principle

AI is used as an **assistant**, not the final decision-maker. A project manager should validate dates, owners, impacts, contractual commitments, customer communications, and escalation decisions before information is distributed.

## Technology

HTML, CSS, JavaScript, structured fictional project data, and LLM-ready prompt design. A production implementation could connect to Jira, CRM/project systems, Microsoft 365, or an LLM API with appropriate security and governance.
