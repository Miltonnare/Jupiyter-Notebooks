## **Data Analysis of Iris Dataset**

## **Overview**

This repository contains a detailed analysis of the **Iris dataset** using Python and various data analysis tools. The dataset has been explored, cleaned, analyzed, and visualized using popular libraries such as Pandas, Matplotlib, and Seaborn.

The key insights derived from the dataset include basic statistics, group-wise analysis, and visualizations that highlight trends and relationships between various features.

## **Dataset**

The dataset used for this analysis is the Iris dataset, a well-known dataset in machine learning. It contains 150 records, with 4 features (sepal length, sepal width, petal length, and petal width) for each flower of 3 different species:

Setosa

Versicolor

Virginica

## Columns:

*sepal_length: Length of the sepal in cm*

*sepal_width: Width of the sepal in cm*

*petal_length: Length of the petal in cm*

*petal_width: Width of the petal in cm*

*species: The species of the iris plant*

## Steps Involved

*1. Data Loading and Inspection*
The data was loaded into a Pandas DataFrame. We performed an initial inspection using the .head() method to check the first few rows of the data.

*2. Data Exploration*
We explored the structure of the dataset by checking the data types and looking for missing values.

Missing values, if any, were handled by either filling them with appropriate values or dropping them.

*3. Statistical Summary*
The basic statistical details, including the mean, median, and standard deviation, were calculated using .describe() for the numerical columns. This provided insights into the distribution of the data.

*4. Group-wise Analysis*
We grouped the dataset by the species column and calculated the mean for each species across the numerical features (sepal length, sepal width, petal length, petal width). This helped us understand the average size of each feature for each flower species.

*5. Visualization*
The following visualizations were created to gain better insights:

*Line Chart: A trend over time, e.g., sepal length over different measurements.*

*Bar Chart: Comparison of average petal length for each species.*

*Histogram: Distribution of petal lengths across all species.*

*Scatter Plot: Relationship between petal length and petal width.*

These visualizations helped identify key patterns in the dataset and the relationships between features.

## Key Insights

Mean Sepal and Petal Sizes:

Setosa has the smallest mean petal and sepal sizes, while Virginica has the largest.

Petal Width vs. Petal Length:

A strong positive correlation exists between petal width and petal length across species, particularly for Virginica and Versicolor.

## Species Differences:

Significant differences between species in terms of petal length and petal width. Setosa, in particular, stands out with its smaller petals.

## Visualizations

Here are the four key visualizations created for this analysis:

*1. Line Chart - Petal Length Over Measurements*

*2. Bar Chart - Average Petal Length per Species*

*3. Histogram - Distribution of Petal Length*

*4. Scatter Plot - Petal Length vs. Petal Width*

## **Conclusion**

This analysis provides a comprehensive overview of the Iris dataset, helping us understand the key features of the flowers and their relationships. The visualizations offer valuable insights into the distribution of petal and sepal lengths and widths, as well as the differences between species.

## **Requirements**

To run the analysis and generate the visualizations, you will need the following Python libraries:

Pandas

NumPy

Matplotlib

Seaborn
