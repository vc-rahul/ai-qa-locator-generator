---
name: qa-locator-generator
description: Generates stable automation locators and Playwright selectors
version: 1.0.0
---

# QA Locator Generator

## Purpose

Generate reliable, automation-friendly selectors from analyzed DOM.

This skill converts UI elements into:
- Playwright locators
- resilient selectors
- test-ready actions

---

## Inputs

- DOM analysis output
- page HTML
- user flows
- test scenarios

---

## Responsibilities

1. Identify interactive elements
2. Generate stable selectors
3. Avoid brittle locators
4. Prefer semantic attributes
5. Output Playwright-ready code

---

## Locator Priority

1. data-testid
2. aria-label
3. role selectors
4. text selectors
5. CSS fallback

Avoid:
- nth-child
- dynamic class names
- inline indexes

---

## Output Format

Return:

- locator map
- Playwright snippets
- selector confidence score