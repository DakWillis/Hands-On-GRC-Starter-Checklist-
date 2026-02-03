# Sample Environment Profile — Small Nonprofit (Cloud-first)

## Organization Type
Small nonprofit organization supporting education and community programs.

## User Count
~35 users (staff + part-time contractors/volunteers)

## Environment Model
- [x] Cloud-first
- [ ] Hybrid
- [ ] On-prem heavy

## Core Tools / Systems
- Identity & email: Google Workspace
- Storage: Google Drive / Shared Drives
- Endpoints: Windows laptops + a few Macs
- Collaboration: Google Meet, Google Chat
- Ticketing: Lightweight request intake (form + email)
- Security tooling: Basic endpoint protection (varies), MFA enabled (goal)

## Data Types (high-level)
- [x] PII (student/participant info)
- [x] Financial (donations, budgets, invoices)
- [x] Internal (operations docs)
- [ ] Public (marketing materials)
- [x] Confidential (HR/admin records)

## Key Assumptions
- MFA is available for all accounts but adoption may be inconsistent.
- Shared Drives exist but ownership and access review cadence are not standardized.
- Devices are often used in event environments, increasing loss/theft risk.

## Scope Notes
**In scope**
- Google Workspace accounts and access controls
- Shared Drives and file permissions
- Staff endpoints (laptops)
- Portable storage usage and data movement

**Out of scope**
- Donor CRM deep technical configuration
- Clinical/medical systems (none in this environment)
- Full SOC tooling or SIEM implementation
