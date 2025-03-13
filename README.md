# Statistical-Test-in-Production-Data

**STATISTICAL DECISION MAKING - APPLYING STATISTICAL TESTS IN PRODUCTION DATA:**

The main goal of this task is to analyze the attributes of the wine production dataset to explore their significant effects on wine quality. The dataset consists of 32,485 records and includes six factors: residual sugar, free sulfur dioxide, density, pH, sulfates, and type, which could significantly affect wine quality. To examine the impact on quality of each attribute, one-way ANOVA tests and T-tests have been performed.

Based on the ANOVA test results, Tukey's Honest Significant Difference (HSD) test has been conducted to determine the optimal levels of each attribute that contribute to higher wine quality. 

For attributes that significantly affect wine quality according to the T-test results, the mean values of quality levels among groups have been compared to identify which category shows better quality.

After residual sugar, pH, and free sulfur dioxide have been tested by ANOVA, the results as follows:
- Residual Sugar: p-value (0.25311572446096287) is above 0.05 so, H0 is approved, which means there is no significant difference in quality among the three different sugar categories.
- pH: p-value (4.516421352031459e-10) is below 0.05 so, H0 is rejected, which means there is a significant difference in quality among the three different pH categories.
- Free Sulfur Dioxide: p-value (5.439591614762173e-16) is below 0.05 so, H0 is rejected, which means there is a significant difference in quality among the three different free sulfur dioxide categories.
