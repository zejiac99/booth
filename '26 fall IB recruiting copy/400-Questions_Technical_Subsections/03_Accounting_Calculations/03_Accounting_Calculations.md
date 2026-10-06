# Accounting – Calculations

If you understand how the 3 financial statements link together, these questions will be straightforward.

If not, these questions will be quite challenging, and you'll need a good amount of practice to master them.

Use the following order when answering these questions:

1. Explain how the **Income Statement** changes, if at all.
2. Explain how the **Cash Flow Statement** changes, if at all (including changes in Deferred Taxes).
3. Explain how the **Balance Sheet** changes and why it still balances, i.e., why Assets still equal Liabilities + Equity.

It's also important to understand whether the interviewer wants you to walk through *a single change in one step* or to *combine changes*.

For example, the output looks quite different if they ask you to walk through a simple Debt issuance vs. a Debt issuance with interest and principal repayment over an entire year.

**If anything is unclear, follow up and ask them to clarify whether they want single/individual changes, combined changes, or something else.**

For most accounting interview questions, you can assume a 25% corporate tax rate because this is the average in developed countries, but it's worth verifying this to be sure.

### 1. A company hires a new employee for a total cost of $100,000 per year. Walk me through how the financial statements change, assuming a 25% tax rate.

This is a simple OpEx increase:

- **Income Statement:** Operating Expenses increase by $100K, so Pre-Tax Income is $100K lower. At a 25% tax rate, Net Income is $75K lower.
- **Cash Flow Statement:** Net Income is down by $75K, and there are no other changes, so Cash at the bottom is also down by $75K.

## Accounting Rules

### Cash Flow (CF) Rules

Asset UP → Cash Flow DOWN
Asset DOWN → Cash Flow UP

Liability UP → Cash Flow UP
Liability DOWN → Cash Flow DOWN

Cash Flow from Operations includes Net Income, Non-Cash Adjustments, and changes to Current Assets Excluding Cash and Investments and changes to Current Liabilities Excluding Debt.

Cash Flow from Investing includes changes to many Long-Term Assets and also non-operational Current Assets, such as short-term investments.

Cash Flow from Financing includes changes to many Long-Term Liabilities and Equity items, and also non-operational Current Liabilities, such as short-term debt.

Record Revenue and Expenses only in the period when the associated product or service is delivered. If there's no delivery, use Balance Sheet items like Deferred Revenue and Prepaid Expenses to track these items.

- **Balance Sheet:** Cash is down by $75K on the Assets side, so Total Assets are down by $75K. On the L&E side, Equity is down by $75K due to the Net Income reduction, so both sides are down by $75K and balance.
- **Intuition:** The company spends $100K more but saves $25K in taxes.

### 2. You go into a job interview, and the interviewer points out that every single Interview Guide has a question about how Depreciation going up by $10 affects the statements.

**So, he asks you to walk through a $10 *decrease* in Depreciation, assuming a 25% tax rate.**

This question mostly tests whether you are a human or an NPC:

- **IS:** A $10 reduction in Depreciation means Pre-Tax Income is up by $10. Net Income is up by $7.5 at a 25% tax rate.
- **CFS:** Net Income is up by $7.5, and now you add back *$10 less* of Depreciation, which means that Cash at the bottom is down by $2.5.
- **BS:** Cash is down by $2.5, and Net PP&E is up by $10 because of the reduced Depreciation, so Total Assets are up by $7.5. On the L&E side, Equity is up by $7.5 due to the increased Net Income, so both sides balance.
- **Intuition:** The company loses a $2.5 tax benefit by recording a lower Depreciation number, so its Cash balance falls by $2.5.

### 3. A company's CEO has decided to sell all its assets, starting with a factory recorded at a book value of $100 on its Balance Sheet.

**If this factory sells for $140, how do the statements change?**

This is a Realized Gain of $140 – $100 = $40, which is recorded as follows:

- **IS:** The $40 Realized Gain appears here and increases Pre-Tax Income by $40; Net Income is up by $30 at a 25% tax rate.
- **CFS:** Net Income is up by $30, but you reverse the $40 Gain in CFO. Then, in the CFI section, you reflect the *total amount* of proceeds, or $140. Therefore, Cash changes by +$30 – $40 + $140 = +$130.
- **BS:** Cash is up by $130, and Net PP&E is down by its book value of $100, so Total Assets are up by $30. On the L&E side, Equity is up by $30 due to the increased Net Income, so both sides balance.
- **Intuition:** The company sells the factory for $140 but pays taxes only on the $40 representing the Gain, so its Cash is up by $130 rather than $140.

### 4. Walk me through the financial statements when a customer orders a product for $100 and receives it but hasn't yet paid for it. Then, walk me through the cash collection, combining it with the first step. Ignore COGS and other delivery costs for simplicity.

The first step corresponds to Accounts Receivable increasing by $100, and the second step represents AR decreasing by $100. Here's the first step:

- **IS:** Revenue increases by $100, so Pre-Tax Income is up by $100, and Net Income is up by $75 at a 25% tax rate.
- **CFS:** Net Income is up by $75, but the increase in AR reduces cash flow by $100, so Cash at the bottom is down by $25.
- **BS:** Cash is down by $25, but AR is up by $100, so the Assets side is up by $75. On the L&E side, CSE is up by $75 due to the increased Net Income, so both sides are up by $75 and balance.
- **Intuition:** The company must pay $25 in taxes on Revenue it hasn't yet collected in cash, so its Cash balance falls by $25.

And when the AR is collected, combining it with the first step:

- **IS:** Net Income is still up by $75, and there are no other changes.
- **CFS:** Net Income is still up by $75, but now the AR increase is reversed, so the Change in AR is $0. Therefore, Cash at the bottom is now up by $75.
- **BS:** Cash is now up by $75, and AR goes back to its original level, so the Assets side is up by $75. The L&E side is still up by $75 because of the CSE increase due to the increased Net Income in the first step, so both sides balance.
- **Intuition:** This is a simple cash collection of a $100 payment owed to the company. Initially, Cash was down by $25 because the company had to pay taxes in advance; it's up by $75 in the end because it's a $100 sale minus $25 of taxes.

### 5. A company hires a marketing agency to run an online advertising campaign for its services. The marketing agency charges $10,000 for this initial campaign, delivers it, and invoices the company, which has 60 days to pay. Walk me through the statements.

This is an expense for the delivery of a service that the company has not yet paid in cash, and there is a specific invoice attached, so this is a $10K increase in Accounts Payable:

- **IS:** Operating Expenses increase by $10K, so Pre-Tax Income falls by $10K, and Net Income falls by $7.5K at a 25% tax rate.
- **CFS:** Net Income is down by $7.5K, but the increase in Accounts Payable is a $10K cash inflow because the company has not paid the invoice in cash yet. Cash at the bottom is up by $2.5K.
- **BS:** Cash is up by $2.5K, so Total Assets are up by $2.5K. On the L&E side, AP is up by $10K, and Equity is down by $7.5K due to the reduced Net Income, so both sides are up by $2.5K and balance.
- **Intuition:** The company gets a $2.5K tax benefit on this expense that it has not yet paid in cash.

### 6. Now, walk me through what happens ONLY in Step 2, when the company finally makes payment after 60 days. Also, explain intuitively what happens from start to finish.

This corresponds to the payment of a previous Accounts Payable line. In **ONLY** this cash payment step:

- **IS:** No changes.
- **CFS:** Net Income is the same, but Accounts Payable now decreases by $10K, which is a cash outflow on the CFS. Cash is down by $10K.
- **BS:** Cash is down by $10K on the Assets side, and AP is down by $10K on the L&E side, so both sides are down by $10K, and the Balance Sheet balances.
- **Intuition:** The company has finally paid this $10K bill. It received the tax benefit for this expense in a *previous period*, so it's not part of this step.

**From start to finish**, the company's Cash balance is down by $7.5K because it paid $10K for this marketing campaign but also received a $2.5K tax deduction. There are no permanent changes to AP because it increased by $10K and then decreased by $10K as the payment was made.

### 7. Your friend's e-commerce company orders $200 of products from its main supplier. A month later, it sells these products for $500.

**Walk me through each step of this process SEPARATELY.**

The initial step is an Inventory purchase, and the second step is a recognition of Revenue and COGS and the removal of the Inventory. Here's Step 1:

- **IS:** No changes because no product has been sold or delivered yet.
- **CFS:** The Inventory increase reduces cash flow by $200, so Cash is down by $200.
- **BS:** Cash is down by $200 on the Assets side, and Inventory is up by $200. Nothing changes on the L&E side, so the BS remains in balance.
- **Intuition:** The company has spent $200 of Cash on Inventory.

And Step 2:

- **IS:** Revenue is up by $500, and COGS is up by $200, so Pre-Tax Income is up by $300, and Net Income is up by $225 at a 25% tax rate.
- **CFS:** Net Income is up by $225, and Inventory now decreases by $200, which is a positive cash flow, so Cash is up by $425 *in just this step*.
- **BS:** Cash is up by $425, and Inventory is down by $200, so the Assets side is up by $225. On the L&E side, Equity is up by $225 due to the increased Net Income, so both sides balance.
- **Intuition:** *In just this step*, the company recovers $200 in cash from the sale of the Inventory, earns a $300 pre-tax profit, and pays $75 in taxes, so its Cash is up by $425.

This scenario makes more sense when you combine the steps: **Over both steps, Inventory goes up and then down, and Cash is up by $225.**

The company bought some Inventory, turned it into a product, sold and delivered it, profited $300 from it, paid $75 in taxes, and now has $225 in additional Cash.

### 8. A Software-as-a-Service (SaaS) company bills customers upfront for an entire year of service and collects the cash before the contract begins.

**Walk me through the process for a $250 contract with a $50 delivery cost between January 1 and December 31 of the year. COMBINE the cash collection and revenue recognition.**

On January 1, Deferred Revenue and Cash both increase by $250 on the Balance Sheet, so the BS remains in balance. For the rest of the year, the company recognizes $250 in Revenue and $50 in Cost of Sales, so the combined steps look like this:

- **IS:** Revenue is up by $250, and COGS is up by $50, so Pre-Tax Income is up by $200, and Net Income is up by $150 at a 25% tax rate.
- **CFS:** Net Income is up by $150, and Deferred Revenue is initially up by $250 but decreases by $250 over the year, reversing this initial increase. So, on December 31, Cash is up by $150.
- **BS:** Cash is up by $150, so Total Assets are up by $150. On the L&E side, Deferred Revenue increases by $250 but then falls by $250, so on December 31, Equity is up by $150 due to the increased Net Income, and both sides balance.
- **Intuition:** The company has earned $200 over the year and paid $50 in taxes, so its Cash is up by $150. The Deferred Revenue changes are temporary and get reversed by the end of the year.

### 9. A company with 1000 shares issues 500 new shares worth $1.00 on January 1 to fund its business. Then, it decides to issue Dividends per Share of $0.10 to all its shareholders at the end of the year.

**Walk me through both steps SEPARATELY on the statements.**

In Step 1, the company issues 500 * $1.00 = $500 worth of new Equity. This does not appear on the Income Statement because it is a long-term action that does not affect shareholder income in the current period. Instead, it appears on the CFS under Cash Flow from Financing, boosting Cash by $500, and on the Balance Sheet, Cash and Equity are both up by $500.

In Step 2, the company issues 1500 * $0.10 = $150 of Dividends. These Dividends go to all the shareholders, not just the new ones!

- **IS:** No changes because Common Dividends do not appear on the IS.
- **CFS:** The Common Dividends are a negative $150 here, so Cash is down by $150.
- **BS:** Cash is down by $150 on the Assets side, and Equity is down by $150 on the L&E side, so both sides are down by $150, and the BS balances.
- **Intuition:** The company has distributed $150 to its shareholders, reducing its Cash and Equity capital.

### 10. A company issues $200 of Debt at a 10% interest rate. Walk me through the entire first year on the statements, including the initial issuance and the full interest payment. COMBINE both steps.

In the first step, nothing changes on the IS because Debt issuances only appear on the CFS. So, Debt on the L&E side increases by $200, and Cash increases by $200 on the Assets side to balance it.

In the second step, the company records Interest on this Debt. The combined steps are:

- **IS:** There's an interest expense of $200 * 10% = $20, so Pre-Tax Income is down by $20, and Net Income is down by $15 at a 25% tax rate.
- **CFS:** Net Income is down by $15, but the Debt issuance is a +$200 to cash flow, so Cash is up by $185.
- **BS:** Cash is up by $185, so Total Assets are up by $185. On the L&E side, Debt is up by $200, and Equity is down by $15 due to the Net Income reduction, so both sides are up by $185 and balance.
- **Intuition:** The company has raised $200 in new funding, paid $20 in interest on it, and received a $5 tax benefit, so its Cash is up by $185.

### 11. How does this change if, in addition to the 10% interest rate, the Debt now has a 20% principal repayment each year? Combine both steps and assume the principal repayment occurs on December 31.

The main difference is that 20% * $200 = $40 of the Debt must be repaid at year-end.

However, this principal repayment does not appear on the IS and is not tax-deductible, so very little changes. The Interest Expense stays the same because this principal is only repaid at the end of the year.

So, the IS stays the same, but on the CFS, there's an additional cash outflow for this $40 principal repayment. Therefore, Cash is up by $145 rather than $185.

On the BS, Cash is up by $145 on the Assets side. On the L&E side, Debt is up by $160, and Equity is down by $15 due to the Net Income reduction, so both sides are up by $145 and balance.

### 12. A company that follows U.S. GAAP signs a 10-year Operating Lease on January 1. It will pay $160 in Rent each year.

**Assuming a 5% Discount Rate, walk me through the financial statements over this entire year. For simplicity, you may "round" and assume the Present Value of the lease payments equals $1,200.**

Initially, the company records the Operating Lease Assets and Liabilities on its Balance Sheet ($1,200 on both sides), and then it records the $160 Rental Expense on its Income Statement.

The 5% Discount Rate means that the initial "Interest Expense" is 5% * $1,200 = $60, so the "Depreciation" equals $160 – $60 = $100. Since the lease payments are constant, the Lease Principal Repayment equals the Depreciation here:

- **IS:** Operating Expenses are up by $160 due to the Rent, so Pre-Tax Income falls by $160, and Net Income falls by $120 at a 25% tax rate.
- **CFS:** Net Income is down by $120, but Operating Lease Assets and Liabilities increase by $1,200, which offset each other. Then, they both decrease by $100, which is also an offset. So, Cash is down by $120 at the bottom.
- **BS:** On the Assets side, Cash is down by $120, and Operating Lease Assets are up by $1,100, so Total Assets are up by $980. On the L&E side, the Operating Lease Liabilities are up by $1,100, and Equity is down by $120, so the L&E side is up by $980, and both sides balance.
- **Intuition:** Cash is down by $120 because this is a simple $160 cash expense with $40 in tax savings. The Lease Asset and Lease Liability are created and then decrease by the same $100 (they will decrease by larger amounts over time).

### 13. Now walk through the same scenario, but under IFRS rather than U.S. GAAP (or pretend it is a Finance Lease under U.S. GAAP).

Under IFRS, the company records Depreciation of $1,200 / 10 = $120 per year and an initial Interest Expense of $1,200 * 5% = $60.

The Lease Principal Repayment = Cash Rental Expense – Interest Expense = $160 – $60 = $100.

- **IS:** Depreciation is up by $120, and the Interest Expense is up by $60, so Pre-Tax Income is down by $180, and Net Income falls by $135 at a 25% tax rate.
- **CFS:** Net Income is down by $135, but you add back the $120 of Depreciation and record the $1,200 additions to the Lease Assets and Liabilities (which offset each other). Also, you record a negative $100 for the Lease Principal Repayment. Cash is down by $115 at the bottom.
- **BS:** Cash is down by $115, and the Lease Assets are up by $1,080 due to the initial $1,200 increase and the $120 of Depreciation, so Total Assets are up by $965. On the other side, the Lease Liabilities are up by $1,100, and Equity is down by $135 due to the reduced Net Income, so both sides are up by $965 and balance.
- **Intuition:** Cash is down by $115 because the total Cash Lease Expense here is $160, but the company gets a tax benefit for the $180 of Lease Interest + Lease Depreciation that appears on the Income Statement. So, ($160) + $180 * 25% = ($115).

### 14. A company buys a factory for $200 using $200 of Debt. What happens, INITIALLY, on the statements?

- **IS:** No changes.
- **CFS:** There's no net change in cash because the $200 factory purchase counts as CapEx, which reduces cash flow, and the $200 Debt issuance is a cash inflow.
- **BS:** PP&E is up by $200, so the Assets side is up by $200, and Debt is up by $200, so the L&E side is up by $200, and the Balance Sheet stays balanced.
- **Intuition:** An Asset increases, a Liability increases to balance it, and there are no tax effects.

### 15. One year passes. The company pays 10% interest on its Debt, and it depreciates 10% of the factory. It also repays 5% of the Debt principal. What happens on the statements in this first year?

A 10% interest rate means $20 in Interest Expense, the 10% depreciation means $200 * 10% = $20 of Depreciation, and 5% * $200 = $10 of the Debt principal is repaid. So:

- **IS:** You record $20 in Interest and $20 in Depreciation, so Pre-Tax Income falls by $40, and Net Income falls by $30 at a 25% tax rate.
- **CFS:** Net Income is down by $30, but you add back the $20 of Depreciation and record $10 in Debt Principal Repayments, so Cash at the bottom is down by $20.
- **BS:** Cash is down by $20, and Net PP&E is down by $20, so the Assets side is down by $40. On the L&E side, Debt is down by $10 due to the principal repayment, and CSE is down by $30 due to the reduced Net Income, so both sides are down by $40 and balance.
- **Intuition:** Cash declines because of the Interest Expense and Debt Principal Repayment, offset by the tax savings from the Interest and Depreciation.

### 16. At the end of this first year, the company sells its factories for $220 and uses the proceeds to repay its remaining Debt principal after realizing there is little demand for its products.

**Walk through this step SEPARATELY from the previous two.**

Assume that the Net PP&E balance is $180, and the Debt is $190 because of changes in the previous step.

The Net PP&E selling price is $220, and its Book Value is $180, so we record a Gain of $40:

- **IS:** The Realized Gain of $40 increases Pre-Tax Income by $40 and Net Income by $30 at a 25% tax rate.
- **CFS:** Net Income is up by $30, but the $40 Gain is non-cash, so it's reversed in the CFO section. Then, in Cash Flow from Investing, the full sale proceeds of $220 are recorded as a cash inflow. The $190 Debt repayment is shown as a negative in Cash Flow from Financing. So, Cash at the bottom is up by $20.
- **BS:** Cash is up by $20, and Net PP&E is down by $180, so Total Assets are down by $160. On the L&E side, Debt is down by $190, and CSE is up by $30 because of the increased Net Income, so both sides are down by $160 and balance.
- **Intuition:** The Realized Gain would normally boost Cash by $30 after taxes. However, this full $30 does not flow into Cash because the Debt Repayment exceeds the reduction in Net PP&E by $10. As a result, Cash is up by $20 instead of $30.

### 17. Walmart purchases $200 of Inventory "on credit," sells it for $400, and records an additional $100 in Operating Expenses to support the sale.

**Walk me through ONLY Step 1 of this process with the Inventory purchase.**

Accounts Payable is not necessarily linked to a specific Income Statement line item in a case like this! It could just correspond to the company paying for Inventory on credit. In the first step:

- **IS:** No changes.
- **CFS:** Accounts Payable increases, boosting cash flow by $200, and Inventory also increases, reducing cash flow by $200; the changes offset each other, and Cash at the bottom stays the same.
- **BS:** Inventory on the Assets side is up by $200, and Accounts Payable on the L&E side is up by $200, so both sides are up by $200 and balance.
- **Intuition:** The company receives the parts and materials but has not paid for them in cash yet, so the Balance Sheet changes, but Cash stays the same.

### 18. Now walk through Step 2 – the sale and delivery of the products and the supplier payments – SEPARATELY from Step 1.

In this step, Walmart recognizes the additional Revenue, COGS, and OpEx:

- **IS:** Revenue is up by $400, COGS is up by $200, and OpEx is up by $100, so Pre-Tax Income is up by $100. Net Income is up by $75 at a 25% tax rate.
- **CFS:** Net Income is up by $75. The Change in Inventory is now +$200 because it falls by $200 in this step, and the Change in AP is now –$200 because it also falls in this step. They cancel each out, so the Cash at the bottom is up by $75.
- **BS:** Cash is up by $75 on the Assets side, and Inventory is now down by $200, so the Total Assets are down by $125 *in just this step*. On the L&E side, AP is now down by $200 *in just this step*, and Equity is up by $75 due to the increased Net Income, so both sides are down by $125, and the BS balances.
- **Intuition:** Cash is up by $75 because the company earns $100 in pre-tax profits and pays $25 in taxes. The Inventory and AP changes in this step are temporary and represent reversals of Step 1; if you combine the steps, Total Assets and Total Liabilities & Equity are up by $75 cumulatively.

Return to Top.
