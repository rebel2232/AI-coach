# VIA — Violence Investigation Agent

A prototype healthcare workplace violence investigation tool designed for managers conducting Code White and other workplace violence investigations.

## Overview

VIA streamlines the investigation workflow that managers complete after a workplace violence incident by:

- Auto-populating data from intake systems
- AI-extracting narratives from uploaded security reports
- AI-drafting sequences of events, contributing factor analysis, and corrective actions
- Standardizing violence-context questions and contributing factor taxonomy
- Preparing content for transfer to Web IIT (the system of record)

## Features

### Dashboard
- Overdue alerts with deadline tracking (48-hour and 30-day marks)
- Filter by status (overdue, in progress, not started)
- Delegate access management

### 10-Section Investigation Workflow
1. Incident details — Auto-populated from provincial intake
2. Training compliance — LMS data with refresher status flags
3. Security report — PDF upload with AI narrative extraction
4. Staff statements — Auto-populated from PWHCC + follow-up notes
5. Witnesses — Manager-entered with structured prompts
6. Scene & context — Environmental Yes/No/N/A checklist + contextual factors
7. Sequence of events — AI-drafted, manager-editable timeline
8. Violence context questions — AI answers 13 standardized questions with confidence levels
9. Contributing factors — AI pre-selects from standardized taxonomy
10. Corrective actions — AI-suggested with action/reason split, copy-ready for Web IIT

### AI Investigation Assistant
Embedded chatbot that answers questions about the investigation with confidence ratings and explicit assumptions.

## Tech Stack

- Frontend: Vanilla HTML, CSS, JavaScript (no framework, no build step)
- AI: Anthropic Claude API
- Hosting: Static — runs anywhere

## Quick Start

Run locally by opening `index.html` in a browser, or:
