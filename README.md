# HR-Data-Analytics-Dashboard-using-Tableau

# Tools Used
# 1. Tableau Desktop
You used Tableau for:
Data connection (Excel/CSV)
Data cleaning (Tableau Data Interpreter)
Calculated fields
Charts & Dashboards
Filters, parameters, and color formatting

# 2. Microsoft Excel
You used Excel for:
Storing the dataset
Basic data preparation (cleaning columns, handling nulls)

# Charts, Visuals & Tableau Features Used
Below is a breakdown of every chart you used and where in Tableau it appears.

# 1. KPI Cards (Text Tables in Tableau)
You created 5 KPI cards:
Employee Count – 1,470
Attrition Count – 237
Attrition Rate – 16.12%
Active Employees – 1,233
Avg Age – 37

# Tableau features used:
Text Marks card
Calculated Fields
Attrition Rate = SUM(Attrition) / COUNT(Employees)
Active Employees = Total – Attrition
Formatting (background color, large font)
These KPIs help users quickly understand overall workforce health.

# 2. Pie Chart – Department-wise Attrition
Chart type: Pie Chart
Shows attrition distribution across departments:
Sales – 56.12%
R&D – 38.82%
HR – 5.06%

# Tableau techniques used:
Marks → Pie
Color legend for departments
Label formatting to show % and count
SUM(Attrition) as the measure
Department as dimension
This instantly highlights high-attrition departments.

# 3. Histogram / Bar Chart – Employees by Age Group
Chart type: Histogram
Bin Size selector is a Tableau Parameter.
Tableau features used:
Bins (Age → Create → Bin)
Histogram chart type
Parameter control to adjust bin size dynamically
Color gradient based on employee count
This shows that the highest workforce concentration is in the 30–35 age group.

# 4. Matrix Table – Job Satisfaction Rating
Chart type: Text Table (Heatmap Table)
Displays:
Job roles
Satisfaction ratings (1–4)
Count of employees per rating
Tableau features used:
Rows → Job Role
Columns → Job Satisfaction
Measure Values (count of employees)
Color encoding for heat intensity
This serves as a comparative table to understand satisfaction distribution across roles.

# 5. Horizontal Bar Chart – Education Field-wise Attrition
Chart type: Bar Chart
Shows which education fields contribute more to attrition:
Highest: Life Sciences, Medical
Moderate: Marketing
Lowest: HR
Tableau features:
Bars sorted by attrition count
Category on Y-axis, measure on X-axis
Color-coded bars
Useful for understanding the skill backgrounds affected most by attrition.

# 6. Donut Charts – Attrition Rate by Gender Across Age Groups
Chart type: Donut Chart (Pie Chart with Hole)
You created a series of donut charts, each representing an age range, showing:
Female attrition %
Male attrition %
How you built it in Tableau:
Pie chart
Dual axis:
Outer pie = male/female count
Inner circle = white circle to create the donut
Filtering by age bands
Separate dashboard containers for each donut
This reveals gender-specific attrition trends.

# 7. Gender Comparison (Ribbon Chart / Horizontal Bar)
Shows total attrition by:
Female → 87
Male → 150
Tableau features:
Bar Chart
Color-coded by gender
Tooltips showing total attrition
Helps identify attrition imbalance across genders.

# 8. Background Image and Styling
Tableau features used:
Custom dashboard background image
Floating containers for exact placement
Transparent backgrounds
Consistent color theme (Blue/Teal/Orange)
This gives the dashboard a polished, professional UI. 

# Dataset Used
Your dataset likely included columns such as:
Age
Department
Education Field
Job Role
Gender
Attrition (Yes/No)
Job Satisfaction
Monthly Income
Years at Company
Tableau pulled these fields to create:
Dimensions
Measures
Calculated Attrition %
Age bins

# Overall Insights from the Dashboard
1. Sales has the highest attrition (56%)
Indicates potential workload or management issues.

2. Workforce is mostly 30–35 years old
This age group needs focused engagement.

3. Male attrition is higher than female attrition
Possible reasons: job type, job pressure, or industry patterns.

4. Life Sciences & Medical fields show higher exit rates
Indicates domain-specific retention issues.

5. Mixed job satisfaction across roles
Some roles need HR intervention.
