# WEEK-2-PROJECT
# Maven Fuzzy Factory - Week 2 Analysis
## Business Performance & Customer Behaviour Analysis

### Project Overview
This project analyses the business performance and customer behaviour of Maven Fuzzy Factory, an online teddy bear store. The analysis uses website session and order data from 2012 to 2015.

### Objectives
1. Understand business growth in terms of revenue, orders and sessions over time.
2. Analyse where traffic comes from and how customers behave.
3. Compare conversion rates by device type and new vs repeat visitors.
4. Identify the top-performing products.
5. Provide recommendations to improve business performance.

### Datasets Used
| File | Description |
|---|---|
| website_sessions.csv | Website visits, traffic source, device, repeat status |
| orders_mav.csv | Orders, order value, order date |
| order_items.csv | Items in each order |
| products.csv | Product names and details |

### Tools Used
- Python
- Google Colab
- Pandas - Data cleaning and analysis
- Matplotlib & Seaborn - Data visualisation

### How To Run This Project
1. Open Google Colab: https://colab.research.google.com
2. Upload all CSV files to Colab.
3. Open the notebook: `Week_2_Maven_Fuzzy_Factory.ipynb`
4. Run all cells in order: Runtime > Run All
5. All charts and outputs will appear in the notebook.

### Key Findings
- **Total Revenue:** $1,938,509.75
- **Total Orders:** 32,313
- **Total Sessions:** 472,871
- **Average Order Value:** $59.99
- **Top Traffic Source:** Gsearch (Paid Google Search)
- **Higher Converting Device:** Desktop
- **Most Sessions:** New visitors (not repeat)
- **Top Product:** The Original Mr. Fuzzy

### Key Recommendations
1. Diversify traffic sources beyond gsearch.
2. Improve mobile checkout to increase mobile conversion.
3. Use email and retargeting to increase repeat visits.
4. Protect Mr. Fuzzy stock and bundle slower products with it.

### Files In This Project
- `Week_2_Maven_Fuzzy_Factory.ipynb` - Main analysis notebook
- `Week_2_Report.docx` - Word-style written report
- `README.md` - This file
- `*.csv` - Raw datasets


### Notes
- The drop in February 2015 is likely due to incomplete data for that month.
- Analysis covers data from 2012 to 2015.
