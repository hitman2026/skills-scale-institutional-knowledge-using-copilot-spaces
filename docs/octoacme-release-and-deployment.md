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
- Release notes drafted (Release Manager with input from Product Owner)
- Rollback / mitigation plan documented (Release Manager)
- Smoke tests prepared (QA team)
- Change request approved if required (Change Control Coordinator)
- Stakeholder communication plan ready (see [Stakeholder Communication Checklist](octoacme-stakeholder-communication-checklist.md))

## Deployment Checklist
- [ ] Deployment window scheduled by Release Manager (if needed)
- [ ] Change request submitted and approved (Change Control Coordinator)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (QA team)
- [ ] Go/no-go decision meeting held (Release Manager facilitates, Product Owner approves)
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications (QA team)
- [ ] Announce release to stakeholders and support (Release Manager and Product Owner)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Release Manager triggers incident response and notifies on-call
  - Change Control Coordinator activates emergency change procedures
  - Rollback to last known-good release if necessary (Release Manager executes)
  - Project Manager and Product Owner informed immediately
  - Triage root cause and capture action items
  - Post-incident review scheduled (include all relevant roles)

For detailed handoff and escalation procedures, see [Responsibility Matrix](octoacme-responsibility-matrix.md).

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
