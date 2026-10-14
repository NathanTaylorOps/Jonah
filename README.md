# Monday delivery control

A focused operational example supporting the Head of Operations & Delivery practical assessment.

The deliverable is a **Monday founder review across six fictional engagements**. It brings together client commitments, consultant allocations, a four-week coverage outlook, verified mobilisation prerequisites, direct delivery cost forecasts and decisions requiring ownership. The outlook counts only recorded commitments; it does not imply unverified people are available or that blank weeks have spare capacity. It is intentionally small enough for a founder-led consultancy to maintain.

## Review the material

1. Read **[the assessment](assessment.md)** for the discovery questions, initial 90-day priorities and management rationale.
2. Download or clone the repository and **open `index.html` locally** in a modern browser. No dependencies, login or server required.
3. Use the example scenario controls to inspect allocation approval and a change in forecast direct cost, then reset to the initial view.
4. Print in **A4 landscape** for the weekly founder report. The printed version excludes the scenario controls.

The browser page is **not** automatically hosted by GitHub simply because its source is committed here.

## Operating rules

- The six clients, people, dates, fees and costs are illustrative; no company internal records are used.
- Consultant allocation has distinct **confirmed**, **tentative** and **proposed** states. Overlap is tested against time-zone-qualified time windows and stable consultant identifiers, not merely calendar dates or display names. Example time windows use Australian Eastern Standard Time (UTC+10), and national deployment would need verified location-specific time zones, travel and recovery. A proposed replacement is not available for confirmed delivery until suitability and approvals are established.
- A mobilisation prerequisite without evidence is not ready. Site access, inductions, preparation, travel and any task-specific authorisations must be checked against the actual engagement; the demonstration does not imply universal statutory clearance requirements for all workshop facilitators.
- Commercial exposure remains visible independently of scheduling actions.
- Forecast direct cost is committed direct cost plus forecast remaining direct cost. Forecast direct margin uses authorised fee only; it is neither net profit nor EBITDA. Unknown values remain unknown.
- Commercial alert thresholds are examples for discussion, not company policy.

## Scope and verification

This is an interview demonstration, not a production booking, authorisation, finance or specialist methodology system. It has no persistent storage, client access or third-party integrations.

Run **`node test.js`** for scenario and arithmetic checks. GitHub Actions runs the same verification when changes are submitted. Inspect browser print preview before using the page as a one-page landscape report. The separate PDF founder view is a reviewed, fixed snapshot of the starting scenario rather than an automatically synchronised export of subsequent interactive changes.
