# Bee-Finance-Analysis

# Table of Contents
1. Project Overview
2. Data and Analysis
3. Discussion
4. Recommendations
5. References

# Project Overview
The purpose of this project is to gain insight into the financial effects of the declining honey bee (*Apis Mellifera Linnaeus*) population in the United States. "Honey bees alone pollinate 80 percent of all flowering plants, including more than 130 types of fruits and vegetables” (1) making them a keystone species and essential for the reproduction of non-asexual flora. 

# Data
The data was retrieved in the form of a CSV file from Kaggle.com and provided by the National Agricultural Statistics Service of the USDA https://www.kaggle.com/datasets/mohitpoudel/us-honey-production-19952021.

# Methodology
- Python: EDA, modification, and cleaning of data 
- Tableau: Reporting

# EDA
Initial exploration of the data shows that there are no missing values and the datatypes are correct.

# Modification of Data
- Column "year": transformed to string dtype
- Column "unnamed: 0" removed as it is redundant
- Column "colonies_number": values were scaled for improved visibility in plotting. All values were multiplied by 0.001 (ex: 1500.0 -> 15.0)
- Column "average_price": values were scaled to better reflect the price of honey by the pound (ex: intitial value of 86.0 -> 8.60)

# Visualizations
# *Figure 1* shows the decline of production levels in the top 5 honey producing states
![Decline of production levels](https://github.com/DanielWrightGIT/Bee-Finance-Analysis/blob/main/prod%20decline.PNG)

# *Figure 2* shows stocks held by producers. The color represents the average price of honey.
![stock](https://github.com/DanielWrightGIT/Bee-Finance-Analysis/blob/main/stocks.PNG)

# *Figure 3* shows the average colony yield in LBS per state (continental US only)
![colony yield](https://github.com/DanielWrightGIT/Bee-Finance-Analysis/blob/main/colony%20yield.PNG)

# *Figure 4* shows the combined visualizations in a tableau dashboard. The year slider can be altered to show custom time ranges and is applied to all of the visualizations simultaneously. 
![tableau viz](https://github.com/DanielWrightGIT/Bee-Finance-Analysis/blob/main/intiial.PNG)
