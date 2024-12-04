# <span style="color:skyblue">Mobile Games A/B Testing - Cookie Cats</span>


<img src="https://play-lh.googleusercontent.com/a8LfQ-50UmPUw-ubM0vqrmK7RUJ1wup2H9Od-5hBZDUPK9XdnDyFKiLjJaws2UwgspE=w526-h296-rw" style="display: block; margin-left: auto; margin-right: auto; width: 250px;"/>

 

**A/B Testing Analysis:**

The analysis is based on data from 90,189 players who installed the game during the A/B test period. Each player is uniquely identified in the dataset and categorized based on the app version they experienced. Players were divided into two groups:

- **Control Group (gate_30):** Players encountered a progression gate at level 30.
- **Test Group (gate_40):** Players encountered the progression gate at level 40.


**Business Case:** 🐱

The test aims to evaluate whether moving the progression gate from level 30 to level 40 (test group) increases the total number of game rounds played (sum_gamerounds) without negatively impacting player retention metrics (retention_1 and retention_7), which are considered guardrail metrics. 

## Conclusion
Based on the analysis, the results show no meaningful or statistically significant improvement in the total Cookie Cats game rounds when moving the progression from level 30 to level 40.

The 95% confidence interval (-17.7677, 15.4527) includes zero (which means that the true difference between the two groups could be zero), and the p-value of 0.3759 further supports the conclusion that there is no significant difference between the control (gate_30) and test (gate_40) groups.

Additionally, our guardril metrics (retention at 1 and 7 days) declined in the test group to 0.442283 for 1 day and 0.182000 for 7 days, compared to the control group which the retention was 0.448188 for 1 day and 0.190201 for 7 days, suggesting a potential negative impact on player engagement.

Given these findings, we recommend maintaining the control group (gate_30) as the progression gate. Deploying the test group does not present clear benefits and poses risks to player retention and overall engagement.