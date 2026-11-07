# Landscaping invoice template for lawn care

A lawn care or landscaping invoice puts repeat visits on one line (the visit dates, times the price per visit) and one-off jobs on their own lines, each with its unit. The sample below is one customer's October.

Web page: [https://klmlabs.app/invoice-maker/invoice-templates/landscaping-lawn-care/](https://klmlabs.app/invoice-maker/invoice-templates/landscaping-lawn-care/)  
Filled-in sample PDF (US Letter): [landscaping-lawn-care.pdf](./landscaping-lawn-care.pdf)  
Line items as data: [line-items.csv](./line-items.csv)

## The sample invoice

- INV-561, issued Oct 31, 2026, due Nov 14, 2026 (net 14)
- From Greenway Lawn & Landscape to Priya Natarajan (made-up business and client)

| # | Description | Qty | Unit price | Amount |
|---|---|---|---|---|
| 1 | Weekly mowing, trimming and edging: Oct 3, 10, 17, 24 | 4 | $55.00 | $220.00 |
| 2 | Fall leaf cleanup and haul-away | 1 | $285.00 | $285.00 |
| 3 | Hardwood mulch, installed (cubic yards) | 3 | $68.00 | $204.00 |
| 4 | Shrub pruning, front beds (hours) | 2.5 | $60.00 | $150.00 |

Subtotal: **$859.00**  
Total: **$859.00**

Each amount is quantity × unit price, rounded half up to the cent; tax, where there is any, is worked on the subtotal the same way. These are the Invoice Maker app's own money rules.

## Notes printed on the invoice

> October service. Last mow of the season is planned for Nov 14, weather allowing.  

Payment details: Pay by check to Greenway Lawn & Landscape or Zelle to (614) 555-0181.

## Why the lines are built this way

- Recurring visits are one line with the visit dates in the description and the count as the quantity (4 x $55).
- One-off jobs (cleanup, mulch, pruning) are separate lines with their own units: cubic yards, hours.
- Next month, duplicate this invoice in the app: it copies the client and lines into a new draft with today's date, and you change the dates and counts.

## Notes

- The business, client, addresses, phone numbers (555) and emails (.example) are made up. Prices are an example, not a rate guide: use your own prices and your local tax rate.
- The PDF was made by the same invoice template the Invoice Maker app uses.
- License: CC BY 4.0. Credit: "KLM Labs, klmlabs.app".
