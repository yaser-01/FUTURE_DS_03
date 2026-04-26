# Bank Marketing Analysis & Funnel Dashboard

This repository contains a data science project focused on analyzing bank marketing campaigns and visualizing customer conversion funnels. The goal is to predict customer behavior and provide actionable insights through an interactive dashboard.

Repository Structure

* `bank-additional-full.csv`: The complete dataset including social and economic context attributes.
* `bank-additional.csv`: A 10% subset of the additional dataset for testing/prototyping.
* `bank-full.csv`: The full original dataset (older version).
* `bank.csv`: A 10% subset of the original dataset.
* `funnel-dashboard.html`: An interactive HTML dashboard visualizing the marketing funnel and conversion rates.

Project Overview

The project utilizes the **Bank Marketing Dataset** (typically from the UCI Machine Learning Repository). The dataset relates to direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe to a term deposit (variable `y`).

### Key Features Analyzed:
* **Customer Demographics:** Age, job, marital status, education.
* **Financial Status:** Default history, housing loan, personal loan.
* **Campaign Details:** Contact type, month, day of the week, duration of call.
* **Social/Economic Indicators:** Employment variation rate, consumer price index, etc.

How to Use

1.  **Data Exploration:** You can find the raw data in the `.csv` files.
2.  **Visualization:** Open `funnel-dashboard.html` in any web browser to view the interactive conversion funnel and campaign performance metrics.

Tools & Technologies
* **Data Processing:** Python (Pandas, NumPy)
* **Machine Learning:** Scikit-learn (implied for classification)
* **Visualization:** Plotly / Dash (exported as HTML)

Future Work
* Implement advanced classification models (XGBoost, Random Forest).
* Perform deep-dive feature engineering on social-economic factors.
* Automate the dashboard update process using GitHub Actions.
