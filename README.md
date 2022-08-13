# IQR vs Standard Deviation

## Why is 1.5 used in IQR Analysis for finding out outliers ?
- In descriptive statistics, the interquartile range is a measure of statistical dispersion, which is the spread of the data. The IQR may also be called the midspread, middle 50%, fourth spread, or H‑spread. It is defined as the difference between the 75th and 25th percentiles of the data. 
-  A Z-score is a numerical measurement that describes a value's relationship to the mean of a group of values. Z-score is measured in terms of standard deviations from the mean. If a Z-score is 0, it indicates that the data point's score is identical to the mean score.
- We use the above 2 concepts and find out why 1.5 is used for finding the lower and upper limits when looking for outliers

![This is an image](https://upload.wikimedia.org/wikipedia/commons/8/89/Boxplot_vs_PDF.png)

## Data Used
- Water Potability from Kaggle (https://www.kaggle.com/datasets/adityakadiwal/water-potability)

Python libraries required

```
pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn
```

## IQR for Outlier Detection
![This is an image](https://miro.medium.com/max/1400/1*2c21SkzJMf3frPXPAR_gZA.png)

## 3 Sigma for Outlier Detection
![This is an image](https://miro.medium.com/max/1400/1*ARpoeY3MdhFImq0JXAXtRw.png)




