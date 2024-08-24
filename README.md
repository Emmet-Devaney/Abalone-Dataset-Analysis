# Abalone-Dataset-Analysis

This repository is an analysis of the Abalone Dataset by Nash ,Warwick, Sellers,Tracy, Talbot,Simon, Cawthorn,Andrew, and Ford,Wes. (1995).

## Libraries

- pandas
- matplotlib
- seaborn

# 1.  About This Repository 

This repository will be taking a look into the shellfish know as an Abalone. This is a large marine gastropod mollusk.

![alt text](<Image Files/Abalone Picture.png>)

We will be focusing on two varibles in the supplied data:
- The Whole Weight of the Abalone.
- The Shell Height of the Abalone.

As we progress through the jupyter notebook and display the information, we will see what conclusions can be drawn.

**The files that this Repository contains:**

* **README.md**
    - A summary and conclusion of the statistical and visual analysis of the Abalone Dataset

* **abalone.csv**
    - This file contains the dataset in question

* **abalone.ipynb**
    - A statistical and visual investigation using pandas, matplotlib, and seaborn.



# 2. The Dataset

This dataset had been used to predict the age of abalones from physical measurements.

**The Variables:**
-	Sex: Male; Female; and Infant
-	Length: Longest shell measurement in millimetres
-	Diameter: perpendicular to length in millimetres
-	Height: with meat in shell in millimetres
-	Whole Weight: Whole abalone in grams
-	Shucked Weight: weight of meat in grams
-	Viscera Weight: gut weight (after bleeding) in grams
-	Shell Weight: after being dried in grams


# 3. The Analysis of Data

For this project, I will be using pandas to read the dataset and a combination of matplotlib and seaborn to perform a statistical investigation and illustrate patterns present.


![alt text](<Image Files/Analysis of Data - Abalone.png>)


# 4. Displaying the Statistics

The describe function in pandas shows the basic statistics e.g means, standard deviations, medians, etc.

![alt text](<Image Files/Display Of Statistics - Abalone.png>)

# 5. Data Visualisation

Below I have included visualisations of the data to better understand the differences and correlations between the variables measured:

**Histograms:**

![alt text](<Image Files/Whole Weight Histogram - Abalone.png>)

![alt text](<Image Files/Shell Height Histogram.png>)

**Barcharts:**

![alt text](<Image Files/Weight By Sex Barchart.png>)

![alt text](<Image Files/Height By Sex Barchart.png>)

# 6. Correlations

Using the Pandas correlation function, we may be able to discern a distinction between the variables measured.

![alt text](<Image Files/Correlations - Abalone.png>)


A good way to visualise this information is through a heatmap:

![alt text](<Image Files/Abalone Heatmap.png>)

# 7. Conclusions

My conclusions based on the data are below:
*	There is a strong correlation between the Shell Height and the Whole Weight of the Abalone, which can be seen on the heatmap.
*   The relationship between the Whole Weight and the Sex of the Abalone is linear. However, the Shell Height shows a clear difference between the Males and the Females.




# 8. References
Nash,Warwick, Sellers,Tracy, Talbot,Simon, Cawthorn,Andrew, and Ford,Wes. (1995). Abalone. UCI Machine Learning Repository. 
https://doi.org/10.24432/C55C7W.

Mendis, A. (2019) Data Visualization in Python: Matplotlib vs Seaborn. KDnuggets. https://www.kdnuggets.com/2019/04/data-visualization-python-matplotlib-seaborn.html


Suprabhat Kumar, 2018 - kaggle kernels pull suprabhatsk/abalone-a-simple-guide-to-logistic-regression
https://www.kaggle.com/code/suprabhatsk/abalone-a-simple-guide-to-logistic-regression

# 9. Further Links:

pandas.DataFrame.to_string: https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_string.html

How to create a seaborn correlation heatmap in Python?: https://www.geeksforgeeks.org/how-to-create-a-seaborn-correlation-heatmap-in-python/

