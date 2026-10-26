# PRAXIS

### Business Process Optimization & Automation

**Simulated operations, SQL database, EPC process maps, and human-reviewed workflows.**

PRAXIS is an operations software prototype built around a practical business problem: incoming service requests need clear review, ownership and follow-through. A message being read does not mean the underlying issue has been resolved.

The demonstration follows a fictional commercial-equipment maintenance company in Quebec. It brings service intake, coordinator review, assigned follow-ups and technician visibility into one workspace.

## What the prototype demonstrates

| Business need | Demonstrated capability |
| --- | --- |
| Find incoming requests | Searchable inbox with original message details |
| Identify messages needing attention | Review queue with clear recorded dispositions |
| Keep human judgment in the process | Saved review decisions, notes and history |
| Make responsibility visible | Assigned follow-ups with open and resolved states |
| Inspect technician work | Team directory and individual workload windows |
| Explain technician scores | Score table with visible component totals |
| Support process analysis | Private EPC process documentation and improvement hypotheses |
| Check data consistency | SQL-backed relationship and integrity checks |

## Demonstration environment

- **6,523 simulated incoming messages** with varied wording, sender addresses and demand patterns.
- **178 fictional customers** across **321 facilities**, with **944 equipment assets**.
- **30 fictional staff members**, including **22 technicians**.
- English and French examples, incomplete details, follow-ups and other intake exceptions.

All names, communications and business records are fictional. The dataset is a demonstration corpus rather than a live company backlog. No client results or measured time savings are represented.

## Technology and professional scope

**Python · SQL / SQLite · Streamlit · Business analysis · EPC process mapping · Workflow controls · Automated testing**

The work combines process analysis, data modelling, application development and functional validation. The current private implementation has passed **43 automated tests**, including data integrity, review persistence, follow-up handling, technician workload isolation and score calculations.

## Project status

**Functional local prototype — under active development.**

The implemented screens support intake exploration, human review, follow-up tracking and team visibility. Scheduling, work-order execution and a complete service-case lifecycle remain in development. There is no public hosted application or production deployment associated with this repository.

## About this repository

This is a **public portfolio showcase**, not the application source repository. Source code, database files, internal architecture, detailed process maps, business rules, scoring formulas and development history remain private. This repository contains presentation material only.

Copyright © 2026. All rights reserved. No open-source license or implementation rights are granted.
