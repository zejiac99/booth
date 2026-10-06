In developed markets, the average annualized stock market return is often in the 7 – 10% range, so a company with a Levered Beta of 1.0 will have a Cost of Equity in that range.

For the Cost of Debt to be higher, the Pre-Tax Cost would have to be ~9 – 13% at a 25% tax rate. More speculative companies might pay interest rates in that range, but larger/mature companies tend to pay less than that.

### 10. How do you determine the Cost of Debt and Cost of Preferred Stock in the WACC calculation, and what do they mean?

These Costs represent what the company would pay if it issued additional Debt or Preferred Stock.

To an outside investor, these Costs represent their expected annualized returns if they held the Debt or Preferred Stock through their maturities.

You can estimate the Cost of Debt by calculating the Yield to Maturity (YTM), which reflects the coupon rates on the company's bonds and their market values (e.g., a bond with a coupon rate of 5% that's trading at a discount to par value will have a YTM higher than 5%).

If you can't find this information, you could also use a simple weighted average interest rate for the issuances or take the Risk-Free Rate and add a default spread based on the company's expected credit rating.

The Cost of Preferred Stock is similar, but Preferred Dividends are not tax-deductible, so you do not multiply by the (1 – Tax Rate) term in the WACC calculation.

## Merger Models – Concepts

It's important to understand the fundamentals of M&A deals and merger models, but they are less important than the accounting and valuation topics.

They are more advanced but also less relevant in certain groups (e.g., ECM, DCM, etc.). Unlike accounting and valuation, M&A modeling applies mostly to investment banking and other deal-based roles and is less important for "public markets" roles (equity research, asset management, hedge funds, etc.).

You could certainly get quantitative questions related to merger models, such as quick accretion/dilution calculations, but conceptual questions are more likely in entry-level interviews.

|  | | EPS Accretion / Dilution Analysis | Units: | 0.0% | 10.0% | 20.0% | 30.0% | 40.0% |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  | | Company A Share Price: | $ as Stated | $ 7.00 | $ 7.00 | $ 7.00 | $ 7.00 | $ 7.00 |  |
|  | | Company B Offer Price per Share: | $ as Stated | 5.00 | 5.50 | 6.00 | 6.50 | 7.00 |  |
|  | | **Company B - Purchase Equity Value:** | **$ M** | **500.0** | **550.0** | **600.0** | **650.0** | **700.0** |  |
|  | | Cash Used: | $ M | 166.7 | 183.3 | 200.0 | 216.7 | 233.3 |  |
|  | | Debt Issued: | $ M | 166.7 | 183.3 | 200.0 | 216.7 | 233.3 |  |
|  | | Company A Shares Issued: | M Shares | 23.810 | 26.190 | 28.571 | 30.952 | 33.333 |  |
|  | | Weighted Cost of Acquisition: | % | 5.6% | 5.6% | 5.6% | 5.6% | 5.6% |  |
|  | | After-Tax Yield of Company B: | % | 6.0% | 5.5% | 5.0% | 4.6% | 4.3% |  |
|  | | **The Deal is Predicted to Be:** | **Text** | **Accretive** | **Dilutive** | **Dilutive** | **Dilutive** | **Dilutive** |  |

- Interview Guide – M&A Deals and Merger Models | Quiz Questions
- Core Financial Modeling – M&A and Merger Model Module

### 1. Walk me through a merger model (accretion/dilution analysis).

In a merger model, you start by projecting the financial statements of the Buyer and Seller. Then, you estimate the Purchase Price and the mix of Cash, Debt, and Stock used to fund the deal. You create a Sources & Uses schedule and Purchase Price Allocation schedule to estimate the after-effects of the deal on the financial statements.

Then, you combine the Balance Sheets of the Buyer and Seller, reflecting the Cash, Debt, and Stock used, new Goodwill created, and any write-ups and write-downs. You then combine the Income Statements, reflecting the Foregone Interest on Cash, Interest Paid on New Debt, and Synergies.

The Combined Net Income equals the Combined Pre-Tax Income times (1 – Buyer's Tax Rate), and the Combined EPS equals the Combined Net Income divided by (Buyer's Existing Share Count + New Shares Issued in the Deal).

The EPS accretion/dilution equals the percentage difference between this Combined EPS and the Buyer's standalone EPS.

### 2. Why might an M&A deal be accretive or dilutive?

A deal is accretive if the extra Pre-Tax Income from a Seller exceeds the cost of the acquisition in the form of the Foregone Interest on Cash, Interest Paid on New Debt, and New Shares Issued.

For example, if the Seller contributes $100 in Pre-Tax Income, but the deal costs the Buyer only $70 in additional Interest Expense, and the Buyer doesn't issue any new shares, the deal will be accretive because the Buyer's Earnings per Share (EPS) will increase.

A deal will be dilutive if the opposite happens. For example, if the Seller contributes $100 in Pre-Tax Income, but the deal costs the Buyer $130 in additional Interest Expense, and its share count remains the same, its EPS will decrease.

### 3. How can you tell whether an M&A deal will be accretive or dilutive?

You compare the Weighted Cost of Acquisition to the Seller's Yield at the Purchase Price.

- **Cost of Cash** = Foregone Interest Rate on Cash * (1 – Buyer's Tax Rate)
- **Cost of Debt** = Interest Rate on New Debt * (1 – Buyer's Tax Rate)
- **Cost of Stock** = Reciprocal of the Buyer's P / E multiple, i.e., Net Income / Equity Value.
- **Seller's Yield** = Reciprocal of the Seller's P / E multiple, calculated using the Purchase Equity Value.

**Weighted Cost of Acquisition** = % Cash Used * Cost of Cash + % Debt Used * Cost of Debt + % Stock Used * Cost of Stock.

If the Weighted Cost is **less than** the Seller's Yield, the deal will be **accretive**; if the Weighted Cost is **greater than** the Seller's Yield, the deal will be **dilutive**.

### 4. That sounds complicated. Are there any shortcuts for guesstimating whether an M&A deal will be accretive or dilutive?

If it is a **100% Stock deal**, you can compare the Buyer's P / E multiple to the Seller's P / E multiple *at* the purchase price. If the Buyer's multiple is higher, the deal will be accretive.

This works because the reciprocals of the P / E multiples in a 100% Stock deal are the Weighted Cost of Acquisition and the Seller's Yield.

For example, let's say the Buyer's P / E multiple is 10x, and the Weighted Cost of Acquisition is 10%.

If the Seller's Current Equity Value is $1000, the Buyer pays a 20% premium, and the Seller's Net Income is $200, its P / E multiple at the purchase price is $1200 / $200 = 6x.

Therefore, a 100% Stock version of this deal is accretive because the Seller's Yield is 1 / 6 = 16.7%, which is higher than the Weighted Cost of Acquisition.

### 5. How do you determine the Purchase Price in an M&A deal?

If the Seller is public, you assume a **premium** to the Seller's current share price based on the average premiums for similar deals in the market (usually between 10% and 30%). You can also use the DCF, Public Comps, and other valuation methodologies to cross-check this figure.

The Purchase Price for private Sellers is based on the standard valuation methodologies, and you usually link it to a multiple of EBITDA, EBIT, or Revenue since private companies don't have easy-to-determine share prices.

If the Buyer expects to realize significant Synergies, it is often willing to pay a higher premium for the Seller because the Present Value of the Synergies might exceed this premium.

### 6. What is the "true price" in an M&A deal: The Purchase Equity Value or Purchase Enterprise Value? Why?

The "true price" is the Purchase Enterprise Value (or something close to it) because that represents what the Buyer pays *all* the Seller's investors for its core assets. However, the Purchase Enterprise Value is *not* necessarily what the Buyer pays in "upfront capital."

Also, the Purchase Equity Value often drives the Cash, Debt, and Stock used to fund a deal. The Purchase Equity Value is also what the selling shareholders receive in the deal.

Therefore, even though the Purchase Enterprise Value is the true price, both metrics are important in M&A analysis.

### 7. How does an Acquirer determine the mix of Cash, Debt, and Stock to use in a deal?

Since Cash is the cheapest for most Acquirers, they'll use all they can before moving to the other funding sources. So, you might assume that the Cash Available equals the Acquirer's current Cash balance minus its Minimum Cash balance, also factoring in the Target's Cash and Minimum Cash when applicable.

After that, Debt tends to be the next cheapest option. An Acquirer might be able to raise Debt to the level where its Debt / EBITDA remains in-line with peer companies'.

So, if it's levered at 2x EBITDA now, and similar companies have 5x Debt / EBITDA, it might be able to raise an additional 3x EBITDA worth of Debt. Again, you may also factor in the Target's Debt and EBITDA if they are significant.

Finally, there's no strict limit on the amount of Stock an Acquirer might issue, but few companies would issue enough shares to lose control of the company, and some Acquirers will issue Stock only up to the point at which the deal turns dilutive.

### 8. Are there cases where EPS accretion/dilution is NOT important? What other analyses could you look at to assess M&A deals?

Yes, there are many cases where EPS accretion/dilution is less important.

For example, if the Buyer is private or has negative EPS as a standalone entity, it won't care whether the deal is accretive or dilutive.

It also makes little difference if the Buyer is far bigger than the Seller (e.g., 10x – 100x its size).

Besides EPS accretion/dilution, you can also analyze the deal's qualitative merits, compare the IRR to the Discount Rate, and value the Seller plus the Synergies and compare that to the Equity Purchase Price.

You can also create a Contribution Analysis to determine how much the Buyer and Seller "contribute" to each financial metric and then compare the contribution percentages to their respective ownership percentages, assuming it's a 100% Stock deal.

Value Creation Analysis to determine how the Buyer's share price will change after the deal closes may also be useful, especially if the Buyer + Seller together will resemble a larger, more valuable public company.

### 9. How do the assumptions for a cash-free, debt-free deal for a private Seller differ from those of a standard M&A deal for a public Seller?

In a cash-free, debt-free deal, the Seller's existing Cash and Debt balances go to $0 when the deal closes and are immediately replaced with new Cash and Debt balances.

The Cash is brought up to the Seller's Minimum Cash, and the new Debt balance is usually the same as the old one because it is simply replaced with a new issuance.

If Debt > Cash, the Seller uses its Cash balance to repay as much Debt as it can, and the remaining Debt is deducted from the proceeds to the selling shareholders (i.e., they earn less because they must repay some of the Debt).

If Cash > Debt, the Seller repays its entire Debt balance using its Cash, and it distributes the remaining Cash to shareholders as the deal closes, which reduces its Equity Value.

In these types of deals, the purchase price is based on a multiple such as TEV / EBITDA or TEV / Revenue rather than a share-price premium because the Seller is private.

Also, the Uses side of the Sources & Uses schedule is based on the Purchase Enterprise Value, the Seller's Minimum Cash, and the Transaction/Financing Fees.

The Sources side is standard and includes the usual Cash, Debt, and Stock line items.

### 10. What's the purpose of a Purchase Price Allocation schedule in a merger model?

The main purpose is to estimate the Goodwill created in a deal.

Goodwill exists because the Purchase Equity Value in deals almost always exceeds the Seller's Common Shareholders' Equity (CSE).

When this happens, the Combined Balance Sheet will go out of balance because the Seller's CSE is written down to $0, but the total amount of Cash, Debt, and Stock used in the deal is greater than the CSE that was written down. Goodwill exists to "plug the gap" and ensure the Balance Sheet balances.

So, you estimate the new Goodwill with this schedule, factor in write-ups of Assets such as PP&E and Intangibles, and include other acquisition effects such as the creation of a new Deferred Tax Liability and changes to the existing Deferred Tax items.

### 11. Why do Deferred Tax Liabilities get created in many M&A deals?

A Deferred Tax Liability, or DTL, represents the expectation that Cash Taxes will exceed Book Taxes in the future.

DTLs get created because the Depreciation & Amortization on Asset Write-Ups is not deductible for cash-tax purposes in a Stock Purchase (i.e., a standard M&A deal where the Buyer purchases all the Seller's common shares and acquires *everything* the Seller has).

As a result, the Buyer will pay more in Cash Taxes than Book Taxes until the Write-Ups are fully depreciated/amortized. Each time the Buyer pays more in Cash Taxes than Book Taxes, the DTL decreases until it eventually reaches 0.

### 12. Give me an example of how you might estimate the Revenue and Expense Synergies in an M&A deal.

With Revenue Synergies, you might assume that the Seller can sell its products to some of the Buyer's customer base.

So, if the Buyer has 100,000 customers, 1,000 of them might buy widgets from the Seller. Each widget costs $10.00, which is $10,000 in extra Revenue.

There will also be COGS and Operating Expenses associated with these extra sales, so you must factor those in. For example, if each widget costs $5.00, the Combined Company will earn only $5,000 in extra Pre-Tax Income.

With Expense Synergies, you might assume that the Combined Company can close several offices or lay off redundant employees, particularly in administrative functions such as IT, accounting, and HR.

For example, if the Combined Company has 10 offices, management might believe only 8 will be required after the merger.

If each office costs $100,000 per year, there will be 2 * $100,000 = $200,000 in Expense Synergies, boosting the Combined Pre-Tax Income by $200,000.

### 13. Why do many merger models tend to overstate the impact of Synergies?

First, many merger models do **not** include the costs associated with Revenue Synergies. Even if the Buyer or Seller can sell more products after the deal closes, those extra units **cost something to produce and deliver**, so you must include the extra COGS and OpEx.

Second, realizing Synergies **takes time**. Even if a company expects $10 million in "long-term synergies," it won't realize all of them in Year 1; it might take several years, and the percentage realized will increase gradually over time.
