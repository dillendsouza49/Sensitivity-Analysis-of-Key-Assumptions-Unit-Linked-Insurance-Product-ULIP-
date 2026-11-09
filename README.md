# Sensitivity Analysis of Key Assumptions – Unit-Linked Insurance Product (ULIP)

## Project Description

Sensitivity analysis of a Unit-Linked Insurance Product (ULIP) using Microsoft Excel to evaluate the impact of changes in key pricing, investment and valuation assumptions on product profitability and fund performance.

The objective is to understand how variations in Premium Amount, Sum Assured, Unit Fund Growth Rate and Non-Unit Fund Growth Rate influence the Expected Present Value (EPV) of Profit and Unit Fund Value at Maturity.

Each assumption was varied independently while keeping the remaining assumptions constant to assess its individual impact on the product's financial performance.

## Technologies Used

- **Microsoft Excel:** Financial modelling, calculations, sensitivity analysis and data visualisation.

### Key Concepts

- Actuarial Valuation
- Unit-Linked Insurance Products (ULIPs)
- Unit Fund and Non-Unit Fund
- Premium Allocation
- Fund Management Charges
- Expected Present Value (EPV) of Profit
- Surrender Value Analysis
- Sensitivity Analysis
- Investment Growth and Fund Accumulation

## Base Scenario – Model Inputs and Assumptions

The following assumptions were used to establish the base scenario for the ULIP valuation model.

| Parameter | Base Assumption |
|---|---|
| Mortality Table | Assumed for this type of product |
| Age at Entry | 40 years |
| Policy Term | 15 years |
| Premium | ₹100,000 |
| Initial Expenses | ₹10,000 |
| Sum Assured | Higher of Unit Fund Value or ₹1,500,000 |
| Renewal Expenses | ₹3,000 |
| Commission | Varying rates throughout the policy term |
| Premium Allocation | Varying allocation rates throughout the policy term |
| Bid-Offer Spread | 0.5% |
| Policy Fee | ₹1,000 |
| Annual Unit Fund Charge | 0.5% |
| Surrender Option | Available |
| Surrender Rates | Varying rates for each policy year |
| Unit Fund Growth Rate | 10% |
| Non-Unit Fund Growth Rate | 6% |

**Additional Model Inputs:**

- Commission rates for the entire policy term are incorporated in the Excel workbook.
- Premium allocation rates are also varied throughout the policy term and are provided in the workbook.
- Surrender rates for each policy year are included in the workbook to account for the surrender option.

These assumptions form the reference point for the sensitivity analysis. Individual assumptions were varied while keeping the remaining assumptions constant to evaluate their impact on profitability and fund performance.

## Features of the Project

- Analysis of four key assumptions affecting product performance:
  - Premium Amount
  - Sum Assured
  - Unit Fund Growth Rate
  - Non-Unit Fund Growth Rate
- Evaluation of the impact of different assumptions on EPV of Profit.
- Analysis of Unit Fund Value at Maturity under different scenarios.
- Identification of break-even points.
- Visualisation of profitability and fund accumulation using charts.
- Assessment of the relationship between investment growth assumptions and product profitability.

## Project Process

1. **Base Model:** Establish a ULIP valuation model using the specified base assumptions, including premium allocation, commission, expenses, fund charges and surrender rates.
2. **Sensitivity Analysis – Premium:** Vary premium amounts while keeping other assumptions constant to evaluate their impact on EPV of Profit and Unit Fund Value at Maturity.
3. **Sensitivity Analysis – Sum Assured:** Vary the sum assured to assess changes in mortality risk exposure and product profitability.
4. **Sensitivity Analysis – Unit Fund Growth Rate:** Change the unit fund growth rate to examine its impact on fund accumulation and insurer profitability.
5. **Sensitivity Analysis – Non-Unit Fund Growth Rate:** Vary the non-unit fund growth rate to assess its impact on the EPV of Profit.
6. **Profitability Assessment:** Calculate the resulting EPV of Profit under each scenario and identify break-even points where applicable.
7. **Visualisation and Interpretation:** Use charts to compare results and interpret the impact of each assumption on product performance.

## Key Findings

### 1. Premium Sensitivity

- The annual premium was varied from ₹20,000 to ₹200,000.
- Unit Fund Value at Maturity increases significantly from approximately ₹6.17 lakh to ₹64.71 lakh as the premium increases.
- EPV of Profit improves from a loss of ₹25,320 at a premium of ₹20,000 to a profit of ₹28,450 at a premium of ₹200,000.
- The product reaches its break-even point around the base premium of ₹100,000, where EPV of Profit is approximately ₹966.
- Premium amount demonstrates a strong positive relationship with both profitability and fund accumulation.

### 2. Sum Assured Sensitivity

- The sum assured was varied from ₹300,000 to ₹3,000,000.
- EPV of Profit decreases from ₹6,782 at a sum assured of ₹300,000 to a loss of ₹11,123 at ₹3,000,000.
- The break-even point occurs between ₹1,500,000 and ₹1,800,000.
- The relationship between sum assured and profitability is negative, as higher insurance coverage increases the insurer's mortality risk exposure and expected benefit payments.

### 3. Unit Fund Growth Rate Sensitivity

- The Unit Fund Growth Rate was varied from 2% to 20%.
- Unit Fund Value at Maturity increases from approximately ₹16.40 lakh at 2% growth to ₹78.82 lakh at 20% growth.
- EPV of Profit improves from a loss of ₹7,807 at 2% growth to a profit of ₹18,331 at 20% growth.
- The break-even point occurs around the base growth assumption of 10%, where EPV of Profit is approximately ₹966.
- Unit Fund Growth Rate has a strong positive impact on both fund accumulation and profitability.

### 4. Non-Unit Fund Growth Rate Sensitivity

- The Non-Unit Fund Growth Rate was varied from 2% to 11%.
- EPV of Profit decreases from ₹1,533 at 2% growth to ₹258 at 11% growth.
- The relationship between the Non-Unit Fund Growth Rate and profitability is negative.
- The product remains profitable throughout the range tested.
- Compared to the other assumptions analysed, changes in the Non-Unit Fund Growth Rate have a relatively limited impact on overall profitability.

### Overall Findings

The sensitivity analysis demonstrates that the profitability of the ULIP is highly dependent on premium levels, sum assured and investment growth assumptions.

- **Premium Amount:** Strong positive relationship with EPV of Profit and Unit Fund Value at Maturity.
- **Sum Assured:** Negative relationship with profitability due to increased insurance risk exposure and expected benefit payments.
- **Unit Fund Growth Rate:** Significant positive impact on fund accumulation and profitability.
- **Non-Unit Fund Growth Rate:** Relatively limited negative impact on profitability across the range analysed.

Overall, premium amount emerges as the strongest positive driver of profitability, while sum assured represents the strongest negative driver. Unit Fund Growth Rate also plays a significant role in determining long-term fund performance and profitability.

## What I Learned

- Understanding the financial structure of a Unit-Linked Insurance Product.
- Understanding the distinction between unit fund and non-unit fund components.
- Analysing the impact of premium allocation and commission structures on product profitability.
- Understanding the impact of fund growth assumptions on maturity fund value.
- Applying sensitivity analysis to evaluate changes in EPV of Profit.
- Assessing the impact of sum assured on mortality risk exposure and expected benefit payments.
- Understanding the role of policy charges, expenses and surrender assumptions in ULIP valuation.
- Identifying break-even points and interpreting profitability trends.

## Next Steps

- Extend the analysis by varying multiple assumptions simultaneously.
- Conduct scenario analysis under different investment and economic conditions.
- Explore the impact of mortality and surrender assumptions on profitability.
- Analyse the sensitivity of commission and premium allocation structures.
- Develop a more comprehensive ULIP profitability model incorporating additional actuarial and investment assumptions.

## How to Run the Project

1. Download or clone this repository.
2. Open the Excel workbook included in the repository.
3. Review the base assumptions, commission rates, premium allocation rates and surrender rates.
4. Review the valuation calculations for the unit fund and non-unit fund.
5. Modify the selected assumptions to explore different scenarios.
6. Observe the resulting changes in EPV of Profit, and Unit Fund Value at Maturity.

## Reference

The assumptions used in this valuation model and sensitivity analysis were based on the Institute of Actuaries of India (IAI) CM1B – Actuarial Mathematics Practice Examination Paper, November 2025.

**Additional Assumption:** Death benefits were assumed to be payable at the end of the year of death.
