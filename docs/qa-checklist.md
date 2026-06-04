# QA Checklist — Release Readiness

Use this checklist to verify release readiness for each release candidate.

## Pre-release verification
- [ ] Acceptance criteria for user stories completed and signed off
- [ ] All critical and high defects resolved (or mitigation accepted)
- [ ] Regression test suite executed (automated/manual) and pass rate >= defined threshold
- [ ] Performance smoke tests executed (if applicable)
- [ ] Security scans run and no critical findings
- [ ] Environment and configuration validated
- [ ] Data migration scripts tested (if applicable)

## Release gating
- [ ] QA Lead recommends release (Yes/No) — evidence attached
- [ ] Test summary report attached (link)
- [ ] Known issues documented and communicated

## Post-release verification
- [ ] Smoke tests passed in production
- [ ] Monitoring and alerts configured and validated
- [ ] Stakeholder sign-off received (if applicable)

(End of checklist)
