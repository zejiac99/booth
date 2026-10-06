# Discounted Cash Flow (DCF) – Assumptions and Analysis

|     | A | B | C                                    | D | E          | F          | G          |
| --- | - | - | ------------------------------------ | - | ---------- | ---------- | ---------- |
| 6   |   |   |                                      |   |            |            |            |
| 7   |   |   | Forecast Period Discount Rate:       |   |            | 10.0%      |            |
| 8   |   |   | Initial Cash Flow in Forecast:       |   |            | $ 100      |            |
| 9   |   |   | PV of Cash Flows, Years 1 - 10:      |   |            | 819        |            |
| 10  |   |   |                                      |   |            |            |            |
| 11  |   |   | Terminal Period Discount Rate:       |   |            | 9.0%       |            |
| 12  |   |   | Terminal Cash Flow Growth Rate:      |   |            | 2.0%       |            |
| 13  |   |   | PV of Cash Flows, Beyond Year 10:    |   |            | 2,467      |            |
| 14  |   |   | Discounted to Present Value Today:   |   |            | 951        |            |
| 15  |   |   |                                      |   |            |            |            |
| 16  |   |   | **Implied Company Value:**           |   |            | **$ 1,770**|            |
| 17  |   |   |                                      |   |            |            |            |
| 18  |   |   |                                      |   | **Year 1** | **Year 2** | **Year 3** |
| 19  |   |   | Annual Cash Flow:                    |   | $ 100      | $ 110      | $ 120      |
| 20  |   |   | Cash Flow Growth Rate:               |   |            | 10.0%      | 9.0%       |

Questions about the DCF analysis are among the most common ones in interviews. Even if you don't understand all the details, you **must** be able to walk through the basic analysis (see the image on the left).

You should also understand the factors that affect the analysis and the importance of the Terminal Value vs. the Discount Rate vs. the Cash Flows in the forecast period.

The **Discount Rate** is such a big topic that we cover it separately in the next section; the Finance Concepts section also explains the main idea.

- Interview Guide – DCF / Valuation | Quiz Questions
- Core Financial Modeling – DCF / Valuation Module

### 1. Why do you build a DCF analysis to value a company?

In theory, a company is worth the Present Value of its expected future cash flows:

**Company Value** = Cash Flow / (Discount Rate – Cash Flow Growth Rate), where Cash Flow Growth Rate < Discount Rate

But you can't just use this single formula because a company's **Cash Flow Growth Rate** and **Discount Rate** change over time.

So, in a Discounted Cash Flow analysis, you divide the valuation into two periods: One where those assumptions may change (the **explicit forecast period**) and one where they stay the same (the **Terminal Period**).

You then project the company's cash flows in both periods and discount them to their Present Values based on the appropriate Discount Rate(s).

You compare this sum – the company's Implied Value – to its Current Value or "Asking Price" to see if it's valued appropriately.

### 2. Walk me through a DCF analysis.

A DCF values a company based on the Present Value of its Cash Flows in the explicit forecast period plus the Present Value of its Terminal Value.

You start by projecting the company's Free Cash Flows over the next 5 – 10 years by making assumptions for the revenue growth, margins, Working Capital, and CapEx.

Then, you discount the cash flows using the Discount Rate, usually the Weighted Average Cost of Capital, and sum up everything.

Next, you estimate the Terminal Value using the Multiples Method or the Gordon Growth Method; it represents the company's value after those first 5 – 10 years into perpetuity.

You then discount the Terminal Value to Present Value using the Discount Rate and add it to the sum of the company's discounted cash flows to get its Implied Enterprise Value.

Finally, you add Cash and subtract Debt (and add/subtract all other relevant line items) to get the Implied Equity Value, divide by the share count to get the Implied Share Price, and compare this to the company's Current Share Price.

### 3. How do you move from Revenue to Free Cash Flow in a DCF?

First, confirm that the interviewer is asking for Unlevered Free Cash Flow (AKA Free Cash Flow to Firm). If so:

Subtract COGS and Operating Expenses from Revenue to get Operating Income (EBIT).

Then, multiply Operating Income by (1 – Tax Rate), add back Depreciation & Amortization, and factor in the Change in Working Capital (which could be either positive or negative).

If Working Capital increases, the Change in WC is negative, and if it decreases, the Change in WC is positive.

Finally, subtract Capital Expenditures to calculate Unlevered Free Cash Flow.

### 4. How do you calculate the Terminal Value in a DCF, and which method is best?

You can use the Multiples Method or the Gordon Growth Method (AKA Long-Term Growth Method, Perpetuity Growth Method, etc.).

With the first one, you apply a Terminal Multiple to the company's EBITDA, EBIT, NOPAT, or FCF in the final year of the forecast period. For example, if you apply a 10x TEV / EBITDA multiple to the company's Year 10 EBITDA of $500, its Terminal Value is $5,000.

With the Gordon Growth Method, you assign a "Terminal Growth Rate" to the company's Free Cash Flows in the Terminal Period and assume they'll grow at that rate forever.

Terminal Value = Final Year Free Cash Flow * (1 + Terminal Growth Rate) / (Discount Rate – Terminal Growth Rate)

The Gordon Growth Method is better from a theoretical perspective because growth always slows down over time; all companies' cash flows eventually grow more slowly than GDP.

If you use the Multiples Method, it's easy to pick a multiple that makes no logical sense because it implies a growth rate that's too high.

However, many bankers still use and prefer the Multiples Method because it's "easier" or because they don't understand the issues with Terminal Multiples.

### 5. Suppose you build a Levered DCF instead of an Unlevered DCF. What changes?

First, you use Levered FCF instead of Unlevered FCF, which means you deduct the Net Interest Expense from EBIT before multiplying it by (1 – Tax Rate); you also factor in new Debt issuances and Debt principal repayments, which could make a net positive or negative impact.

Second, you use the Cost of Equity rather than WACC for the Discount Rate because Levered FCF is available only to the common shareholders.

Third, you calculate the Terminal Value using an Equity Value-based multiple such as P / E or Equity Value / Levered FCF.

Finally, there is no "bridge" at the end because in a Levered DCF, you calculate the company's Implied Equity Value directly based on the PV of the cash flows and the Terminal Value.

### 6. Will you get the same results from an Unlevered DCF and a Levered DCF?

No. The simplest explanation is that an Unlevered DCF does not directly factor the Cost of Debt into the FCF projections, while a Levered FCF does. The Unlevered DCF indirectly accounts for it via the WACC calculation, but it won't be equivalent to the Levered version.

That alone creates differences, but the more volatile cash flow in a Levered DCF (due to the Change in Net Debt) also plays a role. It's difficult to pick equivalent assumptions, and it's not worth considering because almost no one uses the Levered DCF in real life.

### 7. A client company plans to change its capital structure. Currently, it has 10% Debt / Total Capital, but it wants to increase this to 30%. Your co-worker claims that if you use an Unlevered DCF to value this company, it won't be affected by this change in capital structure.

**Are they correct?**

No. It's true that the *Unlevered Free Cash Flow* won't be affected by this change in capital structure and the higher Interest Expense, but the *Discount Rate* will be affected.

To account for this difference, you should calculate WACC under both capital structure percentages and use a changing Discount Rate each year in the analysis as the company progresses from 10% to 30% Debt / Total Capital over the forecast period.

### 8. What is the logic behind the main components of Unlevered Free Cash Flow? For example, why does it include the Change in Working Capital but not the Net Interest Expense?

Unlevered FCF reflects the **core, recurring line items available to ALL investor groups**.

That's because Unlevered FCF corresponds to Enterprise Value, which represents the value of the company's core business available to all the investor groups.

So, if an item is **NOT** recurring, **NOT** related to the company's core business, or **NOT** available to all investor groups, you ignore it in UFCF.

The Change in Working Capital is recurring, related to the core business, and available to all the investor groups, so it is included. The Net Interest Expense is related to the company's financing, not its core business, and is only available to the lenders, so it is not included.

### 9. What's the relationship between subtracting an expense in the FCF projections and the Enterprise-Value-to-Equity-Value "bridge" at the end of the DCF?

If you **subtract** a certain expense in FCF, then you **ignore** its corresponding Liability in the "bridge" at the end (i.e., the place where you add Cash, subtract Debt, etc., to move from Enterprise Value to Equity Value).

But if you **ignore or exclude** a certain expense, you should **subtract** its corresponding Liability in the bridge.

The perfect example is Debt: In an Unlevered DCF, you ignore the Interest Expense, so you subtract the Debt as a Liability in the bridge.

### 10. Should you add back Stock-Based Compensation to calculate Free Cash Flow? It's a non-cash add-back on the Cash Flow Statement.

No! You should consider SBC a *cash expense* in the context of a valuation because it creates **additional shares** and dilutes the existing investors. So, it's not just a simple "timing difference" line item like CapEx and D&A.

As a real-life example, imagine owning a house, renting it out, and paying someone to manage the tenants for you. Instead of paying them a salary, you give them a 1% stake in your house each year.

If you now sell your house after 10 years, you only get **90% of the proceeds** rather than 100%. You may not have paid this manager in cash, but you still paid them! SBC works the same way but with a company's existing shareholders and their ownership.

### 11. What's the intuition behind the Gordon Growth formula for Terminal Value?

The typical formula is:

**Terminal Value** = Final Year FCF * (1 + Terminal FCF Growth Rate) / (Discount Rate – Terminal FCF Growth Rate)

A company is worth more if its growth rate is higher in the Terminal Period and less if its growth rate is lower; it's also worth more if its starting FCF in the Terminal Period is higher.

If the company's Discount Rate is higher, the company is worth less because the denominator is bigger (and vice versa).

### 12. If you use the Multiples Method to calculate Terminal Value, do you use the multiples from the Public Comps or Precedent Transactions?

It's better to start with the multiples from the Public Comps – ideally, the ones from 1-2 years into the future – because you **don't** want to reflect the control premium in the Precedent Transactions if you're completing a standalone company valuation.

If the selected multiples imply a reasonable Terminal FCF Growth Rate, you might stick with your initial guess; if not, adjust it up or down as necessary.

### 13. How do you pick the Terminal Growth Rate when calculating the Terminal Value using the Gordon Growth Method?

This growth rate should be *below* the country's long-term GDP growth rate and in line with other macroeconomic variables like inflation.

For example, if you're in a developed country where the expected long-term GDP growth rate is 3%, you might use numbers ranging from 1% to 2% for the Terminal Growth Rates.

### 14. How can you check whether your Terminal Value estimate is reasonable?

You start by entering a range of assumptions for the Terminal Multiple or Terminal FCF Growth Rate, and you cross-check them by calculating the Growth Rates or Multiples they *imply*.

If these seem wrong, you adjust the range of Terminal Multiples or Terminal FCF Growth Rates until you get more reasonable results.

For example, if the multiple you pick implies a Terminal FCF Growth Rate of 5%, that's too high for developed countries, so you should pick a lower Terminal Multiple.

### 15. Does it ever make sense to use a negative Terminal FCF Growth Rate?

Yes. For example, if you're valuing a biopharmaceutical company, and the patent on its key drug expires within the explicit forecast period, it might be reasonable to assume that the company never replaces the lost revenue from this drug, which results in declining cash flow.

A negative Terminal FCF Growth Rate represents your expectation that the company will stop generating cash flow eventually (even if it happens decades into the future).

It doesn't make the company "worthless"; it's just *worth less*.

### 16. Explain how you deal with leases and lease accounting in a DCF.

The easiest solution is to treat the full Lease Expense (from both Finance and Operating Leases) as a simple cash operating expense and deduct it in the FCF projections.

If you do this, you can ignore the Lease Liabilities in the bridge and the WACC calculation, greatly simplifying the analysis.

You could do the opposite and treat Leases as "capital" and add back or exclude the full Lease Expense in the projections, deduct the change in Lease Liabilities, deduct Lease Liabilities in the bridge, and count Leases in WACC, but this adds significant work and barely changes the results.

### 17. You have just finished building a DCF for a new client. What are some potential "warning signs" that your assumptions may not be correct?

First, the company's revenue and FCF growth should always decline and fall to very low levels by the end of the forecast period (right around GDP growth or inflation).

Second, the PV of the Terminal Value might account for far too much value, such as 95% of the total; if this is the case, you should extend the forecasts so the FCF contributes more. If this happens, you should also check the Implied Terminal Growth Rates and Multiples.

Third, you may be double-counting items; if you deduct an expense in UFCF, it should not appear in the Enterprise Value bridge.

Finally, be careful with the margin, CapEx, and D&A assumptions. The margins should stabilize further into the forecast period, and CapEx should remain ahead of D&A even into the Terminal Period if you are assuming continued growth.

### 18. Why do you use the mid-year convention in a DCF, and how does it affect the results?

You use it because a company's cash flows do not arrive 100% at the end of each year – the company generates cash flow throughout each year.

Using 1, 2, 3, 4, etc., for the discount periods implies that one full year must pass for the first cash flow to arrive (and then another full year after that for the next one).

If you use 0.5, 1.5, 2.5, 3.5, etc., instead, you assume that only half a year passes before the first cash flow is generated, which is closer to real life. A full year still separates each subsequent cash flow, but they now arrive in the middle of each year.

A DCF using the mid-year convention will produce **higher implied values** because the discount periods are lower, and money in 0.5 years is worth more today than money in 1.0 years.

### 19. Why might you include a "stub period" in a DCF, and what does it mean?

You might include a "stub period" if you're valuing a company midway through the year and it has already reported some of its financial results.

A DCF is based on *expected future cash flow*, so you should **subtract** these previously reported results and adjust the discount periods as well.

For example, maybe it's September 30th, and the company's fiscal year ends on December 31st.

The company's *future cash flow for this year* will be generated between September 30th and December 31st.

Therefore, you should **exclude** the cash flow from January 1st to September 30th in your projections since that part of the year has already passed.

So, in the first year, you would include only the projected FCF from September 30th to December 31st. To discount the FCF in those 3 months, you would use 0.25 for the discount period because 3 months is 25% of the year.

You would then use 1.25 for the discount period of the next year, 2.25 for the year after that, and so on.

### 20. Suppose that a company goes from using 0% Debt in its capital structure to 20%. How will its WACC and Implied Value from a DCF change?

*Most likely*, its WACC will decrease because Debt is cheaper than Equity due to the lower expected/targeted returns and the tax-deductibility of interest paid on Debt.

So, when most companies go from 0% Debt to a low/moderate amount of Debt, their WACCs tend to decrease, which means their Implied Values from a DCF increase.

Above this moderate Debt level, WACC will start to increase as the Cost of Debt and Cost of Equity begin to increase, which will reduce the company's Implied Value.

### 21. Let's say that the central bank has just raised short-term interest rates from 2% to 5% to fight inflation. How will this affect the WACC and the DCF valuation of a company?

*Most likely*, WACC will increase, and the company's Implied Value from the DCF will decrease because the Discount Rate is now higher due to a higher Risk-Free Rate.

A higher Risk-Free Rate increases both the Cost of Equity and the Cost of Debt, as the Cost of Equity is based on Risk-Free Rate + Equity Risk Premium * Levered Beta, and the Cost of Debt is based on the cost of issuing additional Debt *today*.

However, higher short-term rates do not always translate into higher *long-term government bond yields*, so we hedged this answer with the "most likely" part. If the 10-year yield you're using for the Risk-Free Rate stays the same, and the other parameters also stay the same, nothing changes.

### 22. You have just finished building a DCF model. Will it make more of a difference to change the average revenue growth rate from 10% to 5% or to change the Discount Rate from 10% to 5%?

*Most likely*, changing the Discount Rate from 10% to 5% will make a bigger difference because the Discount Rate affects both the PV of the Cash Flows and the PV of the Terminal Value, and a 5% vs. 10% difference is very significant because it compounds over time.

Changing the revenue growth from 10% to 5% will reduce the company's Cash Flows and Terminal Value, but not by quite the same factor; the Year 10 revenue will be ~35% lower, which may not even translate into a 35% difference in FCF.

### 23. The government has just decided to cut the corporate tax rate in your country from 35% to 20%. How will WACC and the DCF output of your valuation change?

The tax rate affects both the FCF and the Discount Rate. *If* a company has Debt, a lower tax rate will increase its Cost of Debt because the interest paid on Debt will produce a reduced tax benefit; the Cost of Equity will also be higher because that same tax rate also factors in when levering and re-levering Beta.

So, WACC tends to **increase slightly** from this tax rate reduction, but **FCF also increases**, which tends to be more significant than the increase in WACC. So, the company's Implied Value should most likely increase. If the company has no Debt, its Implied Value definitely increases.
