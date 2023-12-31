# PyMovie_Data_Manipulation


## The script prepares the movie dataset through cleaning and transformation steps, making it ready for in-depth analysis or building predictive models. It's an essential part of the data analysis process, ensuring the reliability and accuracy of insights drawn from the data.

Missing Data Identification: Calculates and prints the percentage of missing values for each column to understand data completeness.

Data Type Correction: Addresses incorrect data types by converting most fields from object to appropriate types like float64, ensuring accurate numerical analysis.

Outlier Detection: Visualizes potential outliers in the 'gross' revenue column using boxplots and removes duplicate entries to maintain data integrity.

Data Sorting: Sorts movies based on their gross revenue to identify top and bottom performers.

Correlation Analysis: Utilizes Pearson, Kendall, and Spearman methods to calculate and visualize correlations between numerical features, providing insights into relationships such as between budget and gross revenue.

Categorical Conversion: Converts object type columns to categorical codes for better processing in analytical models.

Visualization: Employs various seaborn plots like regression and swarm plots to visualize relationships and distributions, facilitating a better understanding of the data.

