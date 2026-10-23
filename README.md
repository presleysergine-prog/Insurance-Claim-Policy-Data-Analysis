# Insurance Claim & Policy Data Analysis

An analysis of insurance claim and policy data for a fictional company, Press Insurance Pvt. Ltd., to uncover trends in claims, policy types, and risk.

## Objective

Understand how claims and policies relate, and identify what drives claim volume and cost, to support better underwriting and business decisions.

## Tools Used

- **Microsoft SQL Server**: storing the raw data
- **Power Query**: data cleaning and transformation
- **Power BI Desktop**: dashboards and visualization

## Dataset

- **Source:** Provided as part of the Complete Data Analyst Bootcamp (Udemy)
- **Size:** 10,000 customers (5,000 male, 5,000 female)
- **Key fields:** PolicyNumber, ClaimNumber, CustomerID, PolicyType, PremiumAmount, CoverageAmount, ClaimAmount, ClaimStatus, ClaimDate, PolicyStartDate, PolicyEndDate, Age, Age Group, Gender, Active/Inactive

## Approach

1. **Data storage:** imported the raw CSV file into Microsoft SQL Server
2. **Data loading:** connected Power BI Desktop to SQL Server and loaded the data
3. **Data cleaning:** cleaned and transformed the data in Power Query, including adding Age Group and Active/Inactive columns
4. **Analysis:** compared claim volume and amounts across policy types, age groups, and claim statuses
5. **Visualization:** built a Power BI dashboard of the key metrics, with filters for policy, claim, and customer

## Dashboard Preview

<img width="1320" height="760" alt="Image" src="https://github.com/user-attachments/assets/879e08ec-4468-4909-93fe-61cdb484c509" />

## Power BI Workspace

<img width="4032" height="2268" alt="Image" src="https://github.com/user-attachments/assets/9c95e2a7-3ba4-451e-a70e-11ae0ace6e15" />

## Key Findings

- Total claims (16.90M) were about 2.8x total premiums collected (5.97M).
- Travel generated the highest premium (2.5M, ~42% of total), while Home was lowest (0.6M).
- Rejected claims were the largest group (~4.4K), ahead of settled (~3.4K) and pending (~2.3K).
- Adults accounted for the highest claim amount (8.8M, ~52%); Young Adults the lowest (1.7M).
- About 25% of policies (2.51K) are inactive, a retention risk worth investigating.

## Summary

Press Insurance collected 5.97M in premiums but faced 16.90M in claims, so claim payouts are well above income. Travel is the company's biggest premium source, while Adults generate the most claim cost. Nearly half of all claims were rejected, and a quarter of policies are inactive.

## Recommendations

- **Review pricing:** claims far exceed premiums, so premium rates may need a closer look, starting with the highest-claim segments.
- **Look into rejected claims:** with about 44% of claims rejected, find out why. Reasons could include documentation gaps or policy exclusions.
- **Target the Adult segment:** this group drives the most claim cost, so it is the best place to focus risk management.
- **Improve retention:** reach out to inactive policyholders to bring back some of the 25% who have lapsed.

## Files in This Repository

| File | Description |
| --- | --- |
| `InsuranceData.csv` | Raw insurance dataset |
| `insurance-cleaned-data-set.pbix` | Power BI dashboard file |

## Author

**Presley Ufuoma Sergine**

Data Analyst | Lagos, Nigeria

[LinkedIn](https://www.linkedin.com/in/presley-sergine-b9176343a) | presleysergine23@gmail.com 
