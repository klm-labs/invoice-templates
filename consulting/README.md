# Consulting invoice template

A consulting invoice lists your hours at an hourly rate (or a fixed fee), any expenses you pass on at cost, and when and how the client should pay. The sample below is filled in line by line, so you can copy how it's written.

Web page: [https://klmlabs.app/invoice-maker/invoice-templates/consulting/](https://klmlabs.app/invoice-maker/invoice-templates/consulting/)  
Filled-in sample PDF (US Letter): [consulting.pdf](./consulting.pdf)  
Line items as data: [line-items.csv](./line-items.csv)

## The sample invoice

- INV-1042, issued Nov 2, 2026, due Dec 2, 2026 (net 30)
- From Ridgeway Operations Consulting to Fernhill Bakery Co. (made-up business and client)

| # | Description | Qty | Unit price | Amount |
|---|---|---|---|---|
| 1 | Kitchen workflow review, Oct 6-17 (hours) | 12.5 | $150.00 | $1,875.00 |
| 2 | Staff scheduling model and handover call (hours) | 6.25 | $150.00 | $937.50 |
| 3 | On-site workshop, Oct 22, half day (fixed fee) | 1 | $900.00 | $900.00 |
| 4 | Mileage to client site, 84 miles | 84 | $0.70 | $58.80 |

Subtotal: **$3,771.30**  
Total: **$3,771.30**

Each amount is quantity × unit price, rounded half up to the cent; tax, where there is any, is worked on the subtotal the same way. These are the Invoice Maker app's own money rules.

## Notes printed on the invoice

> Hours are billed in quarter hours at $150 an hour; time log attached.  
> December retainer ($1,500 for up to 10 hours) is billed separately on Dec 1.  

Payment details: Pay by ACH (details on file) or by check to Ridgeway Operations Consulting. Terms: net 30.

## Why the lines are built this way

- Hours go in the quantity box with decimals: 12.5 hours at $150 is $1,875.00. The app keeps up to 3 decimals, so quarter hours (6.25) print exactly.
- A fixed-fee item is quantity 1 at the agreed price, so the client sees what was hourly and what was fixed.
- Expenses passed through at cost get their own line, with the unit in the description (miles).
- The retainer lives in the notes: the app has no deposit or credit lines, so a retainer is billed on its own invoice.

## Notes

- The business, client, addresses, phone numbers (555) and emails (.example) are made up. Prices are an example, not a rate guide: use your own prices and your local tax rate.
- The PDF was made by the same invoice template the Invoice Maker app uses.
- License: CC BY 4.0. Credit: "KLM Labs, klmlabs.app".
