# Catering invoice template

A catering invoice prices food per guest, times the final headcount, then lists staff time, rentals and delivery as separate lines. The sample below shows an 85-guest staff lunch with the math visible on every line.

Web page: [https://klmlabs.app/invoice-maker/invoice-templates/catering/](https://klmlabs.app/invoice-maker/invoice-templates/catering/)  
Filled-in sample PDF (US Letter): [catering.pdf](./catering.pdf)  
Line items as data: [line-items.csv](./line-items.csv)

## The sample invoice

- INV-377, issued Oct 31, 2026, due Nov 14, 2026 (net 14)
- From Saffron & Sage Catering to Lakeline Credit Union (made-up business and client)

| # | Description | Qty | Unit price | Amount |
|---|---|---|---|---|
| 1 | Staff lunch Oct 30, buffet menu B, per guest | 85 | $24.50 | $2,082.50 |
| 2 | Dessert table, per guest | 85 | $6.00 | $510.00 |
| 3 | Serving staff, 4 staff x 5 hours (staff hours) | 20 | $35.00 | $700.00 |
| 4 | Linens and chafing dish rental | 1 | $180.00 | $180.00 |
| 5 | Delivery, setup and breakdown | 1 | $95.00 | $95.00 |

Subtotal: **$3,567.50**  
Sales tax (8.25%): **$294.32**  
Total: **$3,861.82**

Each amount is quantity × unit price, rounded half up to the cent; tax, where there is any, is worked on the subtotal the same way. These are the Invoice Maker app's own money rules.

## Notes printed on the invoice

> Final headcount of 85 confirmed by email on Oct 28. Guests added after the final count are billed at the per-guest price.  
> 12 vegetarian and 3 gluten-free plates were included in the count.  
> Sample tax rate: use the rate that applies where you cater.  

## Why the lines are built this way

- Food is priced per guest with the final headcount as the quantity, so the math is visible: 85 x $24.50.
- Staff time is written as total staff hours (4 staff x 5 hours = 20) at one hourly rate.
- Rentals and delivery are flat lines, so the client can see they are not food.
- The app applies one tax rate to the whole invoice. The 8.25% here is only an example; use your own local rate.

## Notes

- The business, client, addresses, phone numbers (555) and emails (.example) are made up. Prices are an example, not a rate guide: use your own prices and your local tax rate.
- The PDF was made by the same invoice template the Invoice Maker app uses.
- License: CC BY 4.0. Credit: "KLM Labs, klmlabs.app".
