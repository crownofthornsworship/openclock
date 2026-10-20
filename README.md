# OpenClock v0.2

Mobile-friendly white-label time clock and payroll-preparation prototype by Salt & Light Web Studio.

## What works now

- Local demo time punches for fictional employees
- Manager summary and estimated gross wages
- CSV payroll-summary export
- Custom company name, color, and tagline
- Browser-local activity history
- Mobile-friendly GitHub Pages-compatible static website

## Demo limitations

This is not production payroll software. It has no authenticated accounts, server-backed punches, shared workspaces, immutable audit trail, overtime or break compliance, withholding, tax filing, direct deposit, or payroll processing. Local demo data can be changed or lost and must not be used for real payroll or confidential records.

## Development direction

A production release requires secure authentication, tenant isolation, server-generated timestamps, role validation, append-only audit records, transactional punch updates, backups, monitoring, and payroll/legal review.

## Deployment

GitHub Pages serves the repository's `main` branch from `/ (root)`.

Expected URL: https://crownofthornsworship.github.io/openclock/
