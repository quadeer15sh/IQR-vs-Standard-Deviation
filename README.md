# IQR vs Standard Deviation

## Why is 1.5 used in IQR Analysis for finding out outliers ?
- In descriptive statistics, the interquartile range is a measure of statistical dispersion, which is the spread of the data. The IQR may also be called the midspread, middle 50%, fourth spread, or H‑spread. It is defined as the difference between the 75th and 25th percentiles of the data. 
-  A Z-score is a numerical measurement that describes a value's relationship to the mean of a group of values. Z-score is measured in terms of standard deviations from the mean. If a Z-score is 0, it indicates that the data point's score is identical to the mean score.
- We use the above 2 concepts and find out why 1.5 is used for finding the lower and upper limits when looking for outliers

![This is an image](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1a/Boxplot_vs_PDF.svg/1200px-Boxplot_vs_PDF.svg.png)

## Data Used
- Water Potability from Kaggle (https://www.kaggle.com/datasets/adityakadiwal/water-potability)

Python libraries required

```
pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn
```

Architecture of the model 

![This is an image](https://www.researchgate.net/profile/Larysa-Kosheva/publication/284738593/figure/fig3/AS:860915851329536@1582269742987/The-inter-quartile-range-IQR-of-a-probability-density-function-pdf-of-normal.png)
