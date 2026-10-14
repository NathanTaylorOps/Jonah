# Monday delivery control

A focused operational example supporting the Head of Operations & Delivery practical assessment.

The deliverable is a **Monday founder review across six fictional engagements**. It brings together confirmed client commitments, consultant allocation, mobilisation evidence, forecast direct costs and the decisions requiring ownership. It is intentionally small enough for a founder-led consultancy to maintain.

## Review the material

1. Read **[the assessment](assessment.md)** for the discovery questions, initial 90-day priorities and management rationale.
2. Download or clone the repository and **open `index.html` locally** in a modern browser. No dependencies, login or server required.
3. Use the example scenario controls to inspect allocation approval and a change in forecast direct cost, then reset to the initial view.
4. Print in **A4 landscape** for the weekly founder report. The printed version excludes the scenario controls.

The browser page is **not** automatically hosted by GitHub simply because its source is committed here.

## Operating rules

- The six clients, people, dates, fees and costs are illustrative; no company internal records are used.
- Consultant allocation has distinct **confirmed**, **tentative** and **proposed** states. A proposed replacement is not available for confirmed delivery until suitability and approvals are established.
- A mobilisation prerequisite without evidence is not ready.
- Commercial exposure remains visible independently of scheduling actions.
- Forecast direct cost is committed direct cost plus forecast remaining direct cost. Forecast direct margin uses authorised fee only; it is neither net profit nor EBITDA. Unknown values remain unknown.
- Commercial alert thresholds are examples for discussion, not company policy.

## Scope and verification

This is an interview demonstration, not a production booking, authorisation, finance or specialist methodology system. It has no persistent storage, client access or third-party integrations.

Run **`node test.js`** for scenario and arithmetic checks. GitHub Actions runs the same verification when changes are submitted. Inspect browser print preview before using the page as a one-page landscape report.
