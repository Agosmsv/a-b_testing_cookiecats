# <span style="color:skyblue">Mobile Games A/B Testing - Cookie Cats</span>


<img src="https://play-lh.googleusercontent.com/a8LfQ-50UmPUw-ubM0vqrmK7RUJ1wup2H9Od-5hBZDUPK9XdnDyFKiLjJaws2UwgspE=w526-h296-rw" style="display: block; margin-left: auto; margin-right: auto; width: 250px;"/>

 

**A/B Testing Analysis:**

The analysis is based on data from 90,189 players who installed the game during the A/B test period. Each player is uniquely identified in the dataset and categorized based on the app version they experienced. Players were divided into two groups:

- **Control Group (gate_30):** Players encountered a progression gate at level 30.
- **Test Group (gate_40):** Players encountered the progression gate at level 40.


**Business Case:**🐱

The test aims to evaluate whether moving the progression gate from level 30 to level 40 (test group) increases the total number of game rounds played (sum_gamerounds) without negatively impacting player retention metrics (retention_1 and retention_7), which are considered guardrail metrics. 

## Conclusion
The test aimed to evaluate whether shifting the progression gate from level 30 (control group) to level 40 (test group) increases the total number of game rounds played (sum_gamerounds) without negatively affecting player retention (retention_1 and retention_7).

Based on the results, the mean difference in sum_gamerounds between the two groups is 0.3107, with a 95% confidence interval of (0.3107, 3.0395). Since this interval does not include zero, we reject the null hypothesis (H₀), which stated that there would be no significant difference between the groups.
