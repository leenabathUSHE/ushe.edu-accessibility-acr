# Accessibility ACR Tracker – 2026

## Purpose

This repository tracks accessibility testing, issues, and documentation used to create the 2026 Accessibility Conformance Report (ACR) for our website.

## Goals

* Track WCAG 2.1 AA compliance
* Document accessibility issues and remediation progress
* Provide evidence for ACR statements
* Maintain an audit trail for compliance

---

## Testing Methods

* Automated: axe DevTools, Lighthouse, WAVE
* Manual:

  * Keyboard navigation
  * Screen reader testing (NVDA/VoiceOver)
  * Color contrast checks
  * Focus order verification

---

## Repository Structure

* `/acr/` → Final ACR document (YAML or exported report)
* `/testing/` → Testing notes and results
* `/evidence/` → Screenshots, reports, and supporting files

---

## Labels Guide

| Label           | Meaning                      |
| --------------- | ---------------------------- |
| wcag-*          | WCAG success criterion       |
| severity-high   | Critical accessibility issue |
| severity-medium | Moderate issue               |
| severity-low    | Minor issue                  |
| automated-test  | Found via automated tools    |
| manual-test     | Found via manual testing     |
| needs-fix       | Requires remediation         |
| in-progress     | Currently being worked on    |
| done            | Issue resolved               |

---

## Workflow

1. Run accessibility tests
2. Create GitHub Issues for findings
3. Assign labels and severity
4. Fix issues or document limitations
5. Reference issues in ACR

---

## ACR Mapping (Example)

| WCAG Criterion         | Related Issues |
| ---------------------- | -------------- |
| 1.1.1 Non-text Content | #12, #18       |
| 2.1.1 Keyboard         | #25            |
| 1.4.3 Contrast         | #30, #31       |

---

## Timeline

* Testing Complete: [DATE]
* ACR Draft: [DATE]
* Final Submission: [DATE]
