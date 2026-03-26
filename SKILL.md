---
name: qa-locator-generator
description: Automatically generate robust automation locators from DOM elements.
author: Rahul Ranpura
license: MIT
version: 1.0.0
tags:
  - qa
  - automation
  - locator
  - playwright
  - selenium
  - testing
---

# QA Locator Generator

## Overview
QA Locator Generator creates reliable selectors automatically for UI automation frameworks.

It converts DOM elements into optimized locators.

## Capabilities

- Generate Playwright locators
- Generate Selenium selectors
- Prioritize accessibility attributes
- Avoid brittle XPath
- Provide multiple locator options

## Locator Priority

1. data-testid
2. aria-label
3. role
4. unique id
5. css selector
6. xpath (fallback)

## Usage

Use when:
- Writing new automation scripts
- Migrating frameworks
- Improving locator quality

## Output

- Playwright locator
- Selenium locator
- CSS selector
- XPath fallback