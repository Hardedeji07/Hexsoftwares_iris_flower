This project involves an exploratory data analysis (EDA) and statistical summary of the classic Iris Dataset. This dataset is a staple in the machine learning community, typically used as a baseline for classification algorithms. The primary objective is to differentiate between three species of Iris flowers based on their physical measurements.

The Iris dataset consists of 150 observations of iris flowers collected from three different species: Setosa, Versicolor, and Virginica. Each observation includes four physical features measured in centimeters:
Sepal Length: The length of the flower's sepal. 
Sepal Width: The width of the flower's sepal.
Petal Length: The length of the flower's petal. 
Petal Width: The width of the flower's petal.

Analysis Summary
The analysis performed in Iris dataset.ipynb covers the following steps:

1. Data Cleaning
Missing Values: The dataset was audited for null entries, and it was confirmed that there are 0 missing values across all columns.
2. Statistical Analysis
Basic descriptive statistics were calculated to understand the data distribution:  

Average Sepal Length: ~5.84 cm.  

Average Petal Length: ~3.76 cm.  

Sepal Width Range: 2.0 cm to 4.4 cm

3. Data Visualization
Pairplots: A comprehensive pairplot was generated using the seaborn library to visualize the pairwise relationships between features, colored by species. This visualization helps identify which features (like petal length/width) are most effective for species classification
