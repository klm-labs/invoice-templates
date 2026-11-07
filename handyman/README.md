# Handyman invoice template

A handyman invoice puts each job from the visit on its own line with its own time, adds a trip charge and the materials, and ties it back to the estimate. The sample below is three small jobs on one afternoon.

Web page: [https://klmlabs.app/invoice-maker/invoice-templates/handyman/](https://klmlabs.app/invoice-maker/invoice-templates/handyman/)  
Filled-in sample PDF (US Letter): [handyman.pdf](./handyman.pdf)  
Line items as data: [line-items.csv](./line-items.csv)

## The sample invoice

- INV-77, issued Nov 4, 2026, due Nov 11, 2026 (net 7)
- From Okafor Home Repair to Linda Brooks (made-up business and client)

| # | Description | Qty | Unit price | Amount |
|---|---|---|---|---|
| 1 | Trip charge | 1 | $45.00 | $45.00 |
| 2 | Replace kitchen faucet (hours) | 1.5 | $75.00 | $112.50 |
| 3 | Drywall patch and paint (hours) | 2 | $75.00 | $150.00 |
| 4 | Re-hang sticking door (hours) | 0.75 | $75.00 | $56.25 |
| 5 | Materials: compound, paint, shims | 1 | $38.60 | $38.60 |

Subtotal: **$402.35**  
Total: **$402.35**

Each amount is quantity × unit price, rounded half up to the cent; tax, where there is any, is worked on the subtotal the same way. These are the Invoice Maker app's own money rules.

## Notes printed on the invoice

> Three jobs, one visit on Nov 4, as on estimate EST-58.  
> Faucet supplied by the client: labor only.  

Payment details: Pay by Zelle to (404) 555-0158 or by check within 7 days.

## Why the lines are built this way

- One visit, several small jobs: each job is its own line with its own hours, so the customer sees where the time went.
- The trip charge is a single flat line at the top.
- Materials are one line with a short list; keep receipts in case the customer asks.
- When the customer supplies a part, say so in the notes so the low price on that line isn't a surprise.

## Notes

- The business, client, addresses, phone numbers (555) and emails (.example) are made up. Prices are an example, not a rate guide: use your own prices and your local tax rate.
- The PDF was made by the same invoice template the Invoice Maker app uses.
- License: CC BY 4.0. Credit: "KLM Labs, klmlabs.app".
