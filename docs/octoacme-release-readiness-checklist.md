# OctoAcme — Release Readiness Checklist

Use this checklist before every release to confirm that all required gates have been met. Each item identifies the **owner** responsible for sign-off. The Release Manager is responsible for collecting and tracking all sign-offs.

For deployment steps after release readiness is confirmed, refer to the [Release & Deployment Guide](octoacme-release-and-deployment.md).

---

## 1. Feature Completeness — *Product Manager*

- [ ] All acceptance criteria for in-scope features are met and verified
- [ ] Out-of-scope or deferred items are captured in the backlog with clear notes
- [ ] Release notes drafted and reviewed by Product Manager

## 2. Quality Sign-off — *QA Lead*

- [ ] Test strategy executed: unit, integration, and end-to-end tests passing
- [ ] No open P0/P1 defects (critical/high-severity bugs)
- [ ] Exploratory or manual QA completed for new user-facing features
- [ ] Regression suite passing against the release candidate build
- [ ] QA Lead sign-off recorded (date and name)

## 3. Security Sign-off — *Security Champion*

- [ ] CI security scan results reviewed; no unmitigated critical or high findings
- [ ] Security review completed for new features with data handling or auth changes
- [ ] Known risks documented in the project risk register with agreed mitigations
- [ ] Security Champion sign-off recorded (date and name)

## 4. Infrastructure & Deployment Readiness — *DevOps Engineer*

- [ ] Deployment pipeline green and validated against the release candidate
- [ ] Staging environment matches production configuration
- [ ] Database migrations (if any) tested and rollback procedure documented
- [ ] Monitoring and alerting in place for the new release
- [ ] DevOps Engineer sign-off recorded (date and name)

## 5. Release Coordination — *Release Manager*

- [ ] Deployment window scheduled and communicated to stakeholders
- [ ] Rollback / mitigation plan documented and reviewed
- [ ] Support and on-call teams briefed on changes and potential impact
- [ ] All sign-offs (QA, Security, DevOps, PM) collected
- [ ] Go/no-go decision made and recorded

## 6. Stakeholder Awareness — *Project Manager / Stakeholder Liaison*

- [ ] Relevant stakeholders and domain liaisons notified of release scope
- [ ] Any business-impacting changes confirmed acceptable by Stakeholder / Domain Liaison
- [ ] Post-release success metrics and monitoring period agreed

---

## Sign-off Summary

| Role | Owner | Status | Date |
|---|---|---|---|
| Product Manager | | | |
| QA Lead | | | |
| Security Champion | | | |
| DevOps Engineer | | | |
| Release Manager | | | |
| Project Manager | | | |

> **Release Manager** completes the final go/no-go and archives this checklist with the release record.
