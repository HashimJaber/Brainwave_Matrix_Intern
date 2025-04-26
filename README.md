# Brainwave_Matrix_Intern
Project Overview
In this project, the goal was to analyze a large car sales dataset (more than 450,000+ rows) to extract important business insights using Power BI, SQL, and Excel.

The task included:
Data cleaning
Data preparation
Data modeling
Building visual dashboards
Sharing final insights

📂 Step 1: Dataset Received
File type: CSV file

Content: Sales records for used cars across different US states

Columns included:

Year, Make, Model, Trim, Body Type

Transmission, VIN, State, Odometer

Color, Interior, Seller, MMR, Selling Price, Sale Date

🛠️ Step 2: Data Cleaning and Preparation
At first, the data was too large for Excel (over 450k+ rows).
✅ So I decided to clean the data using SQL.

SQL Data Cleaning Steps:

Loaded data into a SQLite environment.

Checked for missing (NULL) values.

Deleted rows with missing critical fields (year, make, model, selling price).

Removed unnecessary columns (VIN, odometer, etc.).

Removed duplicate entries based on VIN.

Checked for corrupted or blank sales dates.

✅ After SQL cleaning, the dataset was much cleaner and ready for analysis.

🧹 Step 3: Further Cleaning in Excel 
Trimmed and formatted date columns.

Ensured uniform formatting (text, number, date).

Prepared a "cleaned" CSV file ready for Power BI import.

🟦 Step 4: Data Analysis and Modeling in Power BI
Imported the cleaned dataset into Power BI.

Built necessary calculated columns:

Extracted Month Name from Sale Date.

Created Month Number for correct sorting.

Created DAX Measures:

Total Sales (count)

Total Revenue (sum of selling prices)

Average Selling Price

Maximum Selling Price

Top Selling Month

Lowest Selling Month

✅ DAX was used to calculate and filter insights precisely.

🎨 Step 5: Dashboard Building
Built two main dashboard pages:

📄 Page 1: Sales Overview
KPI Cards:

Total Revenue

Average Selling Price

Max Selling Price

Pie Charts:

Sales by Transmission Type (Auto vs Manual)

Sales by Body Type (SUV, Sedan, etc.)

Bar Charts:

Top 10 Car Brands

Revenue by Car Model

📄 Page 2: State and Monthly Sales Trends
Map:

Sales by US States

Bar Chart:

Sales Revenue by State

Line Chart:

Sales Trend across Months

KPI Cards:

Top Selling Month

Lowest Selling Month

✅ Layout and grouping were designed to tell a clean business story.

🖌️ Step 6: Design and Polishing
Aligned all KPI cards and charts cleanly.

Standardized font sizes across visuals.

Applied a clean, soft theme for professional appearance.

Added clear chart titles for user understanding.

Created proper white space between visuals.

✅ Dashboard was made presentation-ready for GitHub and LinkedIn.

