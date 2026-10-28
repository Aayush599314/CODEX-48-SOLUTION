# Inkloom AI

This repository contains a single-page HTML concept prototype for Inkloom AI, a demo for a pre-publication brand review experience.

The page is designed as a marketing landing page and interactive mock demo. It presents the idea of reviewing draft content against approved brand guidelines, product facts, terminology, and visual consistency before publication.

## What the project shows

From the page content, the project highlights a fictional workflow where a draft is checked for issues such as:

- naming inconsistencies
- unsupported growth claims
- mismatches between claimed and approved features
- review decisions that are explained with evidence
- human approval or escalation before publishing

The demo includes:

- a hero section and brand-style landing page
- a “Problem” section explaining brand governance challenges
- an interactive demo with a sample draft and review findings
- a six-step workflow: ingest, analyse, retrieve, explain, route, decide
- audience sections for content creators, brand managers, reviewers, and agencies
- a trust section describing evidence-backed and human-controlled review decisions

## Project structure

- `Inkloom AI.html` — the complete static HTML page containing the styling, content, and JavaScript demo logic

There are no separate app files, frameworks, or backend services in this repository based on the available project content.

## How to view it

Open `Inkloom AI.html` in a browser to view the landing page and interactive mock review demo.

If you want to serve it locally:

```bash
python -m http.server
```

Then open the page in your browser, usually at:

```text
http://localhost:8000/Inkloom%20AI.html
```

## Notes

This is a demo/prototype, not production software. The content and sample findings are fictional and are presented as a concept for a brand review workflow.

## Future scope

Possible next steps, based on the concept shown in the page, include:

- integrating real brand guidelines and approved content sources
- connecting the review flow to a CMS or content publishing workflow
- adding role-based review routing and audit tracking
- supporting real evidence lookup and citation mapping
- expanding the demo into a functional app with backend storage and API integration
- adding accessibility, localisation, and reporting improvements

