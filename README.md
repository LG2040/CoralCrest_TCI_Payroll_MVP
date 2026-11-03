# CoralCrest TCI Payroll MVP

A single-file payroll prototype for Turks and Caicos employers. Open `index.html` (or the GitHub Pages link) in any modern browser. No server, no install; data stays in the browser and can be backed up from Settings.

## What it does

- **Employees** - hourly or salaried, sector (for minimum wage), NIB and NHIP numbers, work permit flag, allowances, loan deductions, bank details
- **Hours import** - paste the Lathem time clock CSV; columns detected by header name; unknown IDs flagged before saving
- **Pay runs** - gross from hours (overtime 1.5x, public holiday 2x) or salary; NIB and NHIP employee and employer contributions with ceilings and the NHIP minimum scaled to the pay period; flags for minimum wage, ceilings, missing NHIP numbers
- **Payslips** - print or save as PDF, one slip per employee
- **Remittances** - monthly NIB and NHIP schedules with CSV download; bank bulk-payment CSV
- **Xero** - manual journal CSV per run (wages, employer contributions, liabilities, net pay)
- **Settings** - every statutory rate, ceiling and due day is editable; each run stores the rules it used

## Statutory defaults (confirm before live use)

| Item | Default | Source note |
|---|---|---|
| NIB employee / employer | 5.5% / 6.5% | Private sector from 1 Apr 2024 |
| NIB ceiling | $4,000 per month | 2022 Regulations; some guides cite about $6,000 - verify with the Board |
| NHIP employee / employer | 3% / 3% | National Health Insurance Ordinance |
| NHIP ceiling | $7,800 per month ($1,800 per week) | |
| NHIP minimum | $25 per side per month | |
| Overtime / public holiday | 1.5x / 2x | Employment Ordinance, 44-hour week |
| Minimum wage | $8.00 ($9.00 in six sectors) | From 1 Apr 2023 |
| Income tax | None | |

Demo data is fictional. Prototype only; not legal or tax advice.

Copyright CoralCrest Consulting Limited. All rights reserved.
