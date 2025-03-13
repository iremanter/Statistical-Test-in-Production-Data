# Statistical-Test-in-Production-Data

**STATISTICAL DECISION MAKING - APPLYING STATISTICAL TESTS IN PRODUCTION DATA:**

The main goal of this task is to analyze the attributes of the wine production dataset to explore their significant effects on wine quality. The dataset consists of 32,485 records and includes six factors: residual sugar, free sulfur dioxide, density, pH, sulfates, and type, which could significantly affect wine quality. To examine the impact on quality of each attribute, one-way ANOVA tests and T-tests have been performed.

Based on the ANOVA test results, Tukey's Honest Significant Difference (HSD) test has been conducted to determine the optimal levels of each attribute that contribute to higher wine quality. 

For attributes that significantly affect wine quality according to the T-test results, the mean values of quality levels among groups have been compared to identify which category shows better quality.

After residual sugar, pH, and free sulfur dioxide have been tested by ANOVA, the results as follows:
- Residual Sugar: p-value (0.25311572446096287) is above 0.05 so, H0 is approved, which means there is no significant difference in quality among the three different sugar categories.
- pH: p-value (4.516421352031459e-10) is below 0.05 so, H0 is rejected, which means there is a significant difference in quality among the three different pH categories.
- Free Sulfur Dioxide: p-value (5.439591614762173e-16) is below 0.05 so, H0 is rejected, which means there is a significant difference in quality among the three different free sulfur dioxide categories.

Sulfates, density, and the type of wine are examined by using a T-test. To apply the T-test, sulfates and density were split into two categories using the median function. If the levels of these factors are higher than the median, they are categorized as high; otherwise, they are categorized as low. There is no modification needed for the type of wine because it already has two categories.
After sulfates, density, and type of wine have been tested by T-test, the results as follows:
- Sulfates: p-value (4.699141670949603e-05) is below 0.05 so, H0 is rejected, which means there is a significant difference in quality among the two different sulfates categories.
- Density: p-value (0.0) is below 0.05 so, H0 is rejected, which means there is no significant difference in quality among the two different density categories.
- Type of Wine: p-value (5.389664048076729e-102) is below 0.05 so, H0 is rejected, which means there is a significant difference in quality among the two different type of wine.

After ANOVA test results were obtained, the optimal category of each factor had to be determined to make wine better quality. Tukey HSD method have been applied and the results as follows:
- Residual Sugar Level: The best residual sugar level is low to obtain better quality wine.
- pH Level: The bestpH level is medium to obtain better quality wine.
- Free Sulfur Dioxide: The best free sulfur dioxide level is low to obtain better quality wine.

After obtaining the T-test results, the optimal category for each factor was determined to improve wine quality. The comparison of the quality means was conducted, and the results are as follows:
- Sulfate Level: The best sulfate level is high to obtain better quality wine.
- Density Level: The best density level is low to obtain better quality wine.
- Type of Wine: The best type of wine is white wine to obtain better quality wine.
