# Canal Resource Guide — Interactive Prototypes

Three interactive prototypes for a bilingual (English/Spanish) community resource guide serving the Canal neighborhood of San Rafael, Marin County. Built using Claude AI and deployed live on the Marin Promise Partnership website for community feedback.

## Live Demos

- **Option A — Conversational Chat:** https://www.marinpromisepartnership.org/canal-resources-option-a/
- **Option B — Browse by Category:** https://www.marinpromisepartnership.org/canal-resources-option-b/
- **Option C — Smart Finder:** https://www.marinpromisepartnership.org/canal-resources-option-c/

## The Problem

The Canal neighborhood is home to a large Spanish-speaking immigrant community in Marin County. Existing resource guides were static PDFs — hard to search, hard to navigate on a phone, and only available in English. Community members and navigators needed a faster, more accessible way to find services across housing, health, food, legal aid, education, and more.

## The Approach

Starting from an existing resource guide document, three distinct interaction models were prototyped to test different user experiences:

**Prototype A — Chat:** A conversational interface where users describe their need in plain language (English or Spanish) and receive matched resources. Designed for users who know what they need but not which organization provides it.

**Prototype B — Browse:** A category-based directory with filtering. Designed for users who want to explore what's available rather than search for something specific.

**Prototype C — Smart Finder:** A guided questionnaire that narrows resources based on eligibility criteria (household size, language, documentation status, etc.). Designed for navigators helping clients find the right match quickly.

## What's in This Repo

```
prototype-a-chat.html          — Conversational chat interface
prototype-b-browse.html        — Browse and filter directory
prototype-c-smart-finder.html  — Guided eligibility-based finder
```

Each prototype is a single self-contained HTML file with embedded CSS and JavaScript. No build step, no dependencies, no server required — open in any browser.

## How It Was Built

These prototypes were built using Claude AI (Anthropic) via Claude Cowork, working from a source resource guide document. The workflow:

1. Source document ingested and resource data extracted
2. Three interaction models designed based on different user personas
3. Each prototype built as a single HTML artifact
4. Shared with the MPP team and community partners for feedback via the live URLs above

Total build time from document to three live deployed prototypes: approximately one working day.

## What This Demonstrates

- Rapid prototyping of community-facing tools using AI
- Bilingual (English/Spanish) interface design
- Multiple UX approaches to the same underlying data problem
- Deployment of AI-built tools into a real organizational context for community feedback

## Context

Built at [Marin Promise Partnership](https://www.marinpromisepartnership.org) as part of the Canal Promise Neighborhood initiative. The Canal neighborhood has one of the highest concentrations of Latino residents in Marin County, with significant resource access barriers related to language, documentation, and digital literacy.
