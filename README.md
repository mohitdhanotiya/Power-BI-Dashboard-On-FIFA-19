# Power-BI-Dashboard-On-FIFA-19

# Data Source
Dataset was downloaded from https://www.kaggle.com/code/ismailsefa/fifa-19-player-data-analysis-and-visualization-eda/notebook and then imported into power BI desktop.

### Table of Content
- Problem Statement
- Importing Data
- Data Preparation
- DAX
- Data Visualization

#### Problem Statement
Data analysis on FIFA 19 world cup.

##### Possible KPI's
Total Sales
Total discounts
Sales based on colour
Sales based on processor
Most rated brand
Importing Data
Dataset was downloaded from Kaggle and then import into Power BI desktop.

Data Preparation
Dataset was loaded into Power BI , Data was tranformed and loaded in Power Query editor.

Validation of each coloumn Data Type's
Removing Unnecessary Row's and Column's
DAX
Discount % = SUM('Flipkart Mobile - 2'[Discount Value(In Crore)])/SUM('Flipkart Mobile - 2'[Original Markup(In crore)])
Max Battery Capacity = MAX('Flipkart Mobile - 2'[battery_capacity])
Top 5 Sales = CALCULATE(SUM('Flipkart Mobile - 2'[Sales(In Crore)]),TOPN(5,T1,T1[Total Sales],DESC))
Max Rating = MAX('Flipkart Mobile - 2'[num_of_ratings])
Data Visualization
Stacked column chart
Scatter plot
Stacked bar chart
Heatmap
Tooltip
Drill through
Use of bookmarks and buttons

