# Clinical-Trials-Analysis
A full end-to-end intermediate/advanced data analytics project for Pharma R&amp;D, Safety, Regulatory, and Commercial operations.
Project Overview

### This project simulates real-world pharmaceutical analytics workflows using four interconnected datasets:

Clinical Trials

Adverse Events (Drug Safety)

FDA Drug Approvals

Pharma Sales & Marketing

Using Python, Pandas, and Matplotlib, the project performs:

Deep exploratory data analysis (EDA)

KPI calculations across R&D, Safety, Regulatory & Commercial domains

Cross-dataset integration (Trials → Approval → Safety → Sales)

Business insights for decision-making

This project mirrors the analytical work done inside pharmaceutical companies and builds a strong portfolio piece for data analysis roles.


###Business Problem Statement

Pharmaceutical companies operate across multiple domains:

R&D (Clinical Trials)

Drug Safety (Pharmacovigilance)

Regulatory Affairs (FDA Approvals)

Commercial Operations (Sales & Marketing)

Executives want to understand:

Which diseases get the most R&D investment?

Where trials face delays or enrollment challenges?

Which drugs have the highest safety risks?

How approval trends differ across companies and drug types?

How product sales vary across regions?

Which products are generating high revenue despite safety concerns?

What the full lifecycle looks like from clinical trial → approval → safety → commercial performance?

This project answers all these questions using analytics.


###Datasets Used
Dataset	Description
clinical_trials.csv	Trial phases, diseases, sponsors, enrollment, durations
adverse_events.csv	Post-market safety reports
fda_approvals.csv	FDA regulatory approvals
pharma_sales.csv	Regional sales, revenue, and marketing spend

These synthetic datasets were designed to reflect real industry structure.


### Analysis Performed
#### A) Clinical Trials Analysis
KPIs

Trials per phase, disease, country, sponsor

Study duration (days)

Enrollment distribution

Sponsor performance

Interventional vs observational split

Key Analysis

Which diseases dominate R&D?

How long do trials take by phase?

Which sponsors conduct most trials?

Country-level R&D hotspots

Outliers in duration or enrollment

#### B) Drug Safety (Adverse Events) Analysis
KPIs

Adverse event count per drug

Serious vs non-serious AE ratio

Reaction frequency

Age & gender distribution

Safety risk index (advanced)

Key Analysis

Which drugs trigger the most AE reports?

What reactions are most common?

Which demographic groups are high-risk?

Which drugs have the highest serious AE rate?

#### C) FDA Approvals Analysis
KPIs

Approvals per year

Biologic vs small-molecule split

Company approval performance

Indication trends

Key Analysis

Long-term approval trends

Top performing companies

Regulatory shifts (e.g., rise of biologics)

#### D) Pharma Sales & Marketing Analysis
KPIs

Revenue by region

Units sold by product

Monthly revenue trend

Marketing ROI

Key Analysis

Best performing regions

Best selling products

Month-over-month revenue patterns

Marketing efficiency scoring

#### E) Cross-Dataset Integrated Analysis (Advanced)

(Most important portfolio section)

Lifecycle View: Trial → Approval → Safety → Sales

Do high-enrollment trials lead to successful approvals?

Do recently approved drugs have higher safety signals?

Do drugs with more AEs still generate high revenue?

Which companies dominate across R&D, approvals, and commercial?

Advanced Outputs

Portfolio Risk Heatmap

Company 360° Scorecard

R&D ROI Indicators

Drug-level Safety vs Revenue scatter matrix


#### How to Run the Project
1. Clone the repository
git clone https://github.com/mansaram90/pharma-analytics-project.git
cd pharma-analytics-project

2. Install dependencies
pip install -r requirements.txt

3. Launch Jupyter Notebook
jupyter notebook

4. Open the notebook
notebooks/pharma_data_analysis_project.ipynb


#### Skills Demonstrated

-Python Data Analysis
-pandas (groupby, merges, cleaning, datetime analysis)
-Data Visualization (Matplotlib)
-KPI development & business reasoning
-Cross-functional analytics (R&D + Safety + Sales)
-Domain understanding of pharma lifecycle
-Project structuring & documentation
-GitHub portfolio building

#### Conclusion

This project simulates real pharma analytics tasks and demonstrates your ability to:

Analyze complex datasets

Build insights that support business decisions

Work across R&D, safety, regulatory, and commercial domains

Communicate findings clearly with visualizations

It is a perfect intermediate → advanced portfolio project for roles in:

Data Analysis

Healthcare Data Science

Pharma/biotech analytics

Business Intelligence

Real-World Evidence (RWE)
