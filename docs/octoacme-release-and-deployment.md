# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted (by Technical Writer or Release Manager)
- Rollback / mitigation plan documented
- Smoke tests prepared
- Stakeholder communication prepared (see [Communication Plan Template](octoacme-communication-plan-template.md))
- User-facing documentation updated (by Technical Writer, if applicable)

## Deployment Checklist
- [ ] Deployment window scheduled (coordinated by Release Manager)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (per Communication Plan)
- [ ] Update user documentation (Technical Writer)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (Release Manager coordinates)
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items in [Decision Log](octoacme-decision-log-template.md)
  - Communicate status per incident communication process (see [Communication Plan](octoacme-communication-plan-template.md))

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
