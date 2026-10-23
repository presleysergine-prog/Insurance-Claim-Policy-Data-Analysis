<h1 align="center"> Insurance Claim & Policy Data Analysis</h1>
<p align="center">
  <i>Uncovering trends in claims, policy types, and risk for Press Insurance Pvt. Ltd.</i>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Customers-10%2C000-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Total%20Claims-16.90M-red?style=flat-square"/>
  <img src="https://img.shields.io/badge/Total%20Premiums-5.97M-brightgreen?style=flat-square"/>
  <img src="https://img.shields.io/badge/Inactive%20Policies-25%25-orange?style=flat-square"/>
</p>
<p align="center">
  <img width="90%" alt="Dashboard" src="https://github.com/user-attachments/assets/879e08ec-4468-4909-93fe-61cdb484c509" />
</p>
[!NOTE]
This project analyzes a fictional company, Press Insurance Pvt. Ltd. The data is sample data from a bootcamp and does not represent real customers.

## 📑 Table of Contents

	•	🎯 Objective

	•	🧰 Tools Used

	•	📂 Dataset

	•	🔄 Approach

	•	📊 Dashboard Preview

	•	🔍 Key Findings

	•	📝 Summary

	•	✅ Recommendations

	•	📁 Files in This Repository

	•	👤 Author

## 🎯 Objective

Understand how claims and policies relate, and identify what drives claim volume and cost, to support better underwriting and business decisions.

## 🧰 Tools Used

## Tool	Purpose
🗄️ Microsoft SQL Server	Storing the raw data
🔧 Power Query	Data cleaning and transformation
📊 Power BI Desktop	Dashboards and visualization

## 📂 Dataset

Detail	Info
Source	Complete Data Analyst Bootcamp (Udemy)
Size	10,000 customers (5,000 male, 5,000 female)

<details>
<summary>📋 <b>Key fields</b> (click to expand)</summary>
<br>

Policy & Coverage	Claims,	Customer
PolicyNumber,	ClaimNumber	CustomerID,
PolicyType,	ClaimAmount,	Age,
PremiumAmount,	ClaimStatus, Age Group,
CoverageAmount,	ClaimDate,	Gender,
PolicyStartDate,		Active/Inactive,
PolicyEndDate		

</details>

## 🔄 Approach

flowchart LR
    A[🗄️ Raw CSV<br/>SQL Server] --> B[🔌 Load<br/>Power BI]
    B --> C[🔧 Clean<br/>Power Query]
    C --> D[🔎 Analyze<br/>Claims & Policies]
    D --> E[📊 Dashboard<br/>Power BI]

	1.	Data storage: imported the raw CSV file into Microsoft SQL Server
	2.	Data loading: connected Power BI Desktop to SQL Server and loaded the data
	3.	Data cleaning: cleaned and transformed the data in Power Query, including adding Age Group and Active/Inactive columns
	4.	Analysis: compared claim volume and amounts across policy types, age groups, and claim statuses
	5.	Visualization: built a Power BI dashboard of the key metrics, with filters for policy, claim, and customer

## 📊 Dashboard Preview

<p align="center">
  <img width="100%" alt="Dashboard Preview" src="https://github.com/user-attachments/assets/879e08ec-4468-4909-93fe-61cdb484c509" />
</p>
<details>
<summary>🖥️ <b>Power BI Workspace</b> (click to expand)</summary>
<br>
<p align="center">
  <img width="100%" alt="Power BI Workspace" src="https://github.com/user-attachments/assets/9c95e2a7-3ba4-451e-a70e-11ae0ace6e15" />
</p>
</details>

## 🔍 Key Findings

	Finding

💸	Total claims (16.90M) were about 2.8x total premiums collected (5.97M).

✈️	Travel generated the highest premium (2.5M, ~42% of total), while Home was lowest (0.6M).

❌	Rejected claims were the largest group (~4.4K), ahead of settled (~3.4K) and pending (~2.3K).

🧑	Adults accounted for the highest claim amount (8.8M, ~52%); Young Adults the lowest (1.7M).

😴	About 25% of policies (2.51K) are inactive, a retention risk worth investigating.

## 📝 Summary

Press Insurance collected 5.97M in premiums but faced 16.90M in claims, so claim payouts are well above income. Travel is the company's biggest premium source, while Adults generate the most claim cost. Nearly half of all claims were rejected, and a quarter of policies are inactive.

## ✅ Recommendations

[!IMPORTANT]
Claims far exceed premiums, which makes pricing and claim handling the top priorities.

	•	💰 Review pricing: claims far exceed premiums, so premium rates may need a closer look, starting with the highest-claim segments.

	•	🔎 Look into rejected claims: with about 44% of claims rejected, find out why. Reasons could include documentation gaps or policy exclusions.

	•	🎯 Target the Adult segment: this group drives the most claim cost, so it is the best place to focus risk management.

	•	🤝 Improve retention: reach out to inactive policyholders to bring back some of the 25% who have lapsed.

## 📁 Files in This Repository

File	Description

* 📄 InsuranceData.csv	| Raw insurance dataset |

* 📊 insurance-cleaned-data-set.pbix | Power BI dashboard file |

👤 Author

Presley Ufuoma Sergine
Data Analyst | Lagos, Nigeria

<p>
  <a href="https://www.linkedin.com/in/presley-sergine-b9176343a">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:presleysergine23@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

<p align="center">
  ⭐ If you found this project useful, consider giving it a star! ⭐
</p>