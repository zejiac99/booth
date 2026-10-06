**24. You're building a 10-year DCF for a growth-oriented tech company. Your VP reviews your model and asks you to extend the forecast period to 20 years. How will the output change?**

The main difference with a longer forecast period is that the PV of the Terminal Value should now account for a reduced percentage of the company's total Implied Value from the DCF (e.g., 50% vs. 70%).

We can't say if the Implied Value will go up or down because it depends on the specific numbers and the relative weight of the Terminal Value vs. everything else.

**25. Two companies have the same financial profiles and operate in the same industry, but one is in an emerging market, and the other is in a developed market. How will their DCF outputs differ?**

The one in the emerging market should have a higher Discount Rate and, therefore, a lower Implied Value because the geopolitical risk, equity risk, and credit default risk are all higher.

This might not always be true if the emerging market company is also growing more quickly, as the higher growth could offset the higher Discount Rate – but the question says these companies have "the same financial profiles."

Return to Top.

## Discounted Cash Flow (DCF) – The Discount Rate

Questions related to the Discount Rate and WACC in a DCF are surprisingly tricky because it's not always easy to explain how the assumptions are linked.

You don't need to know every detail of these calculations, but you should know the **intuition** behind everything.

If you understand that the Discount Rate represents the opportunity cost and that the Debt and Equity levels affect *all* investors, you can answer most of these questions.

### 1. What does the Cost of Equity mean intuitively?

It tells you the average percentage a company's stock "should" return each year over the long term, factoring in both stock-price appreciation and dividends.

In a valuation, it represents the average annualized return that equity investors might earn over the long term.

To a company, the Cost of Equity represents the cost of funding its operations by issuing additional shares to investors.

The company "pays for" Equity via potential Dividends (a real cash expense) and the dilution of existing investors.

### 2. What does WACC mean intuitively?

WACC is your expected or targeted annualized return if you invest proportionately in *all parts* of the company's capital structure – Debt, Equity, and Preferred Stock.

To a company, WACC represents the cost of funding its operations by using **all** its sources of capital and keeping its capital structure percentages the same over time.

Investors might invest in a company if the expected IRR exceeds its WACC, and a company might fund a new project, acquisition, or expansion if the expected IRR exceeds its WACC.

### 3. How do you calculate the Cost of Equity?

**Cost of Equity** = Risk-Free Rate + Equity Risk Premium * Levered Beta

The Risk-Free Rate represents the yield on "risk-free" government bonds denominated in the same currency as the company's cash flows. You usually use 10-year or 20-year bonds to match the explicit forecast period of the DCF.

Levered Beta represents the volatility of this stock relative to the market as a whole, factoring in both **intrinsic business risk** and **risk from leverage**.

And the Equity Risk Premium represents how much the stock market in the company's country will return above the "risk-free" government bond yield in the long term.

Stocks are riskier and have higher potential returns than government bonds, so you take the yield on the bonds, add the *extra* returns you could get from the stock market, and then adjust for *this company's* specific risk and potential returns.

### 4. If a company operates in the EU, U.S., and U.K., what should you use for its Risk-Free Rate?

You should use the appropriate yield on the government bonds denominated in the currency of the company's cash flows.

So, if the company reports its financials in USD, you might use the yield on 10-year U.S. Treasuries; if it reports them in EUR, you might use the yield on 10-year bonds issued by the government in a European country that uses the EUR. And if the financials are in GBP, you would use the yield on 10-year bonds issued by the Bank of England ("gilts").

### 5. How do you calculate the Equity Risk Premium for a multinational company operating in many geographies?

You might take the percentage of revenue earned in each country, multiply it by the ERP for that country's stock market, and then add the terms to get the weighted average ERP.

To calculate the ERP in each market, you would calculate the average annualized returns of the country's stock market vs. the Risk-Free Rate in that country over the long term. If that is not feasible or the data does not exist, you could also take the U.S. stock market ERP and add a default spread to represent the additional risk of the other country.

### 6. What does Beta mean intuitively?

*Levered Beta* tells you how volatile a company's stock price is relative to the stock market as a whole, factoring in both **intrinsic business risk** and **risk from leverage** (i.e., Debt).

If Beta is 1.0, when the market goes up 10%, this company's stock price also increases by 10%.

If Beta is 2.0, when the market goes up 10%, this company's stock price goes up by 20%.

If the market drops by 10%, this company's stock price falls by 10% when the Beta is 1.0 or 20% when the Beta is 2.0.

*Unlevered Beta* excludes the risk from leverage and reflects only the intrinsic business risk, so it's always less than or equal to Levered Beta.

### 7. What are the formulas for un-levering and re-levering Beta, and what do they mean?

**Unlevered Beta** = Levered Beta / (1 + Debt / Equity * (1 – Tax Rate) + Preferred Stock / Equity)

**Levered Beta** = Unlevered Beta * (1 + Debt / Equity * (1 – Tax Rate) + Preferred Stock / Equity)

You use a "1 +" before the Debt / Equity * (1 – Tax Rate) term to ensure that Unlevered Beta is always less than or equal to Levered Beta.

You multiply the Debt / Equity term by (1 – Tax Rate) because the tax-deductibility of interest reduces the risk of Debt.

When you move *from* Levered Beta *to* Unlevered Beta, you divide by the "risk from leverage" term to remove it and reduce Beta accordingly; it's the opposite when moving from Unlevered to Levered Beta.

You un-lever and re-lever Beta because when you calculate WACC in a DCF, you want to isolate the "inherent business risk" and then take that risk and add the *company-specific risk from leverage* for the company you're valuing.

### 8. How do you calculate WACC, and why does it pair with Unlevered Free Cash Flow?

The *formula* for WACC is simple:

**WACC** = Cost of Equity * % Equity + Cost of Debt * (1 – Tax Rate) * % Debt + Cost of Preferred Stock * % Preferred Stock

There is some disagreement around the different ways to calculate each component, but the basic formula is straightforward.

It pairs with UFCF because they both represent all the investors in the company. It is **not** "capital structure-neutral" because *no Discount Rate can be*. Each investor group affects the others!

### 9. Why is Equity more expensive than Debt?

Because it offers higher risk and higher potential returns and lacks the tax benefits of Debt.

Expected stock market returns usually exceed the Yield to Maturity on Debt, making the Equity cost higher. The interest on Debt is also tax-deductible, further reducing the Debt cost and making Equity even more expensive.
