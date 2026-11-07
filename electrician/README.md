# Electrician invoice template

An electrician's invoice shows labor as hours times your rate, materials as their own lines, and any permit or inspection fee passed through. The sample below is a 100A to 200A panel upgrade, billed from the approved estimate.

Web page: [https://klmlabs.app/invoice-maker/invoice-templates/electrician/](https://klmlabs.app/invoice-maker/invoice-templates/electrician/)  
Filled-in sample PDF (US Letter): [electrician.pdf](./electrician.pdf)  
Line items as data: [line-items.csv](./line-items.csv)

## The sample invoice

- INV-904, issued Oct 23, 2026, due Oct 30, 2026 (net 7)
- From Brightline Electric LLC to Tom and Rachel Weiss (made-up business and client)

| # | Description | Qty | Unit price | Amount |
|---|---|---|---|---|
| 1 | Panel upgrade labor (hours) | 10 | $95.00 | $950.00 |
| 2 | 200A main breaker load center | 1 | $425.00 | $425.00 |
| 3 | Breakers, cable and fittings | 1 | $186.40 | $186.40 |
| 4 | Village permit and inspection | 1 | $150.00 | $150.00 |
| 5 | Remove and dispose of old panel | 1 | $40.00 | $40.00 |

Subtotal: **$1,751.40**  
Total: **$1,751.40**

Each amount is quantity × unit price, rounded half up to the cent; tax, where there is any, is worked on the subtotal the same way. These are the Invoice Maker app's own money rules.

## Notes printed on the invoice

> As quoted on estimate EST-31 (100A to 200A panel upgrade), approved Oct 14. Inspection passed Oct 22.  
> License no. EC-000000 (sample).  

Payment details: Pay by check or card at the office within 7 days.

## Why the lines are built this way

- Labor is hours x rate; the panel and the small parts are separate lines so the customer can see materials apart from labor.
- The permit fee is passed through as its own line, which is what customers expect to see when the city charges for an inspection.
- The notes tie the invoice back to the approved estimate. In the app, EST-31 became this invoice with one tap, carrying the same lines.
- If your license number has to appear on paperwork where you work, the notes field is the place for it.

## Notes

- The business, client, addresses, phone numbers (555) and emails (.example) are made up. Prices are an example, not a rate guide: use your own prices and your local tax rate.
- The PDF was made by the same invoice template the Invoice Maker app uses.
- License: CC BY 4.0. Credit: "KLM Labs, klmlabs.app".
