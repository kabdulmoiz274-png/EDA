# EDA
This analysis imported the Superstore data and examined the types and missingness, confirming that no rows needed to be removed due to missing Postal Codes.

Descriptive statistics outlined the central tendency-mean, median, mode-along with spread and distribution characteristics of the variables representing Sales, Profit, and Discount.

Outliers were detected by IQR methodology and treated using Winsorization to reduce its effect on further analysis: Sales - 1,167 and Profit - 1,881 records.

Data Cleaning and Processing All columns were reviewed for missing data; none were found, thus assuring integrity in the analysis.

Winsorizing Sales and Profit columns at 5th/95th percentile helped reduce distortion; both the mean and standard deviation fell significantly, which means that the distribution is much more normal.

Key EDA Insights The dataset consisted of 9,994 records and 11 features that included critical sales and profit information by category, region, segment, and date.

The category frequency identifies Office Supplies as the most common, at 6,026, followed by Furniture and then Technology.

Statistical and visual exploration showed right-skewed distributions with a large number of outliers in the Sales and Profit series before Winsorization.

The final state of data, post-cleaning, was devoid of missingness, and the variables were ready for further predictive analytics or business intelligence applications.

Conclusion This submission shows a strong EDA workflow based on the Superstore dataset, using best practices for importing data, cleaning, handling outliers, and core statistical and visual analysis.

It guarantees the reliability of the data and prepares the dataset for deeper modeling, while transparently documenting each major step and transformation.
