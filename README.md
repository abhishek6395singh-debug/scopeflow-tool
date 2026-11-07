# ScopeFlow — Presales Scoping Tool

A browser-based scoping workspace for IT services and software implementation teams. It helps Presales and Implementation teams capture requirements, build role-based estimates, outline delivery phases, record scope boundaries and risks, and prepare a draft proposal.

## Run locally

No build step, package manager, backend, or API key is required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Start with Project details, then complete Requirements, Estimation, Delivery plan, and Scope & risks.
4. Review Proposal and choose **Print / Save PDF** to create a PDF.

## Features

- Opportunity and client details
- Requirements register with priority and complexity
- Role-based person-day and daily-rate estimation
- Contingency and additional expense calculations
- Delivery phases, durations, outputs and owners
- In-scope / out-of-scope statements, assumptions and risks
- Live dashboard with effort, duration, estimate and completeness indicators
- Draft SOW / proposal preview and browser print-to-PDF
- JSON project export
- Automatic local browser storage

## Currency note

USD is the default display currency. INR, GBP and EUR are also available. Changing the currency selector changes the currency label/format only; it does **not** convert existing rates using an exchange rate. Enter role rates and expenses in the currency selected for the project.

## Data and privacy

This is a standalone front-end MVP. Project data is stored in the current browser using localStorage and is not sent to a server. Clearing browser site data may remove the saved project. Use **Export JSON** to keep a portable backup. There is no user authentication, shared database, or multi-user collaboration in this version.

## Disclaimer

Effort, duration and pricing are indicative planning estimates. Validate assumptions, scope, dependencies, taxes, third-party costs and commercial terms before issuing a client-facing statement of work.
