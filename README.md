# -Tech-_-Crime-Data-Cleaning-And-Analysis-
Krishiv Brahmbhatt (KU2407U540)
Objective of the Datasets:

1. Auto Theft Dataset:
   - Objective:
     The dataset aims to analyze trends in motor vehicle theft across different regions over time. It provides insights into the number of vehicles stolen and recovered, helping law enforcement agencies, policymakers, and researchers understand patterns in auto theft, the effectiveness of recovery efforts, and regional differences in crime rates.
   - Potential Use Cases:
     - Evaluating the effectiveness of anti-theft measures.
     - Identifying regions with higher auto theft incidents.
     - Understanding seasonal or yearly fluctuations in auto theft.

2. Victims of Rape Dataset:
   - Objective:
     This dataset seeks to track and analyze incidents of rape reported in various regions over time, with demographic breakdowns of victims by age group. It provides crucial data for understanding the prevalence of sexual violence, identifying vulnerable groups, and informing policies aimed at prevention and support.
   - Potential Use Cases:
     - Analyzing trends in rape cases over the years.
     - Identifying demographic patterns of victims (e.g., age groups most affected).
     - Informing social policy and law enforcement strategies to reduce sexual violence.
     - Supporting advocacy groups and policymakers in targeted interventions.

These datasets are valuable for studying crime trends and designing evidence-based strategies to enhance public safety and support victims.

Tools and Libraries Used in the Python Code:

1. Pandas (pd):
   - Purpose: Data manipulation and analysis.
   - Usage in Code:
     - Reading CSV files using pd.read_csv().
     - Grouping data with groupby() to aggregate values by Year.
     - Summing columns with sum() to get total thefts and rape cases.

2. NumPy (np):
   - Purpose: Numerical computing library for efficient handling of arrays.
   - Usage in Code:
     - Converting grouped indices to arrays (np.array()).
     - Used in positioning bars in the bar chart for consistent spacing.

3. Matplotlib (plt):
   - Purpose: Visualization library for creating static, interactive, and animated plots.
   - Usage in Code:
     - Creating bar charts with plt.bar() for visualizing stolen vs. recovered vehicles.
     - Plotting line charts with plt.plot() to show the trend of rape cases over time.
     - Adding labels, titles, legends, and grid lines to enhance plot readability.

Summary of Functions and Methods:
- pd.read_csv(): Reads CSV files into DataFrames.
- groupby(): Groups data based on specified columns.
- sum(): Aggregates data by summing column values.
- np.array(): Converts data to NumPy arrays for numerical operations.
- plt.bar(): Creates bar charts.
- plt.plot(): Creates line plots.
- plt.xlabel(), plt.ylabel(): Sets axis labels.
- plt.title(): Adds a title to the plot.
- plt.legend(): Displays the legend.
- plt.tight_layout(): Adjusts layout for better spacing.

These libraries form the backbone of data analysis and visualization in Python, making it easy to extract insights from datasets.
