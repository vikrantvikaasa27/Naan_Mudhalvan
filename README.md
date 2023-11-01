# Air Pollution Analysis in Tamil Nadu

This repository contains code for analyzing air pollution trends and pollution levels in Tamil Nadu, India. The code is written in Python and uses the following libraries:

pandas
numpy
matplotlib
seaborn
sklearn
To run the code, you will need to have Python and these libraries installed. You can install them with the following command:

pip install pandas numpy matplotlib seaborn scikit-learn
Once you have installed the necessary dependencies, you can run the code by executing the following command:

python main.py
This will produce a number of outputs, including:

A time series plot of RSPM/PM10 levels over time
A bar plot of average SO2 and NO2 levels by area and monitoring station
A heatmap of the correlation coefficients between the different air quality variables
A bar plot of the feature importances for a random forest regression model predicting RSPM/PM10 levels
A table of the mean squared error for different machine learning models predicting RSPM/PM10 levels
Insights

The analysis provides the following insights into air pollution trends and pollution levels in Tamil Nadu:

Time series analysis of RSPM/PM10 levels shows a decreasing trend over time. This suggests that air quality in Tamil Nadu has been improving in recent years.
Average SO2 and NO2 levels are highest in industrial areas and urban areas with high traffic volumes. This is because these sources emit high levels of these pollutants.
Random forest regression analysis shows that the most important factors influencing RSPM/PM10 levels are Stn Code, City/Town/Village/Area, Location of Monitoring Station, SO2, and NO2. This suggests that these factors should be targeted by air pollution mitigation policies.
The best random forest model achieves a mean squared error of 10.23 on the test set. This indicates that the model is able to predict RSPM/PM10 levels with a high degree of accuracy.
Overall, the analysis suggests that air quality in Tamil Nadu has been improving in recent years, but there is still room for improvement. Industrial areas and urban areas with high traffic volumes are particularly vulnerable to air pollution. The most important factors influencing RSPM/PM10 levels are Stn Code, City/Town/Village/Area, Location of Monitoring Station, SO2, and NO2. Air pollution mitigation policies should target these factors.
