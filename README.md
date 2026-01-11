# Contractor Access Approval (Power Automate) 🛂

A Power Automate flow that streamlines **contractor/service provider entry requests**: collect details, route approvals, and notify the right people — with an audit-friendly trail.

## Why this exists

In many companies, contractor access is handled through chaotic back-and-forth emails, missing info, and approvals that get lost in the void.  
This flow turns that into a **repeatable process** with clear ownership and traceability.

## What the flow does

**High-level flow:**
1. A requester submits contractor details (name, company, document/ID, vehicle plate, etc.)
2. The flow sends an approval request to the responsible approver(s)
3. After approval, it records the outcome for history/auditing
4. It notifies reception/security (or the gate/responsible team) so entry can happen smoothly

## Features ✅

- Collects structured data (via Microsoft Forms)
- Automated approval routing via email / Power Automate approvals
- Notification to the operational team (reception/security)
- Designed for auditability and repeatability

## Repository contents 📦

- `contractor-access-approval-power-automate.zip` — exported package ready to import into Power Automate
- `Microsoft.Flow/flows/` — flow package contents (useful for review/versioning)
- `manifest.json` — package metadata

## Import to Power Automate 🚀

1. Open Power Automate (make.powerautomate.com)
2. Go to **My flows** → **Import** → **Package (.zip)**
3. Upload `contractor-access-approval-power-automate.zip`
4. Select **Create as new**
5. Reconnect the required connectors using your credentials
6. Click **Import**

## Security & privacy 🔒

This repository is safe for public sharing:
- Sensitive identifiers (emails, tenant info, org-specific names/domains) were removed or replaced with generic placeholders
- No real personal data is included in the exported package shared here

## License 📄

MIT

This project is open-source under the MIT License.
