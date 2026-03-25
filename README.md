cat > README.md << 'EOF'
# Mosaic Wellness — Invoice Audit Intelligence

A browser-based invoice audit system built for the Mosaic Fellowship Finance challenge.

## What it does
Cross-references 21,800 line items across 5,200 invoices against the contracted rate card for all 15 vendors. Runs three audit engines client-side:
- **Price overcharge** — billed amount vs qty × contracted rate
- **GST inflation** — billed GST% vs contracted GST% (self-discovered finding)
- **Phantom billing** — items with no rate card entry

## Key findings
- ₹2,17,82,440 total recoverable
- ₹30,87,637 price overcharges · 719 line items
- ₹1,86,94,802 GST inflation · 471 lines · all 4 marketing vendors applied 28% vs contracted 18%
- ₹9,88,341 phantom billing · 389 items
- 15/15 vendors flagged

## Live demo
https://mosaic-invoice-audit-invoice-audit.vercel.app/

## How to run
Open `artifacts/invoice-audit/index.html` in any browser — fetches live from the Mosaic API.
EOF

git add README.md
git commit -m "Add README with findings and demo link"
git push
