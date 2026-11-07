# Invoice templates by trade

Seven filled-in sample invoices for trades and freelancers (roofing, electrician, handyman, landscaping and lawn care, catering, consulting, photography), as PDFs, plus each sample's line items as CSV and Markdown.

This is the free material behind the [invoice template pages on klmlabs.app](https://klmlabs.app/invoice-maker/invoice-templates/). It is made by KLM Labs, a small studio that makes [Invoice Maker](https://klmlabs.app/invoice-maker/), an iPhone and iPad app for invoices and estimates. The PDFs were made with the same invoice template the app uses, and the line items and totals here come from the site's sample files and the app's own money code, checked against the live pages.

For payment terms and wording (what net 30 means, how to print the due date), see the [net 30 guide](https://klmlabs.app/invoice-maker/invoicing/net-30-payment-terms/).

## Samples

Each folder has a README with the invoice's lines, totals and printed notes, and why the lines are built that way for that trade.

| Trade | Line items | Terms | Sample total | Files | Web page |
|---|---|---|---|---|---|
| [Roofing](./roofing/) | 8 | Due on receipt | $13,203.00 | [PDF](./roofing/roofing.pdf), [CSV](./roofing/line-items.csv) | [klmlabs.app/invoice-maker/invoice-templates/roofing/](https://klmlabs.app/invoice-maker/invoice-templates/roofing/) |
| [Electrician](./electrician/) | 5 | Net 7 | $1,751.40 | [PDF](./electrician/electrician.pdf), [CSV](./electrician/line-items.csv) | [klmlabs.app/invoice-maker/invoice-templates/electrician/](https://klmlabs.app/invoice-maker/invoice-templates/electrician/) |
| [Handyman](./handyman/) | 5 | Net 7 | $402.35 | [PDF](./handyman/handyman.pdf), [CSV](./handyman/line-items.csv) | [klmlabs.app/invoice-maker/invoice-templates/handyman/](https://klmlabs.app/invoice-maker/invoice-templates/handyman/) |
| [Landscaping](./landscaping-lawn-care/) | 4 | Net 14 | $859.00 | [PDF](./landscaping-lawn-care/landscaping-lawn-care.pdf), [CSV](./landscaping-lawn-care/line-items.csv) | [klmlabs.app/invoice-maker/invoice-templates/landscaping-lawn-care/](https://klmlabs.app/invoice-maker/invoice-templates/landscaping-lawn-care/) |
| [Catering](./catering/) | 5 | Net 14 | $3,861.82 | [PDF](./catering/catering.pdf), [CSV](./catering/line-items.csv) | [klmlabs.app/invoice-maker/invoice-templates/catering/](https://klmlabs.app/invoice-maker/invoice-templates/catering/) |
| [Consulting](./consulting/) | 4 | Net 30 | $3,771.30 | [PDF](./consulting/consulting.pdf), [CSV](./consulting/line-items.csv) | [klmlabs.app/invoice-maker/invoice-templates/consulting/](https://klmlabs.app/invoice-maker/invoice-templates/consulting/) |
| [Photography](./photography/) | 5 | Net 14 | $1,756.60 | [PDF](./photography/photography.pdf), [CSV](./photography/line-items.csv) | [klmlabs.app/invoice-maker/invoice-templates/photography/](https://klmlabs.app/invoice-maker/invoice-templates/photography/) |

## Files

- `<trade>/<trade>.pdf`: the filled-in sample invoice, US Letter, the same file served on klmlabs.app.
- `<trade>/line-items.csv`: the line items, UTF-8, columns `line, description, quantity, unit_price_usd, amount_usd`. Amount = quantity × unit price, rounded half up to the cent.
- `<trade>/README.md`: the same lines in Markdown, with subtotal, tax and total, the notes printed on the invoice and why each line is there.

## Things to know

- The businesses, clients, addresses, 555 phone numbers and `.example` emails are made up.
- Prices and tax rates are examples, not a rate guide. Use your own prices, your local tax rate and the terms your customer agreed to.
- These are samples to copy the structure from. To fill in your own invoice on a phone, there is [Invoice Maker](https://klmlabs.app/invoice-maker/); any spreadsheet or word processor works too.

## License and credit

The PDFs, data and text are licensed under [CC BY 4.0](./LICENSE). You may copy, change and share them, also commercially. Please credit: **"KLM Labs, klmlabs.app"**, ideally with a link to the trade's page.

## Corrections

Open an issue, or write to support@klmlabs.app.
