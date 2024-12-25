# Lending Club Risk Analytics Case Study

> Analyzing loan data to identify key factors influencing defaults and minimize financial losses.

---

## Table of Contents
- [Objective](#objective)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)

---

## Objective

The case study's primary goals include:

- **Applying EDA** to a real-world business problem and deriving actionable insights.
- **Understanding risk analytics** in the context of the banking and financial services industry.
- Leveraging data to **minimize financial losses** while lending money.
- Enhancing skills in **visualization techniques** and selecting appropriate charts for real-world data.

### Dataset:
Historical loan data from **2007 to 2011** including:
- Loan Amount
- Interest Rate
- Term
- Grade
- Employment Length
- Outcome (e.g., Fully Paid, Charged-Off)

---

## Conclusions

### Key findings from the analysis:

#### Loan Amount and Interest Rates:
- Loan amounts between **$5,000 and $15,000** are common; popular clusters exist between **$10,000 and $20,000**.
- Charged-off loans have higher interest rates (**10%–17%**), with some exceeding **22%**, indicating higher risk.

#### Home Ownership and Default Behavior:
- Borrowers who **rent or mortgage** their homes are more likely to default than homeowners.
- Loans for **debt consolidation** and **credit card payments** have higher default rates.

#### Location and Employment Patterns:
- Default rates are higher in states like **California, Florida, New York, and Texas**, possibly due to larger populations.
- Borrowers with employment lengths of **0–1 year** or **10+ years** show higher default rates.

#### Loan Types and Terms:
- **36-month** term loans and loans with Grades **B** and **C** have the highest default rates.
- Higher grades (**D, E, F, and G**) correlate with higher default percentages.
- Borrowers with annual incomes between **$40,000 and $75,000** are most prone to defaults.

#### Key Indicators:
- High **loan-to-income ratios** and **payment-to-income ratios** are strong predictors of defaults.
- Borrowers with lower incomes struggle with large monthly payments, leading to higher failure rates.

#### Additional Insights:
- Loans for **small businesses** and **debt consolidation** carry higher interest rates (**15%–17%**) and higher risk.
- **Bankruptcy history** is not a significant differentiator between defaulters, suggesting other financial behaviors, like income stability and spending habits, are critical.

### Recommendations:
- Focus policies on:
  - Stable income verification.
  - Reasonable payment loads.
  - Stricter risk ratings for larger loans.
- Closely monitor loans for **debt consolidation**, **small businesses**, and **credit card payments**.

---

## Technologies Used

This project was implemented using Python with the following libraries:
- `pandas` - version 1.4.4
- `numpy` - version 1.23.3
- `matplotlib` - version 3.5.2
- `seaborn` - version 0.11.2

---

## Acknowledgements

- This project draws inspiration from Lending Club's mission to enhance **risk analytics**.
- Data was sourced from Lending Club's historical loan records.
