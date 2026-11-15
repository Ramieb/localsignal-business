# Offer Notes (working name)

The original LocalSignal agency concept required ongoing client work, so it did not meet the owner’s stated goal of having no employees and doing no routine fulfillment. This project now contains a draft site for a narrower, one-time digital product: an Excel workbook for comparing written car-price and loan offers.

The working name has not been cleared for trademark or domain use. The GitHub repository name remains `localsignal-business`; the current site no longer advertises local marketing services.

## Product draft

Planned price: **$8.99 one time**, subject to owner review. Checkout is disabled.

The downloadable `.xlsx` contains four worksheets:

1. **Compare Quotes** — up to three written vehicle offers. It totals the entered vehicle price, discount, separately listed dealer fees, quoted tax/title/government charges, and optional add-ons the buyer accepts.
2. **Compare Financing** — up to three disclosed loan offers. It lines up amount financed, APR, term, monthly payment, and total payments. If the lender’s total-of-payments figure is omitted, it estimates payment × number of payments, assuming equal payments.
3. **Before You Sign** — prompts for a buyer to check the agreed price, add-ons, trade-in, loan terms, and paperwork.
4. **Start Here** — instructions, fictional sample figures, privacy and calculation limits, and links to free CFPB and FTC consumer guidance.

It does not search for market prices, estimate local taxes, judge a vehicle’s condition, compare insurance, determine anyone’s legal rights, or recommend a car or loan. It is a planning aid, not legal, tax, financial, lending, mechanical, or valuation advice. State rules and lender contracts vary.

## Hosting and customer delivery

- The website is a static HTML/CSS/JavaScript site hosted on GitHub Pages. A GitHub Actions workflow deploys the repository on pushes to `main`.
- The product workbook is kept out of the public repository. The current website has no payment link, cart, email capture, analytics package, or customer-data form.
- A digital marketplace could collect payment and deliver the workbook automatically. Etsy is one possible channel because it offers marketplace discovery and instant delivery for eligible digital downloads. The seller must create and verify the shop. Etsy’s published fees include a $0.20 listing fee and a 6.5% transaction fee, plus payment-processing and any applicable setup, advertising, or other fees. A listing expires after four months and may incur a renewal fee.
- Etsy’s seller onboarding requires the account owner’s legal, tax, bank, and identity details, including government-ID verification. Keep those private and enter them directly with the marketplace. Do not send passwords, verification codes, ID, or bank details by email or chat.

## Why this is not fully unattended

Automated file delivery can remove per-order fulfillment and a one-person business needs no employees. It cannot guarantee customers or profit, remove account verification, settle location-dependent registration and tax questions, prevent a platform from changing its fees or rules, or remove the owner’s responsibility for business records, customer issues, and account health. The launch would still require owner setup and occasional review. No promise of self-sustaining revenue is being made.

## Before checkout can open

- The owner reviews the exact workbook, sample values, planned $8.99 price, supported software, and product limitations.
- The owner chooses and checks a final product/business name and decides where to sell it.
- The owner completes storefront verification and payout setup directly with the chosen platform.
- The owner checks current federal, state, county, and city obligations for their location, and confirms business and tax records with the appropriate official sources or adviser. Requirements vary by location and structure.
- The owner confirms the temporary contact address is monitored: `ramiebash@gmail.com`.
- The seller uploads the final file, sets clear terms/refund support, and completes a real end-to-end checkout and download test before enabling purchase on the site.

## Preview and publishing

Open `index.html` locally or use the GitHub Pages site. Pushes to `main` deploy through `.github/workflows/pages.yml` when GitHub Pages is enabled for the repository.

The current public site is a product preview. It says checkout is closed and does not accept payments.
