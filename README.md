# ML_Basic_Exploratory-Data-Analysis-EDA
📁 Task: Data Exploration, Visualization & Pattern Discovery
✅ Tasks Completed:
Generated Summary Statistics:

Used .describe() to compute basic metrics like mean, median, standard deviation, min, and max for numerical features.

Visualized Distributions and Outliers:

Plotted histograms and boxplots for numeric columns (Age, Fare, etc.).

Identified skewness and outliers visually.

Removed outliers using IQR (Interquartile Range) method.

Explored Feature Relationships:

Created a pairplot to observe interactions among features.

Built a correlation heatmap to quantify the strength of relationships between numeric variables.

Analyzed Patterns & Trends:

Grouped passengers by Age bins and computed average survival rate.

Visualized the relationship between AgeBin and Survived using seaborn.barplot.

Derived Feature-Level Insights:

Young children had higher survival rates.

First-class passengers (Pclass = 1) were more likely to survive.

Higher fares were correlated with increased survival probability.

📊 Tools & Libraries Used:
pandas, numpy for data manipulation

matplotlib.pyplot, seaborn for visualization
