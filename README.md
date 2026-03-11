Data Pipeline & Methodology

​1. Data Cleaning & Preprocessing
​The raw dataset (bike_buyers) underwent a rigorous cleaning process to ensure analytical integrity:
​Duplicate Removal: Identified and removed 26 duplicate rows to prevent skewed results.
​Data Standardization: * Updated Marital Status column: M ➔ Married, S ➔ Single.
​Updated Gender column: M ➔ Male, F ➔ Female.
​Data Formatting: Converted Income to currency format and removed unnecessary decimal points.
​Feature Engineering: Created a new Age Bracket column using nested logic to segment customers into:
​Adolescent (<31)
​Middle Age (31-54)
​Old (55+)

​2. Exploratory Data Analysis (EDA)
​Leveraged Pivot Tables to isolate key variables and calculate metrics:
​Income Analysis: Compared the average income of buyers vs. non-buyers, segmented by gender.
​Commute Analysis: Evaluated the correlation between commute distance and the likelihood of purchasing a bike.
​Demographic Segmentation: Analyzed purchase frequency across different age brackets and regions.

​3. Data Visualization & Dashboarding
​Built a professional Business Intelligence (BI) dashboard featuring:

​Clustered Column Charts: Visualizing income disparities between customer segments.
​Line Graphs: Highlighting the decline in purchase intent as commute distance increases.

​Interactive Slicers: Dynamic filters for Region, Education, and Marital Status that update all visualizations in real-time.

​Key Insights
​The "Middle Age" Factor: The highest conversion rates were found within the 31–54 age demographic.

​Commute Correlation: Customers with a commute of 0-1 miles are the primary buyers; intent drops significantly as distance exceeds 5 miles.

​Economic Profile: On average, bike buyers have a higher household income than non-buyers, particularly in the European and Pacific regions.

Tools & Technologies

​Software: Microsoft Excel

​Features Used: Pivot Tables, Pivot Charts, Slicers, Advanced Formulas (IF, VLOOKUP), Conditional Formatting.