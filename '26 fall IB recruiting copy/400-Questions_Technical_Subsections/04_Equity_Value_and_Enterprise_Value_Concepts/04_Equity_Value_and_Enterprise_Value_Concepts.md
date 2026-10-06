# Equity Value & Enterprise Value – Concepts

**Equity Value** is the value of **EVERYTHING** a company has (Net Assets, or Total Assets – Total Liabilities), but only to the **EQUITY INVESTORS** (the common shareholders).

**Enterprise Value** is the value of the company's **CORE BUSINESS OPERATIONS** (Net Operating Assets, or Operating Assets – Operating Liabilities), but to **ALL INVESTORS** (Equity, Debt, Preferred, and possibly others).

Enterprise Value **stays the same** even when a company's capital structure changes, while Equity Value changes (like the "total price" of a home vs. the "down payment" in the illustration on the left).

You use both metrics when valuing companies because one valuation methodology might produce the Equity Value, while another might produce the Enterprise Value, and you must be able to move between them.

To calculate Equity Value, multiply the company's Diluted Share Count by its Current Share Price. Equity Value is a fancier name for "Market Cap."

To move from Equity Value to Enterprise Value, subtract non-core Assets and add Liability and Equity lines that represent investor groups beyond the common shareholders (the Debt investors, Preferred Stock investors, etc.).

At a basic level, Enterprise Value = Equity Value – Cash + Debt + Preferred Stock + Noncontrolling Interests, but *many other items* could factor in.

You can also calculate "Implied" versions of both metrics that are based on the output of valuation analyses, but this section focuses on the "Current" versions based on current market prices.

- Interview Guide – Equity Value & Enterprise Value | Quiz Questions
- Core Financial Modeling – Equity Value & Enterprise Value Module

## 1. What do Equity Value and Enterprise Value MEAN? Don't explain how you calculate them – tell me what they mean!

**Equity Value** represents the value of **EVERYTHING** a company has (its Net Assets) but only to the **EQUITY INVESTORS** (i.e., the common shareholders).

**Enterprise Value** represents the value of the company's **CORE BUSINESS OPERATIONS** (its Net Operating Assets) but to **ALL INVESTORS** (Equity, Debt, Preferred, and possibly others).

## 2. That sounds complicated. What do these concepts mean in plain English? Can you give a real-life analogy?

If you buy a house for $500K with a $100K down payment, $500K is the Enterprise Value, and $100K is the Equity Value.

Enterprise Value does not change when the capital structure changes, so if you use $250K for the down payment, the Equity Value is now $250K, but the Enterprise Value is still $500K.

## 3. Why do you need both Equity Value and Enterprise Value? Can't you just value companies using one of them?

We need both because some valuation methodologies and analyses produce Equity Value for the output, but others produce Enterprise Value, so we must be able to move back and forth to make proper comparisons.

Enterprise Value has some advantages because it is **not** affected by capital structure changes (e.g., a company using less Debt and more Equity); people often call it "capital structure-neutral" for this reason.

However, Equity Value is still important because most valuations are conducted from the perspective of the **common shareholders**, who mostly care about what their shares are worth.

## 4. What is the difference between "Current" and "Implied" Enterprise Value? Can you give a real-life example to explain it?

"Current" means that you are calculating the Enterprise Value based on the company's current share price, share count, and Balance Sheet (subtract Cash, add Debt, add Preferred Stock, etc.).

"Implied" means that you are using a valuation methodology, such as the DCF, to value the company and determine what you think it should be worth.

Let's say that you search for houses in real life and find one you like with a "list price" of $500K. However, you research the area, similar properties, and demographic trends, and believe it's worth more like $450K.

$500K is the Current Enterprise Value of the house, and $450K is the Implied Enterprise Value.

## 5. What is the difference between Basic Equity Value and Diluted Equity Value?

Basic Equity Value is Common Shares Outstanding * Current Share Price, while Diluted Equity Value includes the impact of dilutive securities, such as options, warrants, restricted stock units (RSUs), and convertible bonds; it equals Diluted Shares Outstanding * Current Share Price.

Companies create and issue these dilutive securities to incentivize employees to stay at the company (and to raise funds, in the case of convertible bonds).

You factor in these dilutive securities via different methods, such as the Treasury Stock Method for options and warrants and the "If Converted" method for convertible bonds.

Diluted Equity Value more accurately measures what the company's Net Assets are worth to the common shareholders.

## 6. Let's say you have a company's Diluted Equity Value. How do you move from Equity Value to Enterprise Value?

At a basic level, Enterprise Value = Equity Value – Cash + Debt + Preferred Stock + Noncontrolling Interests, so you could say that in an interview and be fine.

The more technical answer is that you should take Equity Value and subtract Non-Operating Assets and add Liability & Equity lines that represent other investor groups beyond the common shareholders.

Examples of Non-Operating Assets include Cash, Investments, Equity Investments (Associate Companies), Assets Held for Sale, and Net Operating Losses.

Examples of L&E lines representing other investor groups include Debt, Preferred Stock, Underfunded Pensions, Noncontrolling Interests, and sometimes Leases (it's complicated).

## 7. Why do you subtract Equity Investments and add Noncontrolling Interests in the Enterprise Value calculation?

The short, simple answer is that Equity Investments (< 50% stakes the parent company owns in others) are considered **non-core assets**, and Noncontrolling Interests (when a parent owns more than 50% in another company, the portion it does *not* own) are considered **another "investor group"** (the minority shareholders of this other company).

The longer answer is that you also do this for **comparability purposes**. For example, let's say that Company A owns 30% of Company B and 75% of Company C.

Company A's EBITDA includes 0% of Company B's EBITDA but 100% of Company C's EBITDA due to accounting rules around the consolidation of the financial statements.

However, Company A's Equity Value reflects 30% of Company B and 75% of Company C.

Therefore, to use Enterprise Value with EBITDA in metrics such as TEV / EBITDA, you must adjust Enterprise Value to reflect 0% of Company B and 100% of Company C.

To do this, you subtract the Equity Investments, which represent 30% of Company B, and you add the Noncontrolling Interests, which represent the 25% of Company C that Company A does *not* own.

## 8. Can you explain the proper treatment of pensions in Enterprise Value?

Only Defined-Benefit Pension plans factor in because Defined-Contribution Plans do not appear on the Balance Sheet.

You should add the **Unfunded or Underfunded portion**, i.e., MAX(0, Pension Liabilities – Pension Assets), in the TEV bridge because *the employees* represent another investor group when they are promised future payments.

They agree to lower pay and benefits today in exchange for fixed payments once they retire, and the company must fund the pension and invest the funds appropriately.

If contributions into the pension plan are tax-deductible, you should multiply the unfunded portion by (1 – Tax Rate) in the Enterprise Value bridge.

## 9. Should you add Operating Leases in the Enterprise Value calculation? What about Finance Leases?

This is a question of **comparability** and the valuation multiples you're using. *Generally*, you should add Finance Leases because metrics such as EBITDA exclude the Finance Lease Interest and Finance Lease Depreciation.

If a metric **excludes** certain expenses, then the Enterprise Value paired with this metric should **add or include** the corresponding Liability.

Operating Leases are trickier because the accounting differs under U.S. GAAP vs. IFRS. Under U.S. GAAP, it's best **not to add them** because the corresponding expense is "Rent" on the Income Statement, which is deducted to calculate EBIT, EBITDA, etc.

If you add them to Enterprise Value, you must pair it with a metric like EBITDAR that adds back the Rental Expense.

Under IFRS, it's easiest **to add Operating Leases** because metrics like EBITDA exclude the full Lease Interest and Lease Depreciation from all Lease types, so the corresponding Lease Liabilities should be in Enterprise Value.

**NOTE: We do not view Leases as true "financial" items representing "outside investor groups"; this treatment is for comparability and ease of calculation.**

## 10. Can you give examples of company actions that affect Equity Value but NOT Enterprise Value, Enterprise Value but NOT Equity Value, and BOTH Enterprise Value and Equity Value?

This "compound question" tests how well you understand these concepts beyond simple definitions. There are many possible answers, but a few simple ones include:

- **Affects Equity Value But Not Enterprise Value:** A company issues $100 of Stock and lets it sit in Cash on its Balance Sheet (Net Operating Assets are unchanged).
- **Affects Enterprise Value But Not Equity Value:** A company issues $100 of Debt and uses it to buy a factory, boosting its Net PP&E (Net Operating Assets increase by $100).
- **Affects Both Equity Value and Enterprise Value:** A company issues $100 of Stock and uses it to buy a factory, boosting its Net PP&E (Net Operating Assets increase by $100, and Common Shareholders' Equity is also up by $100).

## 11. Could Equity Value ever be negative? What about Enterprise Value?
