# Roofing invoice template

A roofing invoice prices shingles and tear-off by the square, trim and flashing by the linear foot, and lists decking, disposal and the permit separately. The sample below is a full reroof on a 24-square house.

Web page: [https://klmlabs.app/invoice-maker/invoice-templates/roofing/](https://klmlabs.app/invoice-maker/invoice-templates/roofing/)  
Filled-in sample PDF (US Letter): [roofing.pdf](./roofing.pdf)  
Line items as data: [line-items.csv](./line-items.csv)

## The sample invoice

- INV-128, issued Oct 30, 2026, due on receipt
- From Summit Ridge Roofing to Marcus Bell (made-up business and client)

| # | Description | Qty | Unit price | Amount |
|---|---|---|---|---|
| 1 | Tear-off and disposal (squares) | 24 | $89.00 | $2,136.00 |
| 2 | Architectural shingles (squares) | 26 | $310.00 | $8,060.00 |
| 3 | Synthetic underlayment (squares) | 26 | $38.00 | $988.00 |
| 4 | Ice and water shield (lin ft) | 120 | $2.50 | $300.00 |
| 5 | Ridge vent (lin ft) | 42 | $9.50 | $399.00 |
| 6 | Drip edge (lin ft) | 180 | $3.25 | $585.00 |
| 7 | Rotted decking, OSB (sheets) | 6 | $85.00 | $510.00 |
| 8 | City reroof permit | 1 | $225.00 | $225.00 |

Subtotal: **$13,203.00**  
Total: **$13,203.00**

Each amount is quantity × unit price, rounded half up to the cent; tax, where there is any, is worked on the subtotal the same way. These are the Invoice Maker app's own money rules.

## Notes printed on the invoice

> Full reroof at 1904 Cedar Bend Dr, done Oct 30, as quoted on EST-12.  
> Decking photos sent by text Oct 28.  
> 10-year workmanship warranty per the signed contract.  

## Why the lines are built this way

- Roofing is priced by the square (100 sq ft). Tear-off and disposal are billed on the roof's 24 squares; shingles and underlayment on 26, which covers cutting waste.
- Trim and flashing are in linear feet, each on its own line, so a homeowner or adjuster can check the measurements.
- Decking is a count of sheets with photos sent separately: the line customers most often question.
- With Due on receipt, the PDF prints 'Due on receipt' instead of a date.

## Citations (as on the web page)

- A roofing square is the material needed to cover 100 square feet when installed. Source: https://en.wikipedia.org/wiki/Square_(unit) (read 2026-11-06)

## Notes

- The business, client, addresses, phone numbers (555) and emails (.example) are made up. Prices are an example, not a rate guide: use your own prices and your local tax rate.
- The PDF was made by the same invoice template the Invoice Maker app uses.
- License: CC BY 4.0. Credit: "KLM Labs, klmlabs.app".
