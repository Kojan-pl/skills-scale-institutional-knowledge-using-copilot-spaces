# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Roles

The following personas own key release activities. See [Roles & Personas](octoacme-roles-and-personas.md) for full descriptions.

| Role | Responsibility in Release |
|---|---|
| Release Manager | Owns end-to-end release coordination and go/no-go decision |
| DevOps Engineer | Executes pipeline, manages deployment and rollback |
| Security Champion | Signs off on security scan results before release |
| QA Lead | Signs off on test coverage and defect status |
| Product Manager | Confirms feature completeness and approves release notes |

Before proceeding to deployment, complete the [Release Readiness Checklist](octoacme-release-readiness-checklist.md).

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- Release Readiness Checklist signed off by all required roles

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
