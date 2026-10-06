## Technical Questions (Generalist)

These sections act as a **quick review** if you already have a decent understanding of the key technical concepts.

They do **not** teach you the concepts from the ground up or walk you through models.

Please click the links in each section's description for the full walkthroughs and Excel files.

## Finance Concepts

"Finance" refers to concepts such as the time value of money, the Discount Rate, and the internal rate of return (IRR).

Interviewers may not ask about them directly, but they often come up with other questions about accounting and valuation.

- Interview Guide – Finance Concepts | Quiz Questions
- Core Financial Modeling – Finance Concepts Module

### 1. Explain the time value of money. Is money today worth more than money next year due to inflation?

No. The time value of money means you could **invest money today** and earn something additional with it by next year.

Inflation also makes money less valuable over time, but the time value of money is about the *potential returns* of an investment made today.

### 2. What does the "Discount Rate" mean?

The Discount Rate represents your **opportunity cost** or "targeted annualized return." In other words, if you don't invest in *this* company, how much could you earn over the long term by investing in other, similar companies?

The Discount Rate represents **the potential returns and the risk** of other, similar opportunities.

If the Discount Rate is higher, both the potential returns and the risk are higher; the opposite is true if the Discount Rate is lower.

### 3. Why is the Discount Rate higher if the potential returns are higher? Shouldn't a company with higher potential returns have a lower Discount Rate, making it more valuable?

No. The Discount Rate is higher because *the potential returns and the risk move together*: If a stock could potentially go up by 10x, it's much riskier than a stock that only has the potential to increase by 2x.

The point is that there's no such thing as a "free lunch": Higher potential returns also mean that your chances of losing money are higher.

### 4. What is WACC?

WACC stands for the "Weighted Average Cost of Capital," the most common Discount Rate used to value companies.

To calculate it, you multiply the % Equity in a company's capital structure by the "Cost" of that Equity, multiply the % Debt in the company's capital structure by the "Cost" of that Debt, and add them up (and, if applicable, Preferred Stock and other long-term funding sources).

For example, if a company uses 60% Equity and 40% Debt, its Cost of Equity is 10%, and its Cost of Debt is 5%, then its WACC is 60% * 10% + 40% * 5% = 8%.

WACC represents the average annualized return you'd expect to earn if you invested proportionally in the Debt AND Equity of a company and held them for the long term.

### 5. How much would you pay for a company that generates $100 of cash flow every single year into eternity?

Company Value = Cash Flow / (Discount Rate – Cash Flow Growth Rate), where Cash Flow Growth Rate < Discount Rate.

If the cash flow does not grow at all, Company Value = Cash Flow / Discount Rate.

So, if your Discount Rate, or "targeted yield," is 10%, you'd pay $100 / 10% = $1,000.

But if your targeted yield is 20%, you'd pay only $100 / 20% = $500 for this company.

### 6. A company generates $100 of cash flow today, and its cash flow is expected to grow at 5% per year for the long term. You could earn 10% per year by investing in other, similar companies. How much would you pay for this company?

Company Value = Cash Flow / (Discount Rate – Cash Flow Growth Rate), where Cash Flow Growth Rate < Discount Rate.

So, this one becomes: $100 / (10% – 5%) = $2,000.

A higher Discount Rate makes a company less valuable, and a higher cash flow growth rate makes a company more valuable.

### 7. What does "Present Value" mean, and what makes it change? How does it differ from Net Present Value?

The Present Value (PV) of an asset or company equals its future cash flows *discounted* at the appropriate Discount Rate (e.g., ~10% for many stocks).

"Discount" means that you take a future cash flow, such as $100, and divide it by ((1 + Discount Rate) ^ Year #), assuming a constant Discount Rate in each period.

The PV tells you what a company or asset is worth *today* based on its potential future performance and your returns expectations.

The PV increases if the company's expected future cash flow or growth rate increases or the Discount Rate decreases.

The PV decreases if the opposite happens.

"Net Present Value" means that you take the PV of these future cash flows and subtract the upfront cost or "asking price" of the company.

If the NPV is positive, the company is worth more than its current price.

### 8. What does the internal rate of return (IRR) mean? How do you calculate it?

In technical terms, the IRR represents the Discount Rate at which the Net Present Value of an investment equals 0.

Colloquially, you can think of it as "the effective compounded rate of return on an investment."

For example, if you invest $1,000 today and end up with $2,000 after 5 years, the IRR represents the return you'd have to earn on that $1,000, compounded each year, to reach $2,000 in 5 years.

It's 14.9% in this example, which you can verify with a calculator or Excel.

To calculate the IRR, enter the upfront investment as a negative in Excel and the future cash flows and sale value as positives and apply the IRR function to the whole range.

### 9. What affects the IRR? How do these factors differ from the ones that affect the Present Value?

Many factors are the same: Higher cash flows, growth rates, or future sale values for the asset increase both the Present Value and the IRR. Lower values for these assumptions reduce both the Present Value and the IRR.

One major difference is that the Discount Rate does NOT affect the IRR – because you are solving for the Discount Rate when you calculate the IRR!

The whole point of the calculation is that you can compare the IRR to the Discount Rate to determine if the investment is worth your time and money.

Another major difference is that the upfront price or "asking price" affects the IRR since it's entered as a negative for the first value in the series, but it does not impact the Present Value.

You should compare the Present Value to this upfront price to see if the investment is worth more or less than its price.

### 10. How do you use the IRR, Discount Rate, and Present Value to make investment decisions?

Normally, you calculate the IRR and compare it to the Discount Rate of a project, investment, or company.

If the IRR exceeds the Discount Rate, investing makes sense; if not, you should not invest.

Comparing the Present Value to the upfront price does the same thing: If the PV of the future cash flows exceeds this upfront price, invest; otherwise, do not invest.
