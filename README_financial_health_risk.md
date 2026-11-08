# Financial Health & Risk Analysis

A Power BI dashboard that screens publicly traded companies on financial strength and risk, with a drill-through view for any single company.

**Tools:** Power BI, Power Query, DAX, financial ratio analysis
**Data:** Kaggle, financial data of 4,400 public companies (annual and quarterly statements)

![Dashboard preview](images/dashboard_preview.png)

<!-- TODO: add a screenshot of your Financial Health Overview page at images/dashboard_preview.png -->

## Project Overview

This project evaluates company financial health using ratio analysis. It is built as a portfolio-wide screener that covers all companies in the dataset, with a drill-through page that opens the detail for one selected company.

## Business Questions

- Does a company appear financially strong?
- Can it meet its short-term obligations?
- Do its debt levels and profitability trends deserve attention?
- Which companies in the portfolio look strongest, and which look weakest?

## Dataset

The data comes from a public Kaggle dataset of about 4,400 publicly traded companies. It contains annual and quarterly balance sheets, income statements, and cash flow statements.

- Source: [add the Kaggle dataset link here]
- The raw data files are not included in this repository. Please download them from Kaggle.

## What I Did

1. **Data preparation (Power Query):** loaded and cleaned the statement files, set data types, and combined the tables needed for ratio calculations.
2. **Ratio analysis (DAX):** built measures for financial ratios in three areas: liquidity (can the company meet short-term obligations), leverage (how much debt it carries), and profitability.
3. **Screener design:** created a portfolio-wide view that compares all companies, with filters to narrow the list.
4. **Drill-through:** added a company detail page that opens from any company in the screener.

<!-- TODO: edit the steps so they match your real workflow -->

## Ratios Used

| Area | Ratio | What it tells you |
|---|---|---|
| Liquidity | [Current ratio] | Whether short-term assets cover short-term liabilities |
| Leverage | [Debt-to-equity] | How much of the company is financed by debt |
| Profitability | [Net profit margin] | How much of each dollar of revenue becomes profit |

<!-- TODO: replace the rows above with the ratios you actually built, and add or remove rows -->

## Dashboard Pages

| Page | What it shows |
|---|---|
| Financial Health Overview | Portfolio-wide screener comparing companies on the ratios above |
| Company Detail (drill-through) | [add: the ratios and trends for one selected company] |

<!-- TODO: add any other pages that exist in your .pbix file -->

## Key Insights

- [Add 3 to 5 findings with real numbers, for example how many companies fall into a weak liquidity or high leverage group]
- [Add any company or industry that stands out]

## Repository Contents

| File | Description |
|---|---|
| `financial_health_risk_dashboard.pdf` | PDF export of all dashboard pages |
| `images/` | Dashboard screenshots |
| `README.md` | This file |

<!-- TODO: rename the files above to match your real file names -->

## Power BI File

The Power BI report file (`.pbix`) is available on request. Message me on [LinkedIn](https://www.linkedin.com/in/waqar-ahmad-10735b276) and I will send it.

## How to Use

1. Open the PDF to see every dashboard page.
2. If you request the `.pbix` file, open it in Power BI Desktop and use the filters on the Overview page to narrow the company list.
3. Right-click a company and choose **Drill through** to open its detail page.
4. If Power BI asks for data, point it to the Kaggle files you downloaded.

## Limitations

- Ratios describe the reported financial statements only. They do not account for market conditions, management quality, or events after the reporting date.
- The data is a snapshot from a public dataset and may contain gaps or reporting differences between companies.
- This project is for learning and portfolio purposes. It is not investment advice.

## License and Copyright

© 2026 Waqar Ahmad. All rights reserved. The dashboard design, measures, and write-ups in this repository are shared for viewing and review. Please do not copy or redistribute them without permission.

## Author

**Waqar Ahmad**
Data Analyst | SQL, Power BI, Excel, Power Query
[LinkedIn](https://www.linkedin.com/in/waqar-ahmad-10735b276)

See also: [Credit Risk & Loan Default Analysis](add-your-credit-risk-repo-link-here)
