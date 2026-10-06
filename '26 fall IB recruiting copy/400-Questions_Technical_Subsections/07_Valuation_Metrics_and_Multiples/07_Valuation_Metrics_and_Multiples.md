# Valuation Metrics and Multiples

| Valuation Multiple Calculations: |         |
| --- | --- |
| Equity Value: | $49,592 |
| Enterprise Value Excluding Op. Leases: | 60,477 |
| (+) Operating Lease Liabilities: | 2,475 |
| Enterprise Value Including Op. Leases: | 62,952 |
| Revenue Multiple: | 0.8x |
| EBIT Multiple: | 13.0x |
| EBITDA Multiple: | 8.3x |
| EBITDAR Multiple: | 8.4x |
| Net Income Multiple (P / E): | 15.2x |
| FCF Multiple: | 12.2x |
| UFCF Multiple: | 14.2x |
| LFCF Multiple: | 13.9x |

Questions about valuation multiples may seem easy at first glance, but they can be surprisingly tricky if you don't understand the fundamental concepts.

For example, do you understand how a valuation multiple is shorthand for a cash flow-based valuation and a way to compare different companies?

Do you understand the trade-offs of different metrics and multiples? What about the exceptions and special cases, such as differences under U.S. GAAP vs. IFRS?

This section covers these concepts:

### 1. What IS a valuation multiple? Explain the theory and give a real-life analogy.

A valuation multiple is shorthand for a company's value based on its Cash Flow, Cash Flow Growth Rate, and Discount Rate. You could value a company with this formula:

Company Value = Cash Flow / (Discount Rate – Cash Flow Growth Rate), where Cash Flow Growth Rate < Discount Rate

Valuation multiples let you use a number like "10x" to express this in a condensed way.

You can also think of valuation multiples as "per-square-foot" or "per-square-meter" values when buying a house: They help you compare houses or companies of different sizes and see how expensive or cheap they are relative to similar houses or companies.

### 2. You're valuing a mid-sized manufacturing company. This company's TEV / EBITDA multiple is 15x, but the median TEV / EBITDA for the comparable companies is 10x. What's the most likely explanation?

The most likely explanation is that the market expects this company's cash flows to grow faster than comparable companies. For example, other companies might be expected to grow at 5%, but this company might be expected to grow at 15%.

The Discount Rate is unlikely to differ significantly because these companies are in a similar size range in the same industry, which means the risk and potential returns should be similar.

"Current events" could also affect the multiples, but it's hard to say what they might be without additional information.

### 3. Walk me through how you calculate EBIT and EBITDA for a public company.

With EBIT, you start with the company's Operating Income on its Income Statement and then add back any non-recurring charges that have reduced Operating Income.

With EBITDA, you do the same thing and then add Depreciation & Amortization from the company's Cash Flow Statement to get the all-inclusive number (since D&A on the Income Statement may be embedded in other line items there).

### 4. How do you decide whether to use Equity Value or Enterprise Value in valuation multiples?

If the financial metric in the denominator of the valuation multiple deducts Net Interest Expense, it pairs with Equity Value because the Debt Investors can no longer be "paid" after earning their interest; only Equity Investors can earn something now.

If the metric does not deduct Net Interest Expense, it pairs with Enterprise Value. This rule applies to financial metrics (EBIT, EBITDA, etc.) and non-financial ones (Unique Users, Subscribers, etc.).

### 5. A company has $100 in Revenue, a 15% EBIT margin, and D&A that is 5% of its Revenue.

The company's Equity Value is $100, and it has $20 of Cash, $40 of Debt, and $30 in Lease Liabilities. What is its TEV / EBITDA multiple?

$$\text{EBITDA} = \$100 * 15\% + \$100 * 5\% = \$20.$$

$$\text{TEV} = \$100 - \$20 + 40 = \$120. \text{ Therefore, TEV / EBITDA} = 6x.$$

The treatment of the Lease Liabilities here is uncertain because we don't know if this company follows U.S. GAAP or IFRS or if these are Operating or Finance Leases. To explain the correct treatment, you must request these details (see the next question).

### 6. For clarity, the company I just described followed U.S. GAAP, and the Lease Liabilities were for Operating Leases.

Now, imagine that this company followed IFRS rather than U.S. GAAP. How would the EBIT margin and D&A percentages change, and how would the TEV / EBITDA change?

Under IFRS, the EBIT margin would be **higher** because only one component of the Operating Lease Expense would be deducted: The Lease Depreciation. Under U.S. GAAP, the entire Rental Expense is deducted.

The D&A percentage would also be **higher** because D&A under IFRS includes Lease Depreciation as well.

So, the EBITDA margin would be **higher** under IFRS because it would *exclude or add back* the entire Operating Lease Expense so that the EBITDA would be higher than $15.

The TEV / EBITDA multiple would likely stay about the same because under IFRS, you would add the Lease Liabilities to calculate Enterprise Value (you would need more numbers to predict the exact change).

### 7. What are the advantages and disadvantages of TEV / EBITDA vs. TEV / EBIT vs. P / E?

TEV / EBITDA is better when you want to *ignore the company's CapEx and capital structure completely*.

TEV / EBIT is better when you want to *ignore capital structure but partially factor in CapEx* (via the Depreciation, which comes from CapEx in previous years).

So, TEV / EBITDA is more about **normalizing companies** and is more useful in industries where CapEx is not a huge value driver, while TEV / EBIT is better when you want the implied values to have some relationship with CapEx.

The P / E multiple is affected by different tax rates, capital structures, non-core business activities, and more, so it is less useful for "normalization" purposes than the others (though it has the advantage of being widely understood).

P / E is more important in specific industries, such as banks and insurance firms, that use Equity Value as the leading valuation metric.

### 8. A company is currently trading at 10x TEV / EBITDA. It wants to sell an Operating Asset for 2x the Asset's EBITDA. Will that transaction increase or decrease the company's Enterprise Value and its TEV / EBITDA multiple?

The sale will **reduce** the company's Enterprise Value because the company is trading an Operating Asset for Cash, which is a Non-Operating Asset.

Even though the company's Enterprise Value decreases, its TEV / EBITDA multiple **increases** because the Asset's multiple was lower than the entire company's multiple.

To understand this, pretend the company's total EBITDA was $100, and this Asset contributed $20 of that EBITDA. Therefore, the company's Enterprise Value before the sale was $1,000.

The company now sells the Asset for 2x * $20 = $40. After the sale, the company's Enterprise Value falls by $40, and its EBITDA falls by $20. So, its new TEV / EBITDA is $960 / $80, or 12x.

### 9. What happens to the company's Equity Value and P / E multiple in this scenario?

We can't say for sure, but based on the information provided here, Equity Value **does not change** because the Net Assets stay the same (Operating vs. Non-Operating Assets do not matter for Equity Value). It would change only if there were a Gain or Loss recorded on the sale, as that would flow into Common Shareholders' Equity via Net Income.

*Most likely*, the P / E multiple would **increase** because this company is *most likely* trading at a higher P / E multiple than this specific asset if it's a 10x vs. 2x difference for the EBITDA multiples. However, we can't say for sure because there could be a huge capital structure difference between the company and this specific asset.

### 10. How do you calculate and use Unlevered FCF and Levered FCF?

**Unlevered Free Cash Flow** equals Net Operating Profit After Taxes (NOPAT) + D&A and sometimes other non-cash adjustments +/- Change in Working Capital – CapEx.

**Levered Free Cash Flow** equals Net Income to Common + D&A and sometimes other non-cash adjustments +/- Change in Working Capital – CapEx +/- Net Change in Debt.

You normally use UFCF in DCF-based valuations because it lets you evaluate a company independently of its capital structure, which produces more consistent numbers.

LFCF is far less widely used (and people disagree about the basic definition), but it is more common in certain specialized contexts/industries (e.g., equity REITs).

### 11. If a company is valued mostly based on its cash flow, why do you also use metrics such as EBIT and EBITDA that may not represent its true cash flow?

You use these metrics mostly for **convenience** and **comparability**. Free Cash Flow measures a company's cash flow more accurately, but it also takes more time to calculate since you need to review the full Cash Flow Statement and make adjustments.

Also, the individual items *within* FCF vary widely for different companies, regions, industries, and accounting systems.

As a result, EBIT and EBITDA are better for comparability/normalization purposes since they are based primarily on the Income Statement (and one line of the CFS for EBITDA).

### 12. Give an example of a company change that affects UFCF but not EBITDA.

Additional spending on CapEx or a higher-than-normal Change in Working Capital (e.g., due to a large Inventory purchase) would affect UFCF but not EBITDA since UFCF deducts CapEx and reflects the Change in Working Capital (which could be either positive or negative).

### 13. Company A has a P / E multiple of 15x, with a Net Income of $120 and a TEV / EBITDA multiple of 15x. Its EBITDA is $150.

Company B has the same 15x P / E multiple but a Net Income of $100, a TEV / EBITDA of 10x, and an EBITDA of $200.

Which one has a higher Net Debt balance?

Company A's Equity Value is 15x * $120 = $1800, and its Enterprise Value is 15x * $150 = $2250.

Company B's Equity Value is 15x * $100 = $1500, and its Enterprise Value is 10x * $200 = $2000.

Therefore, Company A's Net Debt is $2250 – $1800 = $450, and Company B's Net Debt is $2000 – $1500 = $500, so Company B has a higher balance.

### 14. A company's Operating Income is $100, and it has a $500 Debt balance at a 4% interest rate. It also has Cash of $100, currently earning 0% interest.

If the company's Equity Value is $600, its P / E multiple is 12x, and its tax rate is 25%, what can you conclude about its Enterprise Value?

An Equity Value of $600 and a P / E multiple of 12x means the company's "apparent" Net Income is $600 / 12 = $50.

The company's Operating Income is $100, and it pays $500 * 4% = $20 in Interest Expense per year, with no Interest Income.

So, its Pre-Tax Income is $80, and its Net Income "should be" $60 at a 25% tax rate.

However, it is clearly lower than that, so the most likely explanation is that the company has **Preferred Stock** in its capital structure.

For example, if the company had $10 in Preferred Dividends, the *Net Income* would be $60, and the *Net Income to Common* would be $50 (which you use in the P / E multiple).

We don't know the exact amount of Preferred Stock, but the company's Enterprise Value **must be higher** than $600 - $100 + $500 = $1000 due to it.

### 15. Suppose you are building a set of "global" comparable companies operating in the logistics/delivery sector in the U.S., Europe, and Asia. What is the SAFEST valuation multiple in this scenario?

Given the lease accounting differences under U.S. GAAP vs. IFRS, the safest multiple is (Enterprise Value Including All Lease Liabilities) / EBITDAR, where EBITDAR equals EBITDA + Rental Expense.

Under IFRS, EBITDA already adds back or excludes the full Lease Expense, so the Rental Expense is minimal. But under U.S. GAAP, there is still Rental Expense for the Operating Leases.

Therefore, this multiple normalizes accounting and lease composition differences and allows for a proper comparison.
