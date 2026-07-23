# Feature: Site Audit & Refresh

## Meta
- Owner: Otavio Coelho
- Status: shipping
- Priority: High
- Last updated: 2026-07-23

## Problem
The personal website was dormant for ~2 years and reflected a 2023 junior developer / bootcamp graduate persona rather than Otavio's actual current role as Founder & CEO @ ONSTOQ, Technical Product Leader, and AI Specialist.

## Target users
- Hiring managers, VCs, potential partners, and prospective employers looking for technical leadership and AI expertise.

## Success metrics
- Complete and accurate professional positioning.
- Zero broken links / typos in core configuration (`config.toml`).

## Risks
- Low engagement if content is too generic or dated.

## Dependencies
- None (Hugo SSG, static config updates).

## Timeline
- 2026-07-23: Site audit performed, resume ingested, `config.toml` updated with Founder & CEO profile.

## Evidence
- Source: [`../../../source/adhoc/2026-07-23-linkedin-resume.md`](../../../source/adhoc/2026-07-23-linkedin-resume.md)
- Ingestion: [`../../../ingestion/adhoc/2026-07-23-linkedin-resume.md`](../../../ingestion/adhoc/2026-07-23-linkedin-resume.md)

## Linked
- Hypotheses: TODO: none yet
- Decisions: TODO: none yet
- Stakeholders affected: TODO: none yet

## Open questions
- Should we add posts/pages detailing ONSTOQ or AI projects (e.g. ComfyUI/Blender pipelines, Ray tracer, Ruby doc browser)?

## Follow-up after launch
- Test building the Hugo site locally (`hugo server`) to verify rendering of terminal theme.
