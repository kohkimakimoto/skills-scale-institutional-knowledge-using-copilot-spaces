# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability. The Release Manager coordinates this process across teams to ensure quality and timely delivery.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
Coordinated by Release Manager:
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted (with input from Technical Writer)
- Rollback / mitigation plan documented
- Smoke tests prepared and validated by QA

## Deployment Checklist
Managed by Release Manager:
- [ ] Deployment window scheduled and communicated (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (coordinate with Technical Writer for release notes)
- [ ] Monitor post-release metrics and track any issues

For detailed Release Manager responsibilities, see [OctoAcme Roles and Personas](octoacme-roles-and-personas.md).

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
