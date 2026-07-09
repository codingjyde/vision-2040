# Decision 0002: Use Source Summaries for Handbook Alignment

Owner: Vision 2040 PMO

Status: Accepted

Date: 2026-07-09

## Context

The Leadership Handbook depends on several source documents, including the Vision 2040 presentation and the Workstream Job Descriptions & KPI Framework.

If each guide copies source material directly, the repository will become difficult to maintain. It will also become easier for guides to drift from the approved documents.

## Decision

Create extracted source summaries for key source material.

Initial source summaries include:

- Vision 2040 Goals
- Workstream KPI Framework Summary

Leadership Guides should reference these summaries and avoid redefining them.

## Consequences

This makes the handbook easier to maintain.

When a source fact changes, the source summary should be updated first. Dependent documents should then be reviewed.

Source summaries must not replace approved source documents. They are working aids for consistency and review.

## Affected Documents

- sources/vision-2040-goals.md
- sources/workstream-kpi-framework-summary.md
- templates/leadership-guide-template.md
- guides/leadership-handbook/*

## Review Note

Before a Leadership Guide is approved, its content should be checked against both the source summary and the approved source document.
