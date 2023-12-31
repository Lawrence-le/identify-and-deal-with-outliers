# Identify and deal with outliers

## Exploratory Data Analysis (EDA)

## Objective

I will be analyzing lightning strike data obtained from the National Oceanic and Atmospheric Administration (NOAA) spanning the years 1987 to 2020 for my project document. To manage the extensive dataset, which consists of millions of rows, I've undertaken preprocessing to streamline the information, retaining only the year and the corresponding count of lightning strikes.

The primary objective of my project is to explore the variation in total lightning strike counts for each year and pinpoint any outliers within the dataset. 

## Method Used

* Boxplot visual tool to effectively analyze data distribtuion by percentiles and quartiles.

![image](https://github.com/Lawrence-le/identify-and-deal-with-outliers/assets/151991077/84be2eff-fb9c-46f1-9c76-8c3b8d6ad21b)

* Using IQR method for Outlier Detection

![image](https://github.com/Lawrence-le/identify-and-deal-with-outliers/assets/151991077/1d0ad196-fc85-4080-9515-0c6922e3a400)

* Plot scatterplot to visualise the outliers in red

![image](https://github.com/Lawrence-le/identify-and-deal-with-outliers/assets/151991077/5508440f-48eb-40c4-bff9-fd7423b0e357)

* Understanding outliers impact on the mean and median

---

## Key Takeaways:

**🌐 Visual Exploration:**  
Whisker plots provided an insightful visual representation of data spread, making it easy to identify central tendencies and potential outliers.

**📉 Robust Outlier Detection:**  
The 1.5 IQR rule, coupled with Python-powered scatterplots, offered a robust method to pinpoint potential outliers, enhancing data quality and decision-making.
Impact:

**🚀 Informed Decision-Making:**  
By identifying outliers, we ensured that our analyses and insights were based on a more accurate representation of the underlying data distribution.

**📈 Data Quality Improvement:**  
This approach contributed to enhancing the overall quality and reliability of our dataset.

Reference: [https://towardsdatascience.com/why-1-5-in-iqr-method-of-outlier-detection-5d07fdc82097](https://towardsdatascience.com/why-1-5-in-iqr-method-of-outlier-detection-5d07fdc82097)


