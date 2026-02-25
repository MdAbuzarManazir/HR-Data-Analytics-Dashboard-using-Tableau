# HR-Data-Analytics-Dashboard-using-Tableau

# 1. Tools Used:
# 1.1 Tableau Desktop
Tableau used for:

1. Data connection (Excel/CSV)

2. Data cleaning (Tableau Data Interpreter)

3. Calculated fields

4. Charts & Dashboards

5. Filters, parameters, and color formatting

# 1.2 Microsoft Excel
Excel used for:

1. Storing the dataset

2. Basic data preparation (cleaning columns, handling nulls)

# 2. Charts, Visuals & Tableau Features Used:
Below is a breakdown of every chart you used and where in Tableau it appears.

# 2.1 KPI Cards (Text Tables in Tableau)
Created 5 KPI cards:

1. Employee Count – 1,470

2. Attrition Count – 237

3. Attrition Rate – 16.12%

4. Active Employees – 1,233

5. Avg Age – 37

# 2.2 Tableau features used

1. Text Marks card

2. Calculated Fields:

- Attrition Rate = SUM(Attrition) / COUNT(Employees)

- Active Employees = Total – Attrition

3. Formatting (background color, large font)

These KPIs help users quickly understand overall workforce health.

# 2.3 Pie Chart – Department-wise Attrition

1. Chart type: Pie Chart

2. Shows attrition distribution across departments:

- Sales – 56.12%

- R&D – 38.82%

- HR – 5.06%

# 2.4 Tableau techniques used

1. Marks → Pie

2. Color legend for departments

3. Label formatting to show % and count

4. SUM(Attrition) as the measure

5. Department as dimension

This instantly highlights high-attrition departments.

# 2.5 Histogram / Bar Chart – Employees by Age Group

1. Chart type: Histogram

2. Bin Size selector is a Tableau Parameter.

3. Tableau features used:

- Bins (Age → Create → Bin)

- Histogram chart type

- Parameter control to adjust bin size dynamically

- Color gradient based on employee count

This shows that the highest workforce concentration is in the 30–35 age group.

# 2.6 Matrix Table – Job Satisfaction Rating

1. Chart type: Text Table (Heatmap Table)

2. Displays:

- Job roles

- Satisfaction ratings (1–4)

- Count of employees per rating

3. Tableau features used:

- Rows → Job Role

- Columns → Job Satisfaction

- Measure Values (count of employees)

- Color encoding for heat intensity

This serves as a comparative table to understand satisfaction distribution across roles.

# 2.7 Horizontal Bar Chart – Education Field-wise Attrition

1. Chart type: Bar Chart

2. Shows which education fields contribute more to attrition:

3. Highest: Life Sciences, Medical

4. Moderate: Marketing

5. Lowest: HR

6. Tableau features:

- Bars sorted by attrition count

- Category on Y-axis, measure on X-axis

- Color-coded bars

Useful for understanding the skill backgrounds affected most by attrition.

# 2.8 Donut Charts – Attrition Rate by Gender Across Age Groups

1. Chart type: Donut Chart (Pie Chart with Hole)

2. Created a series of donut charts, each representing an age range, showing:

- Female attrition %

- Male attrition %

3. How you built it in Tableau:

- Pie chart

4. Dual axis:

- Outer pie = male/female count

- Inner circle = white circle to create the donut

- Filtering by age bands

S- eparate dashboard containers for each donut

This reveals gender-specific attrition trends.

# 2.9 Gender Comparison (Ribbon Chart / Horizontal Bar)

1. Shows total attrition by:

- Female → 87

- Male → 150

2. Tableau features:

- Bar Chart

- Color-coded by gender

- Tooltips showing total attrition

Helps identify attrition imbalance across genders.

# 3. Background Image and Styling:

1. Tableau features used:

- Custom dashboard background image

- Floating containers for exact placement

- Transparent backgrounds

- Consistent color theme (Blue/Teal/Orange)

This gives the dashboard a polished, professional UI. 

# 4. Dataset Used:

1. Your dataset likely included columns such as:

- Age

- Department

- Education Field

- Job Role

- Gender

- Attrition (Yes/No)

- Job Satisfaction

- Monthly Income

- Years at Company

- Tableau pulled these fields to create:

- Dimensions

- Measures

- Calculated Attrition %

- Age bins

# 5. Overall Insights from the Dashboard:

1. Sales has the highest attrition (56%):
   
- Indicates potential workload or management issues.

2. Workforce is mostly 30–35 years old:

- This age group needs focused engagement.

3. Male attrition is higher than female attrition
   
- Possible reasons: job type, job pressure, or industry patterns.

4. Life Sciences & Medical fields show higher exit rates

- Indicates domain-specific retention issues.

5. Mixed job satisfaction across roles

- Some roles need HR intervention.

# Completed, thank You........
