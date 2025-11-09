## About

**The first analysis shows an ANOVA test and post-hoc comparisons on the measures of tumor size from an animal xenograft experiment designed to compare four treatments for cancers. The second analysis demonstrates the use of linear regession to assess the relatoinship of BMI and ease of trachael intubations.**


[Click here to view my statistical summaries and graphs](https://alt392.github.io/BIOST-Project-4/Tumor-Growth-and-Intubation-Analysis.html)

## Overall Summary

For the first analysis, at a significance level of a = 0.05, our first post-hoc pairwise treatment comparisons show the drug + radiation group differed from the other groups with p-values of 0.0006, 0.0085, and 0.0028, indicating they are all statistically significant. We then performed a Bonferroni correction to control any type 1 errors, and saw that the control vs drug + radiation group (p = 0.0038, Bonferroni-adjusted) and the radiation only vs drug + radition (p = 0.0165, Bonferroni-adjusted) were statistically significant. The only one of note that was above 0.05 was the comparison between drug only and drug + radiation (p = 0.0509, Bonferroni-adjusted) indicating this comparison was not statistically significant. Furthermore, by constructing simultaneous confidence intervals we note the drug + radiation group (~681, ~1581) had minimal overlap with the other three groups. Overall, we can conclude the drug + radiation treatment significantly reduced mean tumor size compared to the control and radiation-only groups, and showed the largest observed reduction of tumor size among all groups. 

For the second analysis, BMI does not appear to be a good predictor of ease of intubation. The correlation coefficient was -0.09, which indicates an extremely weak negative association between the variables. Furthermore, after conducting a hypothesis test for the slope at a significance level of 0.05, the p-value was 0.37. Since 0.37 >> 0.05, we fail to reject the null hypothesis that there is no significant linear association between BMI and ease of intubation.
