# Customer Purchase Behavior Analysis: Bike Industry
## Project Overview
This end-to-end Excel project analyzes the demographic drivers behind bike purchases. By transforming a raw dataset of 1,000 customers into a polished, interactive KPI dashboard, I identified critical correlations between average income, commute distance, and age demographics. The final solution enables stakeholders to filter datasets by Region, Education, and Occupation, turning static rows of data into actionable business insights.

 
### Tools & Skills

 **Primary Tool:** Microsoft Excel
**Technical Skills:** Data Cleaning (Deduplication, Find & Replace), Data Modeling, Advanced Formulas (Nested IF Statements), Pivot Tables, Data Visualization, and Dashboard Design with Slicers.

### Project Workflow
**1. Data Cleaning & Preparation**
In the **"Working Sheet,"** I performed rigorous data linting to ensure the analysis was accurate:

**De-duplication:** Identified and removed duplicate records to maintain data integrity.

**Standardization:** Cleaned Marital Status (M/S → Married/Single) and Gender (M/F → Male/Female) columns to ensure professional, readable labels.

**Data Bucketing (The Age Bracket):** I utilized a nested IF formula to categorize individual ages into three logical segments:

Youth: < 31

Middle Age: 31–54

Old: 54+

**Currency Formatting:** Standardized the Income column to ensure mathematical consistency across all pivot calculations.

### 2. Data Analysis & Pivot Tables

 **I built dynamic summaries to answer high-level business questions:**

**Income Correlation**: Comparing the average income of bike buyers vs. non-buyers.

**Commute Patterns:** Analyzing if a longer commute distance acts as a barrier to bike sales.

**Demographic Volume:** Identifying which age bracket yields the highest conversion rate.

### 3. Interactive Dashboard
**The Dashboard serves as the final reporting layer for stakeholders:**

**Dynamic Visuals:** Clustered Bar Charts for income analysis and Line Graphs for age trends.

**User Interactivity:** Integrated Slicers for Region, Education, and Occupation, allowing for real-time data drilling.

### Key Insights
**Income Sweet Spot:** Bike buyers generally have a higher average income (approx. $60k+) compared to those who do not purchase.

**Target Demographic:** The Middle Age group (31-54) is the most profitable segment for the bike industry.

**The 5-Mile Rule:** There is a significant drop-off in purchases once a customer's commute exceeds 5 miles.

 ### Project Challenges & Solutions
**Challenge:** Raw "Age" data was too granular, creating cluttered and uninterpretable charts.

**Solution:** Implemented Data Bucketing using nested IF logic. This simplified 50+ unique data points into 3 actionable categories, making the trends immediately visible.

**Challenge:** Inconsistent labels (M/S/F) in the raw data caused "messy" chart legends.

**Solution:** Performed a bulk data transformation to standardize labels, ensuring the final dashboard was "Executive Ready."

 ### How to Use
**Download the File:** Click on BIKE Sales Analysis Project.xlsx in this repository and select the **Download** button.

**Open & Interact:** Launch the file in Excel and navigate to the Dashboard tab.

**Filter:** Use the Slicers on the right side of the dashboard to explore how different regions or occupations affect the sales trends.
