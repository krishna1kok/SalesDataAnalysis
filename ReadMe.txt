Sales Data Analysis
Overview
This project focuses on cleaning and analyzing sales data from a messy dataset. The workflow includes data wrangling, descriptive statistics, data visualization, and outlier detection.

Features
1. Data Cleaning:

	Removing unnecessary rows and columns.

	Renaming columns for clarity.

	Handling missing values.

2. Data Transformation:

	Reshaping the data into a long format using pd.melt.

	Extracting meaningful information like Segment, ShipMode, Year, and Country from columns.

3. Outlier Detection:

	Using the 3-Standard Deviation (3S) Rule.

	Using the Interquartile Range (IQR) method.

4. Data Visualization:

	Histogram of sales with outliers removed.

	Boxplot for segment-wise distribution of sales.

	Categorical data visualizations showing distribution of Segment and ShipMode.

	Horizontal bar chart of total sales by Segment and ShipMode.

Prerequisites
Python 3.6+

Libraries:
pandas
numpy
seaborn
matplotlib
openpyxl (for reading Excel files)

How to Use
1. Install dependencies:

	pip install -r requirements.txt

2. Run the code to:

	Clean and structure the data.

	Generate visualizations and insights.

Visualizations Included
	Histograms of sales data.

	Boxplots showing distribution across segments.

	Bar charts for categorical data analysis.