# Perform multiple linear regression for marketing promotion data.
---
In this notebook, I'll be analyzing a small business' historical marketing promotion data. Each row corresponds to an independent marketing promotion where their business uses TV, social media, radio, and influencer promotions to increase sales.

![Sale from unsplash](https://github.com/mohamedyosef101/mohamedyosef101/assets/118842452/b1055892-f6e4-4e18-a8a2-571470720a4a)

# Key Findings
According to the model, high TV promotional budgets result in significantly more sales than medium and low TV promotional budgets. For example, the model predicts that a Low TV promotion is 154.2971 lower on average than a high TV promotion given the same Radio promotion.

The coefficient for radio is positive, confirming the positive linear relationship shown earlier during the exploratory data analysis.

The p-value for all coefficients is  0.000
 , meaning all coefficients are statistically significant at  𝑝=0.05
 . The 95% confidence intervals for each coefficient should be reported when presenting results to stakeholders.

For example, there is a  95%
  chance the interval  [−163.979,−144.616]
  contains the true parameter of the slope of  𝛽𝑇𝑉𝐿𝑜𝑤
 , which is the estimated difference in promotion sales when a low TV promotional budget is chosen instead of a high TV promotion budget.

 ## Recommendations
High TV promotional budgets have a substantial positive influence on sales. The model estimates that switching from a high to medium TV promotional budget reduces sales by  $75.3120
  million (95% CI  [−82.431,−68.193])
 , and switching from a high to low TV promotional budget reduces sales by  $154.297
  million (95% CI  [−163.979,−144.616])
 . The model also estimates that an increase of  $1
  million in the radio promotional budget will yield a  $2.9669
  million increase in sales (95% CI  [2.551,3.383]
 ).

Thus, it is recommended that the business allot a high promotional budget to TV when possible and invest in radio promotions to increase sales.

# **Useful Resources**

* Google LLC. (2023). [*Regression Analysis: Simplify Complex Data Relationships*](https://www.coursera.org/learn/regression-analysis-simplify-complex-data-relationships?specialization=google-advanced-data-analytics). Coursera

* Saragih, H.S. (2020). [*Dummy Marketing and Sales Data*](https://www.kaggle.com/datasets/harrimansaragih/dummy-advertising-and-sales-data). Kaggle Datasets.

* Kylie Ying. (2022). [*Machine Learning for Everybody: Regression*](https://youtu.be/i_LwzRVP7bg?si=OKiUNxm4eOTf8OxQ). YouTube.

* DATAtab. (2021). [*Regression Analysis | Full course*](https://youtu.be/0m-rs2M7K-Y?si=P6_Z7odr6IxR2DqX). YouTube

--- 

💬 If you have any question, feel free to send me a message on **[LinkedIn](https://linkedin.com/in/mohamedyosef101)**.
