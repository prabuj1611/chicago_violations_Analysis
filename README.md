# 🏛️ Chicago Ordinance Violations Analysis 📊

📖 Introduction
This project analyzes building-related ordinance violations in Chicago, Illinois, using the chicago_violations.csv dataset. The dataset spans from 2008 to the 2024 and provides insights into violation patterns across different city wards. Through this analysis, we explore data wrangling, filtering, statistical analysis, and data visualization techniques to uncover key patterns and trends.

🔍 Analysis Overview

1️⃣ Dataset Exploration
Loaded the dataset using pandas and examined its structure.
Found [rows] rows and [columns] columns.
Filtered data for a randomly chosen ward and identified 3 key facts about it.

2️⃣ Missing Data Handling
Identified missing values and converted blanks into NA.
Calculated the percentage of complete cases.
Generated a summary table of missing values per column.

3️⃣ Date-Time Analysis
Calculated CityDelay by measuring the delay between violation and hearing dates.
Counted violations issued on my birthday and analyzed the most common case disposition.

4️⃣ Exploratory Data Analysis (EDA)
Classified Ward as a categorical variable.
Analyzed correlation between Imposed Fine and Admin Costs.
Identified the most common street type and analyzed violation descriptions.

5️⃣ Time Series Insights
Examined the yearly trend of average Imposed Fines.
Investigated reasons for unusual patterns, such as lower fines in 2024.

6️⃣ Feature Engineering
Removed irrelevant columns like ID and Docket Number.
Created a new Season column based on the Violation Date.

7️⃣ Data Visualization
Created barplots and histograms to visualize seasonal variation, case dispositions, and violation descriptions.
Investigated seasonal patterns and possible reasons behind variations.

8️⃣ Focused Analysis
Filtered data to include the top 5 most common Violation Descriptions.
Simplified lengthy descriptions for better visualization.
Analyzed the mean Imposed Fine for these categories.

🛠️ Tech Stack & Tools
Python: pandas, matplotlib, seaborn
Libraries: numpy, datetime, scipy.stats
Environment: Jupyter Notebooks

🧠 Key Insights
Fines imposed varied significantly by Violation Description and Season.
The correlation between Admin Costs and Imposed Fine was weak, suggesting independent cost structures.
Delays (CityDelay) varied widely, with some outliers indicating significantly delayed hearings.
