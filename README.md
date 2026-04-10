# 🧾 Invoice Audit Intelligence Tool

An AI-assisted invoice auditing system built to detect billing anomalies across vendor invoices — surfacing overcharges, GST inflation, and phantom billing at scale.

## 🔍 What It Does

Audited **~21,800 invoice line items** across FY2025 for a D2C wellness company, identifying **₹2.17 crore in recoverable overcharges** across 15 vendors.

**Anomaly types detected:**
- GST rate inflation (vendor-applied rates exceeding contracted rates)
- Unit price overcharges vs. agreed PO rates
- Phantom billing (line items billed with no corresponding delivery)
- Duplicate invoice detection

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML, CSS, JavaScript
- **Visualization:** Chart.js
- **Deployment:** Vercel

## 🚀 Live Demo

[mosaic-invoice-audit-invoice-audit.vercel.app](https://mosaic-invoice-audit-invoice-audit.vercel.app)

## 💡 Why I Built This

Most finance teams manually reconcile invoices in Excel — slow, error-prone, and unscalable. This tool turns a 2-week audit process into a real-time dashboard, giving ops and finance teams instant visibility into vendor billing patterns.

## 📸 Features

- Vendor-wise anomaly breakdown
- Category-level drill-down (GST / price / phantom)
- Recoverable amount tracker
- Exportable audit summary
