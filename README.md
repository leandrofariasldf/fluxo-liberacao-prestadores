# Power Automate Flow: Contractor Access Approval 🛂

This repository contains a Power Automate flow designed to manage the submission, approval, and notification process for third-party contractors/service providers entering corporate environments.

## ✅ What it does (Features)

- Collects contractor details via Microsoft Forms (e.g., name, company, ID document, vehicle plate)
- Sends an approval request by email
- Stores/records approved contractors for auditing/history
- Notifies the reception/security gate (or the responsible team)

## 📦 Repository contents

- `Liberar prestadores.zip` — exported flow package ready to import into Power Automate
- `Microsoft.Flow/flows` — flow package contents (useful for manual review / versioning)
- `manifest.json` — package metadata

## 🚀 How to import into Power Automate

1. Open Power Automate (make.powerautomate.com)
2. Go to **My flows** → **Import** → **Package (.zip)**
3. Upload `Liberar prestadores.zip`
4. Choose **Create as new**
5. Reconnect the required connectors with your credentials
6. Click **Import**

## 🔒 Security & privacy

Sensitive data (emails, names, company domain, tenant IDs, etc.) was removed or replaced with generic placeholders to make this repository safe for public sharing.

## 💡 Usage notes / Ideas to extend

- Integrate with Power BI for access reports and dashboards
- Extend it for visitor management or technician scheduling
- Store history in SharePoint or Excel Online (instead of—or in addition to—email)

## 📄 License

This project is open-source under the MIT License.
